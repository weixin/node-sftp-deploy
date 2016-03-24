## sftp2 [![NPM Version](http://img.shields.io/npm/v/sftp2.svg?style=flat)](https://www.npmjs.com/package/sftp2 "Package version")

[![NPM Downloads](https://img.shields.io/npm/dm/sftp2.svg?style=flat)](https://www.npmjs.com/package/sftp2"NPM Downloads")

[![Join the chat at https://gitter.im/weixin/sftp2](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/TmT?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![TmT Name](https://img.shields.io/badge/Team-TmT-brightgreen.svg?style=flat)](https://github.com/orgs/TmT/people "Tencent Moe Team")
[![License](https://img.shields.io/npm/l/sftp2.svg?style=flat)](http://opensource.org/licenses/MIT "Feel free to contribute.")

> Upload and deploy files from SFTP within username & password.

## Install


```
npm install --save sftp2
```

## Usage

```javascript
var sftp = require('sftp2');

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
If you get any bugs or feature requests, please open a new [Issue](https://github.com/weixin/gulp-lazyimagecss/issues) or send us [Pull Request](https://github.com/weixin/gulp-lazyimagecss/pulls), Thank you for your contributions.
