# NeZha_Developer_Kit_for_Windows_or_Linux
哪吒开发套件介绍以及Windows、Linux系统安装、开发板资源分享
# 写在前面的话
大家好，欢迎来到我的博客！今天我非常兴奋地和大家分享，我刚刚收到英特尔上海总部（Intel紫竹）寄来的哪吒（Nezha）开发套件。这款开发板以其强大的性能和丰富的接口，吸引了众多开发者的关注。本文将详细介绍哪吒开发套件的特点和规格，并为大家演示如何在Windows和Linux系统上安装和使用这款开发板。希望通过这篇文章，能够帮助到那些对哪吒开发套件和Intel N97感兴趣的朋友们。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b2b6cb3211814214a28089702a094992.jpeg#pic_center)

# 一、哪吒开发套件介绍
## 1.1 开发板介绍
**1.开发板简介**
哪吒（Nezha）开发套件以信用卡大小（85 x 56mm）的开发板-哪吒（Nezha）为核心，哪吒采用Intel® N97处理器（Alder Lake-N），最大睿频3.6GHz，Intel® UHD Graphics内核GPU，可实现高分辨率显示；板载LPDDR5内存、eMMC存储及TPM 2.0，配备GPIO接口，支持Windows和Linux操作系统。
更详细的介绍可以查看[研扬科技](https://www.aaeon.com/cn/p/up-nezha)或者[NeZha Developer Kit (intel.cn)](https://www.intel.cn/content/www/cn/zh/developer/topic-technology/edge-5g/hardware/nezha-dev-kit.html)官网

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0114d2e61fa348238ff2bcb8122ef161.png)

**2.开发板特点**
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a9acf73255b749d5861153c47563dbf2.png)
**3.开发板规格**
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0929343fbfa8408a8a1c8fa63db5d973.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f0ac3f8d42cd4371bb9680ed31cb70a8.png)
**3.开发板尺寸**
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/72e4857df7cd4eb4954f695aa5e403bf.png)

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/16273666840c408286ef8551e3b2d724.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/29cc7dcfa9de45bfb7a6dd2c6bfbfb06.png)
## 1.2 实物开箱
[沉浸式开箱](https://live.csdn.net/v/427778)（见CSDN）

# 二、Windows镜像安装
## 2.1 准备系统盘
在电脑上插上一个u盘32G及以上（做系统盘会格式化u盘）。打开rufus工具
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/092a115c7e934feea83ea464b12659fe.png)
确认一下，设备一栏选项里选择的是你插入的U盘。
然后点击选择按钮，选择你要制作的系统ios文件。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/5bdc103efd204ff991585462c946363a.png)
然后点击开始。然后一路点击确认即可。等状态一栏的进度条读完系统盘即制作完成。
## 2.2 设置U盘开机启动
方法一：
目标主机插上启动盘，然后开机。
开机按F7，然后选择你的U盘为引导项。然后回车。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/562142ec83b3463f8c539fc34ffb662b.png)
方法二：
也可以开机按Delete，进入BIOS。
在BOOT选项中设置你的U盘为boot option #1
然后按F4 保存。
## 2.3 安装Windows系统
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/dc31b1207d4d45ab8b300f619bba1135.png)
这里选择下一步，然后就可进入安装程序。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0c81f7bba6ac40fc95a4f41ce39615e8.png)
选择自定义安装
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a0ddd049674b47688d94baa7db0a8c35.png)
把多余的占用空间删掉，新建分区分盘到进入桌面磁盘分区，这里直接点击下一步
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/036856054afe4728a8ac3f61b0923ee7.png)
系统盘之后想要继续正常使用则必须要格式化，注意格式化时要选择正确的文件系统（NTFS)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/c2a7092b236e4ebe992c4e261f43c8a8.png)


# 三、Linux镜像安装
## 3.1 准备系统盘
在电脑上插上一个u盘（注：里面资料自己保存一下，做系统盘回格式化u盘）。打开rufus-3.1。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0b6c880ca5bb4dc188ba415da37c5ce6.png)
确认一下，设备一栏选项里选择的是你插入的U盘。
然后点击选择按钮，选择你要制作的系统ios文件。
然后点击开始。然后一路点击确认即可。等状态一栏的进度条读完系统盘即制作完成。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/47f5c10431f6451f9226b13df9209e91.png)

## 3.2 设置U盘开机启动
方法一：
目标主机插上启动盘，然后开机。
开机按F7，然后选择你的U盘为引导项。然后回车。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/fe56aba8e91c462ea94e94f97e088f26.png)
方法二：
也可以开机按Delete，进入BIOS。
在BOOT选项中设置你的U盘为boot option #1
然后按F4 保存。

## 3.3 安装Ubuntu系统
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8e90b3e1ae3644689da86b262bd5c3ca.png)
这里选择install Ubuntu，然后就可进入安装程序。

中文英文分别如下设置
1.安装ubuntu
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8162cb7cfebf45e99b1b1045c1d04283.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/6f92bff20f234023bace6fe74b57ea2a.png)
2.设置语言
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a0196a63e2df46fab8db8c0f653a4535.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/fe2f0018ca3c4aa4b3f7b7e2110431e7.png)
3.	选择正常安装
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/151fa565be734392b78787e36931807d.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/c70a628d328947f39018591eb1759b87.png)4.选择完整安装和清除整个磁盘安装。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a4548798fc0d4049aade112e747dc714.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b267f3e46481409fa61064d4f15e02a3.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/01db09facc2e4e7d8ff5896731ff052a.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/9464cc89a60347a8adc503f575df9c76.png)

5.选择上海
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a7ff20fbe1a64e7db6ddcdba8dcc42cf.png)
6.	用户名密码
7.	换源（阿里源or清华源等）打开
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/ea2ba89a5eff4e8297b17c5d54a03381.png)停止更新下载，点击设置settings
选择choose server 再点击continue即可
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/6227a89854734f53aff9aff144b1b106.png)

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/6e978bf58a1941949efdbb31802b8e5f.png)

#  总结
##  资源分享
1.系统镜像资源
[Linux、Windows系统镜像资源](https://pan.baidu.com/s/1kP3ypA_fqodmdB1zmqSvtA?pwd=9o0n)（镜像未预装Openvino）

2.产品规格
[NEZHA-2D3D-Drawings](https://pan.baidu.com/s/1y7Z0ovjofdUKinNXxl443g?pwd=amww)（dwg文件用CAD打开）

3.产品数据手册
[Nezha datasheet and Manual 2nd Ed-20231213](https://pan.baidu.com/s/1hREVGhrTdelewcKQdTyMwQ?pwd=4qmv)（中英文pdf）

其他资源也在同一网盘链接中（BIOS、系统安装教程等）

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/4929e3d299514cd79a4af6cf1c2de2b9.png)


通过这篇文章，我们详细介绍了哪吒开发套件的硬件规格和特点，并且演示了如何在Windows和Linux系统上安装和使用这款开发板，以及一些相关资源的分享。希望这些内容能够帮助到那些对哪吒开发套件感兴趣的朋友们。如果你觉得这篇文章对你有帮助，别忘了点赞加关注，后续我还会分享更多关于哪吒开发套件的使用技巧和项目案例。谢谢大家的支持！
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/4279f880eda7435992c9818321822585.jpeg#pic_center)

