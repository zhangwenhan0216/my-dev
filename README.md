<p align="center">
    <img alt="logo" src="https://img.yzcdn.cn/vant/logo.png" width="120" style="margin-bottom: 10px;">
</p>

<h1 align="center">Vant</h1>

<p align="center">轻量、可靠的移动端 Vue 组件库</p>

<p align="center">
    <img src="https://img.shields.io/npm/v/vant.svg?style=flat-square" alt="npm version" />
    <img src="https://img.shields.io/github/workflow/status/youzan/vant/CI/dev?style=flat-square" alt="npm version" />
    <img src="https://img.shields.io/codecov/c/github/youzan/vant/dev.svg?style=flat-square&color=#4fc08d" alt="Coverage Status" />
    <img src="https://img.shields.io/npm/dm/vant.svg?style=flat-square&color=#4fc08d" alt="downloads" />
    <img src="https://img.shields.io/jsdelivr/npm/hm/vant?style=flat-square" alt="Jsdelivr Hits">
    <img src="https://img.badgesize.io/https://unpkg.com/vant/lib/vant.min.js?compression=gzip&style=flat-square&label=gzip%20size&color=#4fc08d" alt="Gzip Size" />
</p>

<p align="center">
  🔥 <a href="http://172.16.0.25/potato-chips/vant-dgg.git">文档网站</a>
</p>

---

### 介绍

目前 Vant 官方提供了 [Vue 版本](https://vant-contrib.gitee.io/vant)和[微信小程序版本](http://vant-contrib.gitee.io/vant-weapp)，并由社区团队维护 [React 版本](https://github.com/mxdi9i7/vant-react)。

## 特性

- 60+ 高质量组件，覆盖移动端各类场景
- 90%+ 单元测试覆盖率，提供稳定性保障
- 完善的中英文文档和示例
- 支持按需引入
- 支持主题定制
- 支持国际化
- 支持 TS
- 支持 SSR

## 安装

```bash
# 通过 npm 安装
npm i @chipspc/vant-dgg -S

# 通过 yarn 安装
yarn add @chipspc/vant-dgg
```

<!-- > Tips: Vue 3 项目请安装 Vant 3.0，参见 [issue#7035](https://github.com/youzan/vant/issues/7035) -->

## 快速上手

```js
import Vue from 'vue';
import { Button } from '@chipspc/vant-dgg';
import '@chipspc/vant-dgg/lib/index.css';

Vue.use(Button);
```

vant 也支持按需引入、CDN 引入等方式，详细说明见 [快速上手](https://vant-contrib.gitee.io/vant#/zh-CN/quickstart).

## 贡献代码

修改代码请阅读我们的 [开发指南](https://vant-contrib.gitee.io/vant/#/zh-CN/contribution)。

使用过程中发现任何问题都可以提 [Issue](https://github.com/youzan/vant/issues) 给我们，当然，我们也非常欢迎你给我们发 [PR](https://github.com/youzan/vant/pulls)。

## 浏览器支持

现代浏览器以及 Android 4.0+, iOS 8.0+.
