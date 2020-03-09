## cloudbase-adapter-qq_mp

[![NPM Version](https://img.shields.io/npm/v/cloudbase-adapter-qq_mp.svg?style=flat)](https://www.npmjs.com/package/cloudbase-adapter-qq_mp)
[![](https://img.shields.io/npm/dt/cloudbase-adapter-qq_mp.svg)](https://www.npmjs.com/package/cloudbase-adapter-qq_mp)

tcb-js-sdk QQ小程序适配器

## 安装
```bash
npm i cloudbase-adapter-qq_mp -S
```

### Unpkg
可以使用unpkg托管的js文件，地址如下：
https://unpkg.com/cloudbase-adapter-qq_mp/dist/index.js

## 使用
### ES Module
```javascript
import tcb from 'tsb-js-sdk';
import adapter from 'cloudbase-adapter-qq_mp';

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapter);
// 2.数组形式传参
tcb.useAdapters([adapter]);
// adapter必须在init之前传入
tcb.init();
```

### CommonJS
```javascript
const tcb = require('tsb-js-sdk');
const {adapter} = require('cloudbase-adapter-qq_mp');

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapter);
// 2.数组形式传参
tcb.useAdapters([adapter]);
// adapter必须在init之前传入
tcb.init();
```