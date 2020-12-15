# packi-print

[![TypeScript](https://img.shields.io/badge/lang-typescript-blue.svg)](https://www.tslang.cn/) [![Build Status](https://travis-ci.org/yusangeng/packi-print.svg?branch=master)](https://travis-ci.org/yusangeng/packi-print) [![Coverage Status](https://coveralls.io/repos/github/yusangeng/packi-print/badge.svg?branch=master)](https://coveralls.io/github/yusangeng/packi-print?branch=master) [![Npm Package Info](https://badge.fury.io/js/packi-print.svg)](https://www.npmjs.com/package/packi-print) [![Downloads](https://img.shields.io/npm/dw/packi-print.svg?style=flat)](https://www.npmjs.com/package/packi-print)

## 综述

cli 项目使用的控制台打印工具, 主要用于 packi 项目.

## 安装

```shell
npm i packi-print --save
```

## 使用

```typescript
import { setPrintLevel, PRINT_LEVEL, debug, info, warn, error } from "packi-print";

setPrintLevel(PRINT_LEVEL.DEBUG);

debug(`text1`);
info(`text2`);
warn(`text3`);
error(`text4`);
```
