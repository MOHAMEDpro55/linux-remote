# linux-remote
A webside remote desktop of Linux.
## Requested
- A Linux system.
- ssh server
- A Modern Browser like Chrome.

## Install
`npm install linux-remote -g`

`sudo linux-remote install`

`cd /opt/linux-remote`

`npm install`

## Config
修改  `./config.js`. 如下:
***http server:***
```js
module.exports = {
  port: 3000
};
```


***使用现成ssl证书***
```js
module.exports = {
  ssl: {
    cert: '/etc/letsencrypt/live/lr.godmod.cn/cert.pem',
    key: '/etc/letsencrypt/live/lr.godmod.cn/privkey.pem'
  },
  port: 443
};
```
## 开始
`sudo node index.js`

# uninstall
`linux-remote uninstall`
