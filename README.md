# ooomap uni-app 项目模板

本`uni-app`项目使用`vue3/vite`模块创建([文档](https://uniapp.dcloud.net.cn/quickstart-cli.html))

展示了如何在`uni-app`小程序开发中使用`ooomap SDK`, 并包含基础的`2D/3D切换`组件和`楼层切换`组件

# 使用方式

可以直接下载`zip`包

或使用`git clone`的方式

```bash
git clone https://github.com/easyfrog/ooomap-uniapp.git

cd ooomap-uniapp

npm install

npm run dev:mp-weixin

```

然后使用 微信小程序开发者工具 打开 `ooomap-uniapp/dist/dev/mp-weixin` 目录, 即可查看效果

> 另外由于微信小程序开发者工具的一些*bug*, 是无法直接在开发者工具中看到组件的. 因为被地图的canvas遮挡了
> 此问题微信官方的解答是, 使用`预览`, 以真机的效果为准, 真机预览时可以正常看到组件