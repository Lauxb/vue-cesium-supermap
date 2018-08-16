# VUE CESIUM SUPERMAP

<p align="center">
  <img src="https://lauxb.github.io/vue-cesium-supermap/favicon.png" width="200px">
</p>
<p align="center">基于 VUE 2.x 的 SuperMap iClient 3D for WebGL(built on Cesium)组件</p>

[![npm](https://img.shields.io/npm/v/vue-cesium-supermap.svg)]()
[![Travis](https://img.shields.io/travis/lauxb/vue-cesium-supermap.svg)]()
[![Package Quality](http://npm.packagequality.com/shield/vue-cesium-supermap.svg)](http://packagequality.com/#?package=vue-cesium-supermap)
[![npm](https://img.shields.io/npm/dm/vue-cesium-supermap.svg)]()
[![license](https://img.shields.io/github/license/lauxb/vue-cesium-supermap.svg)]()

## 语言

- [中文](https://github.com/lauxb/vue-cesium-supermap/blob/master/README.zh.md)
- [English](https://github.com/lauxb/vue-cesium-supermap/blob/master/README.md)

## 文档

[https://lauxb.github.io/vue-cesium-supermap](https://lauxb.github.io/vue-cesium-supermap)

## 开始

### 安装

```bash
npm i --save vue-cesium-supermap
```

### 初始化

```javascript
import Vue from 'vue'
import SuperMapCesium from 'vue-cesium-supermap'

Vue.use(SuperMapCesium, {
  // cesiumPath 是指引用的Cesium的文件夹路径， 如
  cesiumPath: './statics/Cesium'
})
```

### 使用

```vue
<template>
  <div class="content">
    <sm-viewer>
    </sm-viewer>
  </div>
</template>

<style>
.content {
  background-color: #f9f9f9;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
</style>
```

## 贡献

[贡献指南](https://github.com/lauxb/vue-cesium-supermap/blob/master/CONTRIBUTING.md)

## 协议

[MIT 许可证](https://opensource.org/licenses/MIT)

版权所有 (c) 2018至今, lauxb <188013260@qq.com>

## 感谢

该项目学习、借鉴了[vue-baidu-map](https://github.com/Dafrok/vue-baidu-map)，特此鸣谢！
