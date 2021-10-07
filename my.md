homebrew：

https://zhuanlan.zhihu.com/p/111014448

nvm的安装教程：

https://www.mintimate.cn/2021/07/26/nvmNode/#%E5%89%8D%E8%A8%80



reactnative，以下方式可能报错

`npx react-native init AwesomeProject`

安装一直报cocoapods error



可以尝试使用：

`npm install -g create-react-native-app`

`create-react-native-app xxx`



reactnative mac端的开发可以参考以下网站：

https://www.bilibili.com/video/BV1ot4y197Wj?p=1

函数式编程：

https://www.bilibili.com/video/BV19q4y1X7XV?p=11



快捷生成页面代码 rnc，rnf



调试技巧：command + D

https://www.hangge.com/blog/cache/detail_1480.html



rn  样式继承只发生在Text组件上

样式名采用小驼峰命名

所有尺寸都是没有单位：

width: 100

有些特殊的样式名：

maginHorizontal（水平外边距）

marginVertival（垂直外边距）





npm修改淘宝资源：

设置

```
npm config set registry https://registry.npm.taobao.org
```

查看

```
npm config get registry
```

