# react-native-0.54-start

## 参考资料地址https://reactnative.cn/docs/0.51/getting-started.html#content

## 这个项目将从0开始搭建RN项目 使用的主要脚手架将为redux + webpack

## 根据RN官网  react-native init AwesomeProject  创建新项目 先试着运行一下 react-naive run-andorid

#  然后你就发现，MMP，这是个啥子哦，一堆儿报错，MMP

###  就开始解决问题了， 首先你需要andorid studio 然后按照上面网址上的指示一步步勾选开发依赖；

###  然后你需要下载adb 工具   这个网上很多  推荐 http://vdisk.weibo.com/s/u_bWx/1364188783， 
     下载完成后解压缩，将解压到的文件放入你的命令行的根目录

      像我就是 http://ss1.sinaimg.cn/large/a2b97d67gy1fpj33rhyaqj20c403x3yg.jpg

###  然后编辑器打开项目  在andorid -- app -- src -- main 文件夹下新建一个assets的文件夹 （这里一万句草泥马奔腾而过）；

###  项目根目录执行 
      react-native bundle --platform android --dev false --entry-file index.js 
      --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res/
      
###  然后打开andorid studio  file  open project  导入项目中的安卓目录 （记住一定是安卓目录）；

###  然后要新建一个虚拟机， 
http://ss1.sinaimg.cn/large/a2b97d67gy1fpj33ecwe4j20na05pgm4.jpg  这个虚拟机是非常必要的  否则你就等着一大堆你看不懂的报错吧；

###  然后就可以运行了  就出来官网上的项目了  
http://ss1.sinaimg.cn/large/a2b97d67gy1fpj34u0xwnj20au0jdwg3.jpg
