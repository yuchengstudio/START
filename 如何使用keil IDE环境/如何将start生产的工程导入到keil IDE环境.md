# 1.本文参考文献
如果觉得作者有翻译不恰当的地方，请对比如下链接的英文说明：
<br/>http://atmel-studio-doc.s3-website-us-east-1.amazonaws.com/webhelp/GUID-4E095027-601A-4343-844F-2034603B4C9C-en-US-3/index.html?GUID-AB6C30C2-90EB-4F75-843D-ED9EC099F76C

# 2.第一步：从START环境中导出支持keil的工程：
On the Atmel START website, create a new project (Example or Board).
Click on the Export Software Component button. Make sure the "µVision from Keil" check box is checked.
## 2.1 在START的网站，产生一个新的项目
## 2.2 点击"EXPORT PROJECT"控件，开始导出相应工程
![image](https://github.com/yuchengstudio/START/blob/master/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8keil%20IDE%E7%8E%AF%E5%A2%83/reference/statr_keil_002.png)
## 2.3 保存工程，工程默认为 xxx.atzip的文件（注意是atzip文件格式）
## 2.4 修改xxx.atzip文件的格式为xxx.zip
## 2.5 将xxx.zip文件用解压工具解压到你自选的工作文件夹下面


# 3.第二步：安装keil环境下的器件软件包（这步非常重要，否则无法正常打开工程）
https://www.keil.com/boards2/atmel/samc21n_xpro/#/eula-container
![image](https://github.com/yuchengstudio/START/blob/master/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8keil%20IDE%E7%8E%AF%E5%A2%83/reference/statr_keil_003.png)

# 4.第三部：在Keil µVision 环境下打开工程
## 4.1 启动Keil µVision.
## 4.2 选择File > Open, 在文件过滤选项框中选择所有文件“All Files”, 在第一步解压的文件夹下选择“AtmelStart.gpdsc”文件，点击打开就能正常导入工程。
![image](https://github.com/yuchengstudio/START/blob/master/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8keil%20IDE%E7%8E%AF%E5%A2%83/reference/statr_keil_004.png)

## 4.x 编译之前请在项目配置的Output的界面取消“Browse Information”勾选，否则编译会非常耗时间。
![image](https://github.com/yuchengstudio/START/blob/master/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8keil%20IDE%E7%8E%AF%E5%A2%83/reference/statr_keil_005.png)





