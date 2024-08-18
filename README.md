# sealdice-ui

> 海豹核心的前端实现

## 说明

本仓库为海豹核心的前端实现，使用 Vue3 + ElementPlus + tailwindcss 开发。

后端仓库：[sealdice-core](https://github.com/sealdice/sealdice-core)

此仓库的 Issue 已关闭，请在后端仓库中提交 Issue。包括与前端相关的 Issue。

## 安装 pnpm

首先下载nodejs，然后执行指令

```bash
npm install pnpm
```

## 部署

```bash
pnpm install
```

### 开发环境

```bash
pnpm run dev
```

### 生产环境

```bash
pnpm run build
```

最终完成的前端位于目录 ```./dist/``` 下，请将其复制到后端目录的 ```./static/frontend```中

其他内容待补充
