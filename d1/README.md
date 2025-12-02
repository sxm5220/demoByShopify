<h1 align="center" style="position: relative;">
  <br>
    <img src="./assets/shoppy-x-ray.svg" alt="logo" width="200">
  <br>
  Shopify 骨架主题
</h1>

一个极简且结构精良的 Shopify 主题，旨在帮助你快速上手。设计时充分考虑了模块化、可维护性以及 Shopify 的最佳实践。


<p align="center">
  <a href="./LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License"></a>
  <a href="./actions/workflows/ci.yml"><img alt="CI" src="https://github.com/Shopify/skeleton-theme/actions/workflows/ci.yml/badge.svg"></a>
</p>

## 新建项目

```bash
shopify theme init
```

### 运行项目

```bash
shopify theme dev
```

### 使用tailwindcss

```bash
npm install tailwindcss @tailwindcss/cli
```
### 在项目下新建src文件夹,然后新建tailwindcss.css文件,并在文件中写入以下内容:

```bash
@import "tailwindcss";
```

### 在项目根目录下Terminal中运行

```bash
$ npx @tailwindcss/cli -i ./css/tailwind.css -o ./assets/critical.css --watch
```

## License

Skeleton Theme is open-sourced under the [MIT](./LICENSE.md) License.
