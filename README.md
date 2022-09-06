## 一.下载

### 1:打开浏览器，输入网址 http://www.mongodb.com/try/download/community 

![1](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/1.jpg)

### 2:找到community栏目，并根据提示选择适合自己的系统下载数据库。

##### (1)苹果Macos M1及以上ARM架构处理器的用户选择MacOS ARM 64；intel x86架构处理器选择正常MacOS下载

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/2.jpg)

### 3.选择好系统后，点击下载按钮开始下载

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/3.jpg)

## 二.安装

### 1.打开刚刚的安装包

##### (1)第一步，直接点击next

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/4.jpg)

##### (2)第二步，点击I accept the terms in the License Agreement,然后点击next

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/5.jpg)

##### (3)第三步，点击Custom

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/6.jpg)

##### (4)第四步，如果要自定义安装目录，可以点击Browse，选好后点击Next。如不需要则直接点击next

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/7.jpg)

##### (5)第五步，点击next

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/8.jpg)

##### (6)第六步，不要勾选Install MongoDB Compass 然后点击next

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/9.jpg)

##### (7)第七步，点击Install

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/10.jpg)

##### (8)第八步，等待安装完成

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/11.jpg)

##### (9)第九步，点击finish

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/12.jpg)

### 2.启动mongodb server

##### (1)找到刚刚安装的mongodb文件夹，默认位置在C:\Program Files\MongoDB。data文件夹是数据库存放数据的地方，bin是数据库服务文件夹，也是下面要操作的文件夹

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/13.jpg)

##### (2)打开bin文件夹，双击mongod，出现黑色窗口一闪而过

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/14.jpg)

##### (3)打开浏览器，在url栏输入localhost:27017,若出现图中的字符串(It looks like you are trying to access MongoDB over HTTP on the native driver port.)说明mongodb数据库已经启动成功

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/15.jpg)

### 3.关机后mongodb server重启方法: 找到之前点击的mongod文件，右键，创建快捷方式，然后把快捷方式拖到桌面上，下次要用时，双击其动即可![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/16.jpg)

## 三.管理数据库

### 1.安装

##### (1)打开网站https://www.mongodb.com/products/compass点击Download Now

##### ![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/17.jpg)

##### (2)下载完成点击安装包，将自动安装

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/18.jpg)

### 2.连接mongodb数据库

##### (1)点击绿色Connect

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/19.jpg)

##### (2)连接成功

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/20.jpg)

## 四.获取leukemia api

### 1.打开网站，点击by subtypes的选项，并点击自己的亚型

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/21.jpg)

### 2.进入界面后点击f12，打开开发者工具，并点击网络选项卡

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/22.jpg)

### 3.随便找一个栏目，点击下一页

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/23.jpg)

### 4.网络监听到了我们需要的api

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/24.jpg)

### 5.可以点击新标签打开

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/25.jpg)

### 6.先看请求参数有哪些

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/26.jpg)

### 7.新标签打开

![](https://raw.githubusercontent.com/wobisheng/easy_mongodb_install/main/27.jpg)

### 8.可以看出api请求参数有page和size。page为当前页数，size为每页的记录数
