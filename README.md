# 骨架图demo
> 起因: 官方的demo没法正常运行

## 运行/使用

- 1. 启动
```bash
yarn run dev
```
- 2. 在开发页面中通过 Ctrl|Cmd + enter 呼出插件交互界面(windows 10 下好像没起作用)，或者在在浏览器的 JavaScript 控制台内输入toggleBar 呼出交互界面。

- 3. 点击交互界面中的按钮，进行骨架页面的预览，这一过程可能会花费 20s 左右时间，当插件准备好骨架页面后，会自动通过浏览器打开预览页面，如下图。

![default](https://user-images.githubusercontent.com/24327880/50219373-f4177a80-03c9-11e9-9616-6d51c0161634.png)


- 4. 扫描预览页面中的二维码，可在手机端预览骨架页面，可以在预览页面直接编辑源码，通过点击右上角写入按钮，将骨架页面写入到 shell.html 文件中。

- 5. 通过 webpack 重新打包应用，当页面重新启动后，就能够在获取到数据前看到应用的骨架结构了(用弱网下观看效果会更佳)。

## ERROR

- 1. Cannot read property 'properties' of undefined

更改webpack版本

```bash
npm i webpack-cli@3.1.1 -D
```

## 插件文档
[page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin)
