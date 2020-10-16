error: Parsing error: Unexpected token < at src\views\result\Error.vue:1:1:
> 1 | <template>
    | ^
  2 |   <a-card :bordered="false" style="margin: -24px -24px 0px;">
  3 |     <result type="error" :title="title" :description="description">
  4 |       <template slot="action">


error: Parsing error: Unexpected token < at src\views\result\Success.vue:1:1:
> 1 | <template>
    | ^
  2 |   <a-card :bordered="false" style="margin: -24px -24px 0px;">
  3 |     <result type="success" :description="description" :title="title">
  4 |       <template slot="action">


error: Parsing error: Unexpected token < at src\views\role\RoleList.vue:1:1:
> 1 | <template>
    | ^
  2 |   <a-card :bordered="false" :style="{ height: '100%' }">
  3 |     <a-row :gutter="24">
  4 |       <a-col :md="4">


error: Parsing error: Unexpected token < at src\views\user\Login.vue:1:1:
> 1 | <template>
    | ^
  2 |   <div class="main">
  3 |     <a-form
  4 |       id="formLogin"


error: Parsing error: Unexpected token < at src\views\user\Register.vue:1:1:
> 1 | <template>
    | ^
  2 |   <div class="main user-layout-register">
  3 |     <h3><span>注册</span></h3>
  4 |     <a-form ref="formRegister" :form="form" id="formRegister">


error: Parsing error: Unexpected token < at src\views\user\RegisterResult.vue:1:1:
> 1 | <template>
    | ^
  2 |   <result
  3 |     :isSuccess="true"
  4 |     :content="false"


error: Parsing error: The keyword 'import' is reserved at tests\unit\electron.spec.js:4:1:
  2 |  * @jest-environment node
  3 |  */
> 4 | import spectron from 'spectron'
    | ^
  5 | import { testWithSpectron } from 'vue-cli-plugin-electron-builder'
  6 | jest.setTimeout(50000)
  7 |


error: Parsing error: The keyword 'const' is reserved at babel.config.js:1:1:
> 1 | const IS_PROD = ['production', 'prod'].includes(process.env.NODE_ENV)
    | ^
  2 |
  3 | const plugins = []
  4 | if (IS_PROD) {


error: Parsing error: The keyword 'const' is reserved at vue.config.js:1:1:
> 1 | const path = require('path')
    | ^
  2 | const webpack = require('webpack')
  3 | const createThemeColorReplacerPlugin = require('./config/plugin.config')
  4 |


error: Parsing error: The keyword 'const' is reserved at webstorm.config.js:2:1:
  1 | 'use strict'
> 2 | const webpackConfig = require('@vue/cli-service/webpack.config.js')
    | ^
  3 | module.exports = webpackConfig
  4 |


191 errors found.