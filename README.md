# vue-baidu-map 组件下载,打包网页引入方法：
```
1. 下载百度地图：   
	vue-baidu-map   https://github.com/Dafrok/vue-baidu-map.git
	地图中文文档： https://dafrok.github.io/vue-baidu-map/#/zh/index
	vue：https://cn.vuejs.org/v2/guide/installation.html
2. 下载nodejs并安装
    - 切换淘宝源cnpm   'npm install -g cnpm --registry=https://registry.npm.taobao.org'
3. 安装依赖， 打包地图
    进入地图组件目录：
	C:\Users\Administrator\Desktop\map\vue-baidu-map-master
	cmd：
	cnpm install
    npm run build	   生成地图组件打包后的js文件-----index.js
	构建地图组件（用webpack打包供浏览器使用--不然不支持）
4. HTML页面中引入打包后的地图index.js以及vue.js，即可使用
5. 参考文件地址：
	http://weixin.jrcad.com/map/location.html
	http://weixin.jrcad.com/map/station.html
	http://weixin.jrcad.com/map/path.html
```