# Vue 3 + Typescript + Vite + Electron

该项目为一个以 Vite 快速搭建一个 Electron+Vue3+TS 的项目

# 第一步 首先安装淘宝镜像

找到 C 盘用户目录下的.npmrc 配置文件，配置 npm 的镜像为淘宝的镜像，具体请去https://www.npmmirror.com查看镜像地址

这里也提示淘宝的 npm 镜像地址为https://npmmirror.com/mirrors/
electron 的镜像地址为https://npmmirror.com/mirrors/electron/
electron_builder_binaries_mirror 的镜像地址为https://npmmirror.com/mirrors/electron-builder-binaries/

# 第二步 使用 npm 全局安装 pnpm

npm install -g pnpm

# 第三步 使用 pnpm 命令来执行 Vite 创建 Vue_demo 项目

pnpm craete vite vue_demo

提示：本项目使用的是 vue3+ts 的配置

# 第四步 使用 pnpm 命令启动 vue 项目

pnpm i

pnpm dev

# 第五步 使用 pnpm 来安装 electron 项目依赖以及 electron-builder 项目依赖

pnpm add electron -D

pnpm add electron-builder -D
