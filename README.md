# ss-mirror

> Base on WebSocket proxy, deploy on HeroKu.

## Usage

1. Fork this project.
2. Create new App in Heroku.
3. Deploy branch.
4. Set the password and method, support: `rc4-md5` `aes-256-cfb` `camellia-256-cfb`.
5. Clone this project and install dependencies.
6. `node local.js -s $APPNAME.herokuapp.com -l 1080 -m $METHOD -k $PASSWORD -r 80`
7. Then it will output: `server listening at { address: '127.0.0.1', family: 'IPv4', port: 1080 }`
8. OK, enjoy it! 🤡

## About

This project fork from `521xueweihan/shadowsocks-heroku`, you can find it on GitHub.

## License

MIT