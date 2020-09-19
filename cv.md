# OpenCV培训

## 前置基础

了解python基础语法，会调用python的库以及包管理

本培训教程使用python3和opencv4，其他版本的语法类似

开发环境推荐使用PyCharm或者Jupyter Notebook

## 安装配置

推荐使用国内源进行安装

>清华
>
>https://pypi.tuna.tsinghua.edu.cn/simple
>
>阿里
>
>http://mirrors.aliyun.com/pypi/simple/ 
>
>豆瓣
>
>http://pypi.douban.com/ 
>
>华中理工大学
>
>http://pypi.hustunique.com/ 
>
>山东理工大学
>
>http://pypi.sdutlinux.org/ 
>
>中国科学技术大学
>
>http://pypi.mirrors.ustc.edu.cn/ 

安装numpy库

```shell
pip install numpy -i https://pypi.tuna.tsinghua.edu.cn/simple
```

安装opencv库

```shell
pip install opencv-python -i https://pypi.tuna.tsinghua.edu.cn/simple
```

如果操作系统是Linux，python3环境要使用pip3进行安装

下载完成后输入以下Python代码检查

```python
import cv2
print(cv2.__version__)
```

能打印出版本号则说明安装正常

## 基本操作

1. 读写图片、视频，调用外部摄像头
2. 像素和数组分析
3. 颜色空间转换、模糊、边缘检测、膨胀、腐蚀
4. 改变大小
5. 增加图形和文字
6. 视角变换
7. 图像拼接

## 库

face_recognition

## 云

了解计算机网络基础，教程以百度云作为演示