# pydata-notebook 利用python进行数据分析(练习代码)

>>为无为，事无事，味无味。大小多少。报怨以德。
>>图难于其易，为大于其细；
>>天下难事，必作于易；天下大事，必作于细。
>>--老子

## 准备工作

### 安装EPD_free

Enthought Canopy (Enthought Python Distribution):来自[Enthought](https://www.enthought.com/products/epd/)的面向科学计算的Python计算包。包括免费EPDFree(免费的基本版，带有NumPy、SciPy、matplotlib、Chac以及IPython)和EPD Full（完整版，含有100多个针对各个领域的科学计算包）。EPD Full对高效免费，非高校用户需要缴纳年费。

目前版本EPD使用的是Python 2.7。安装完毕后，你将可以用到下面的这些包:
* Python科学计算基础库：NumPy、SciPy、matplotlib以及IPython。这些都包含在EPDfree中。
* IPython NoteBook依赖项：tornado和pyzmq。这些也包含在EPDfree中了。
* pandas(0.8.2版或更高版本)

EPDfree安装如下：

1. 下载epd_free-7.3-2-win-x86：[点击下载](https://pan.baidu.com/s/1hrLDVpi)
1. 双击安装epd_free-7.3-2-win-x86，安装前需要卸载机器上已安装的Python。文件默认安装在 c:\Python27
1. 安装完成后，打开DOS，运行：python，可以打开命令行Python，并显示Python 2.7.3 |EPD_free 7.3-2 (32-bit)| (default, Apr 12 2012, 14:30:37) [MSC v.1500 32 bit (Intel)] on win32类似信息

### 安装pandas

pandas是Python数据分析包，详细介绍请百度一下。

1. 下载最新版本二进制安装包：[点击下载](https://pan.baidu.com/s/1c2geQPy)
1. 双击安装pandas，安装完毕后就可以在Python中使用了

### 《利用Python进行数据分析》电子书

[点击下载](https://pan.baidu.com/s/1jI6rafG)

## 引言

* 来自bit.ly的1.usa.gov数据：usa_gov.ipynb
* MoviesLens 1M数据集：MovieLens1M.ipynb
* 1880-2010年间全美婴儿姓名：names.ipynb
* 关于pandas的一些练习：pandas_test.ipynb

## IPython:一种交互式计算和开发环境

介绍两种打开IPython方法，使用下面方法需要EPDfree安装在c:\Python27，否则需要修改快捷方式的程序路径：

* 在浏览器打开：执行Notebook PyLab.lnk
* 在命令行打开：执行PyLab.lnk

代码：ch03.ipynb

## NumPy基础：数组和矢量计算

代码：ch04.ipynb

## pandas入门

代码：ch05.ipynb