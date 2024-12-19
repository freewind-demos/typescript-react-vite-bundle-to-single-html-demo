TypeScript React Vite Bundle to Single HTML Demo
=================================

一个使用TypeScript + React + Vite构建的演示项目，可以将所有资源打包成单个HTML文件。

## 功能特点

- 使用TypeScript进行类型安全的开发
- 使用React构建用户界面
- 使用Vite作为构建工具
- 使用vite-plugin-singlefile插件将所有资源打包成单个HTML文件
- 包含PostCSS支持

## 技术栈

- React 17.0.2
- TypeScript 5.4.3
- Vite 5.1.6
- vite-plugin-singlefile 2.1.0

## 安装

```bash
pnpm install
```

## 开发

```bash
pnpm start
```

这将自动在浏览器中打开页面。

## 构建

```bash
pnpm build
```

构建后的文件将生成在`dist`目录下，所有资源都会被打包到一个HTML文件中。
