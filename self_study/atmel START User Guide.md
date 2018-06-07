# 配置界面（configuration screen）
## 时钟配置（clock configuration）
时钟系统由振荡器和不同类型的信号源组成。 通过使用时钟配置器，您可以配置每个源和振荡器，并查看计算出的输出频率。

该视图还允许您为所选组件选择正确的时钟源。
```
a.振荡器部分显示可用于选定器件的振荡器，大多数时钟源将具有固定频率，而其他时钟源可以直接指定或通过选择相关输入信号指定。
  打开设置对话框来配置振荡器参数。
b.源部分允许您通过选择输入信号并更改倍频器和/或分频器（如果可用）来配置时钟频率
c.组件部分将列出添加到配置中的模块实例， 该部分允许您选择输入信号并查看产生的频率。
d.禁用时钟的连接使用虚线显示
```
![image](https://github.com/yuchengstudio/START/blob/master/self_study/picture/clock%20configuration_001.jpg)
并非所有器件都具有用于启用/禁用源的复选框。 这些必须通过访问设置对话框进行设置。 不带复选框的振荡器始终处于启用状态。

## 如何使用时钟配置器
```
     提供了一个默认配置。 大多数组件使用通用时钟发生器0。
     通过在框之间拖放来设置连接或打开设置对话框来选择所需的输入
     通过单击每个框上的齿轮图标访问设置对话框。 时钟必须先启用。
     通过单击框显示各个时钟路径
     通过单击禁用的图标启用禁用的时钟和时钟路径。 图标上的工具提示提供了更多信息。
     重置所有时钟设置
 ```
 
 ## 使能和关闭
 ```
     在创建项目时，许多振荡器最初将被禁用。 在左上角有一个空的复选框。 使用禁用的振荡器的信号源和组件将产生警告信号。 
 要启用或禁用源，请使用复选框（如果可用）或打开设置菜单并检查相应的参数。
 ```

 ## 源（source）作为振荡器的输入
 ```
     一些振荡器可能有一个源发生器作为输入。 如果频率超出定义的限制，这些将显示警告。 将鼠标悬停在文字上以显示显示来源和
 违规频率的工具提示。 如果振荡器输入到输入到相同振荡器的信号源，则会显示警告，因为这样产生循环依赖。
 ```
![image](https://github.com/yuchengstudio/START/blob/master/self_study/picture/clock%20configuration_002.jpg)

## 一个组件有多个时钟
```
    某些组件具有多个时钟。 如果是这种情况，用于拖放的时钟字体较暗。 要切换，请点击应该在拖放中使用的时钟的名称。
```
![image](https://github.com/yuchengstudio/START/blob/master/self_study/picture/clock%20configuration_003.jpg)

## 设置组件的时钟源
```
时钟源可以从组件设置对话框中设置：
```
![image](https://github.com/yuchengstudio/START/blob/master/self_study/picture/clock%20configuration_004.jpg)

```
时钟源也可以从组件编辑器中选择：
```
![image](https://github.com/yuchengstudio/START/blob/master/self_study/picture/clock%20configuration_005.jpg)


## 时钟参数设置
```
    振荡器和信号源设置对话框将显示由所选项目定义的设置。 提供了一个工具提示来帮助选择。 选中上角的“启用” - 
框以启用编辑选项。
```
![image](https://github.com/yuchengstudio/START/blob/master/self_study/picture/clock%20configuration_006.jpg)





  
