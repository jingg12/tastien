##  塔斯汀小程序模仿
- 本项目归塔斯汀所有，只做学习所用，请尊重原厂版权
- 可以去监听访问数据  fiddler 抓包工具抓取图片
- 界面模仿采用markman做标记
   1. 我没有设计稿， 如何一比一还原小程序？
   2. 拍屏得到小程序截图
   3. 使用在线大小【转换工具】（https://www.gaitubao.com/），
       以后在写wxss的时候，直接量像素就可以写进去，因为小程序以750rpx作为
        设计稿标准大小帮我们自动适配，很好用。
   4. 使用[markman](http://www.getmarkman.com/) 先标注，再写样式
      以后上班就不用了，有设计师给你标好，现在还是直接来lol吧

-   项目配置在根目录app.json
   - 隐藏并定制navigationBar
     "navigationStyle": "custom"
   - 启动定位功能

-   使用了BEM 国际css命名规范
   tst_banners  广告位
   tst_banners__image Element

      