## node-sftp-deploy [![NPM Version](http://img.shields.io/npm/v/sftp2.svg?style=flat)](https://www.npmjs.com/package/node-sftp-deploy "Package version")

[![NPM Downloads](https://img.shields.io/npm/dm/sftp2.svg?style=flat)](https://www.npmjs.com/package/node-sftp-deploy "NPM Downloads")
[![dependencies](https://img.shields.io/david/weixin/node-sftp-deploy.svg)](https://ci.appveyor.com/project/weixin/node-sftp-deploy "Dependencies")
[![Join the chat at https://gitter.im/weixin/node-sftp-deploy](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/TmT?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![TmT Name](https://img.shields.io/badge/Team-TmT-brightgreen.svg?style=flat)](https://github.com/orgs/TmT/people "Tencent Moe Team")
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](http://opensource.org/licenses/MIT "Feel free to contribute.") 

> Upload and deploy files from SFTP within username & password.

## Install


```bash
npm install --save node-sftp-deploy
```

## Usage

```javascript
var sftp = require('node-sftp-deploy');
sftp({
    "host": "10.10.10.10",
    "port": "20",
    "user": "user",
    "pass": "pass",
    "remotePath": "",
    "sourcePath": "./"
}, function(){
    //Success Callback
});

//Support Promise
sftp(sftpConfig).then(function(){
    //Success Callback
});
```


## Contributing

This repo is build and maintained by [TmT Team](https://github.com/orgs/TmT/people).
If you get any bugs or feature requests, please open a new [Issue](https://github.com/weixin/node-sftp-deploy/issues) or send us [Pull Request](https://github.com/weixin/node-sftp-deploy/pulls), Thank you for your contributions.
