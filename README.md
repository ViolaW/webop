# webop
 ### Writing for Web Accessibility自制WAI指导原则中文版
 

![截图0](https://images.gitee.com/uploads/images/2020/0323/103949_63326cd4_2229195.png "translate0.png")


|设计与开发|                    
|---|
|写作技巧
|设计技巧
|发展建议
|视听媒体
|教程 


## 为网页无障碍而写作
[关于如何开始的建议](https://www.w3.org/WAI/tips/)
|**总结**|
| :-----|
| 本页介绍了一些基本注意事项，以帮助您开始编写对残疾人更容易访问的web内容。这些提示是帮助您满足web内容可访问性指南（WCAG）要求的良好实践。按照相关WCAG要求的链接，“理解”文档中的详细知识背景，教程的指导，用户故事，等等。|
|**页面内容**
|  [提供信息丰富、独特的页面标题](https://www.w3.org/WAI/tips/writing/#provide-informative-unique-page-titles)
|  [使用标题来传达意思和结构](https://www.w3.org/WAI/tips/writing/#use-headings-to-convey-meaning-and-structure)
|  [使链接文本有意义](https://www.w3.org/WAI/tips/writing/#make-link-text-meaningful)
|  [为图像编写有意义的文本替代](https://www.w3.org/WAI/tips/writing/#write-meaningful-text-alternatives-for-images)
|  [为多媒体创建文本和标题](https://www.w3.org/WAI/tips/writing/#create-transcripts-and-captions-for-multimedia)
|  [提供明确的指示](https://www.w3.org/WAI/tips/writing/#provide-clear-instructions)
|  [保持内容清晰简洁](https://www.w3.org/WAI/tips/writing/#keep-content-clear-and-concise) 

----------------

![翻译截图1](https://images.gitee.com/uploads/images/2020/0323/111434_e7394cfe_2229195.png "translate1.png")

## 提供信息丰富、独特的页面标题

对于每个web页面，提供一个简短的标题来描述页面内容并将其与其他页面区分开来。页面标题通常与页面的主标题相同。把唯一和最相关的信息放在首位;例如，将页面的名称放在组织的名称之前。对于属于多步骤流程的页面，请在页面标题中包含当前步骤。
|例如:页面标题|
| -----------|
|**首页标题**|
|太空玩具有限公司|
|**页面名称后面跟着组织名称**|
|最新消息•太空泰迪公司|
|**页名包括流程中的步骤**|
|买你的熊(3步1)•太空泰迪公司|

|更多的信息|
| ----------|
|**WACG**
[页面标题为2.4.2](https://www.w3.org/WAI/WCAG21/quickref/#page-titled) [(理解2.4.2)](https://www.w3.org/WAI/WCAG21/Understanding/page-titled)|

-----------------

![翻译截图2](https://images.gitee.com/uploads/images/2020/0323/113118_cd26005d_2229195.jpeg "translate2.jpg")

## 使用标题来传达意思和结构
使用简短的标题来组织相关的段落，并清晰地描述章节。好的标题提供内容的大纲。

|**例如:使用标题来组织内容**  |  |
| ---------------|--------------|
| **（错）缺少标题** | **（对）使用标题和副标题** |
|![截图3.1](https://images.gitee.com/uploads/images/2020/0323/113853_4c16189a_2229195.png "3.1.png")| ![截图3.2](https://images.gitee.com/uploads/images/2020/0323/113911_798a1951_2229195.png "3.2.png")|
| - 内联视图示例| - 内联视图示例|
|**标题和副标题**|**标题和副标题**|
|HTML元素提供关于文档结构层次结构的信息。正确使用元素将有助于向辅助技术传达额外的含义。在许多情况下，这样做也会使您的文档更容易编辑。|HTML元素提供关于文档结构层次结构的信息。正确使用元素将有助于向辅助技术传达额外的含义。在许多情况下，这样做也会使您的文档更容易编辑。|
|对于超过三到四段的文档，标题和副标题对于可用性和可访问性非常重要。它们帮助读者确定文档的总体轮廓，并导航到感兴趣的特定信息。|**例如:标题的目的**|
|标题分为1到6级。最高级别是“第1级”，通常对应于页面或主要文档部分的标题。子标头通过增加标头级别进行处理。|对于超过三到四段的文档，标题和副标题对于可用性和可访问性非常重要。它们帮助读者确定文档的总体轮廓，并导航到感兴趣的特定信息。|
|视觉阅读器通过扫描页面以寻找更大尺寸或不同样式的文本来识别标题。辅助技术用户无法看到这些视觉变化，因此改变样式并不是足够的提示。|标题的水平|
|相反，标题必须在语义上“标记”，以便辅助技术能够识别标题。这可以作为导航帮助提供给用户。|标题分为1到6级。最高级别是“第1级”，通常对应于页面或主要文档部分的标题。子标头通过增加标头级别进行处理。|
|这使得添加标题成为屏幕阅读器用户最重要的工具之一，这样他们就可以了解页面上的内容。注意，标记通常会在视觉上触发格式更改，可以在许多文档中进行调整。|**意义与格式化**|
|改编自[宾夕法尼亚州立大学的标题和副标题](https://accessibility.psu.edu/headings/)  |视觉阅读器通过扫描页面以寻找更大尺寸或不同样式的文本来识别标题。辅助技术用户无法看到这些视觉变化，因此改变样式并不是足够的提示。相反，标题必须在语义上“标记”，以便辅助技术能够识别标题。这可以作为导航帮助提供给用户。这使得添加标题成为屏幕阅读器用户最重要的工具之一，这样他们就可以了解页面上的内容。注意，标记通常会在视觉上触发格式更改，可以在许多文档中进行调整。|
|  |改编自[宾夕法尼亚州立大学的标题和副标题](https://accessibility.psu.edu/headings/)|

|更多的信息|
|-------------|
|**WCAG**|
|[标题和标签2.4.6](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)[(理解2.4.6)](https://www.w3.org/WAI/WCAG21/Understanding/headings-and-labels)|
|[章节标题2.4.10](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)[(理解2.4.10)](https://www.w3.org/WAI/WCAG21/Understanding/section-headings)|
|[信息与关系1.3.1](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)[(理解1.3.1)](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships)|
|**用户故事**|
|[屏幕阅读器用户如何使用标题导航](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)|

---------------------------

![翻译截图3](https://images.gitee.com/uploads/images/2020/0323/121126_5d5329dc_2229195.jpeg "translate3.jpg")

## 使链接文本有意义
编写链接文本，以便它描述链接目标的内容。避免使用模棱两可的链接文字，例如“点击这里”或“阅读更多”。说明链接目标的相关信息，如文档类型和大小，例如“提案文档(RTF, 20MB)”。

|**例如:使用链接文本来描述目标页面**|   |
|----|-----------|
|(错）任何信息|（对）有意义的信息|
|有关设备独立性的更多信息，[请单击此处。](about:blank#blocked)|阅读更多[关于设备独立性的内容。](about:blank#blocked)|


|更多的信息|
|-----|
|WACG|
|[链接目的(上下文)2.4.4](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-in-context)[(理解2.4.4)](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-in-context)|
|[链接目的(仅链接)2.4.9](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-link-only)[(理解2.4.9)](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-link-only)|


-------------------

![翻译截图4](https://images.gitee.com/uploads/images/2020/0323/122405_f7e9c5a4_2229195.jpeg "translate4.jpg")

## 为图像编写有意义的文本替代
对于每个图像，编写替代文本，提供图像的信息或功能。对于纯装饰性的图像，没有必要编写替代文本。

|例如:使用替代文本来传达重要信息|   |
|-----------------------|--------------|
|（错）不提供信息的|（对）信息丰富的|
|![4.1](https://images.gitee.com/uploads/images/2020/0323/122937_027ee3ff_2229195.png "4.1.png")充电:使用提供的电缆和电源适配器将手机连接到电源插座。**图片替代文字**:“充电手机”|![4.2](https://images.gitee.com/uploads/images/2020/0323/123042_0ba5713a_2229195.png "4.2.png")充电:使用提供的电缆和电源适配器将手机连接到电源插座。**替代文本图像**:“将电缆插入手机底部边缘。”|
|替代文本通常是不可见的;它包含在这个示例中，这样您就可以看到它是什么。|


|更多的信息|
|------------|
|**WACG**|
|[非文本内容1.1.1](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)[(理解1.1.1)](https://www.w3.org/WAI/WCAG21/Understanding/non-text-content)|
|**教程**|
|[图片](https://www.w3.org/WAI/tutorials/images/)|
|**用户故事**|
|[描述文本替代方案对盲用户的价值](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)|

--------------------------

## 为多媒体制作文本和标题 [原文地址](https://www.w3.org/WAI/tips/writing/#create-transcripts-and-captions-for-multimedia)
对于纯音频内容，比如播客，提供一个文本。对于音频和视频内容，如培训视频，也提供标题。在抄本和标题中包括对理解内容很重要的口语信息和声音，例如，“门吱吱作响”。对于视频抄本，还包括对重要视频内容的描述，例如'Athan leaves the room'。
更多信息
* WCAG 网页内容可访问性指南
*标题（预先记录在）1.2.2（理解1.2.2）；
音频描述或媒体替代（预录制）1.2.3（了解1.2.3）*
* 用户故事
描述字幕如何帮助聋哑学生
![](https://github.com/ViolaW/webop/blob/master/images/%E8%8B%B1%E6%96%87%E5%8E%9F%E7%89%88%E6%88%AA%E5%9B%BE1.png)

## 提供明确指示[原文地址](https://www.w3.org/WAI/tips/writing/#provide-clear-instructions)
确保说明、指导和错误信息清晰易懂，避免使用不必要的技术语言。描述输入要求，如日期格式。
示例：表达说明用户应提供的信息
*密码应至少包含六个字符，至少包含一个数字（0-9）。
密码

示例：出错，指出出现的问题是什么，并尽可能指示如何解决问题
* 1.用户名“superbear”已在使用中。
2.密码必须至少包含一个数字。

更多信息
* 网页内容可访问性指南
标签或说明3.3.2（理解3.3.2）
用户故事
描述帮助有学习困难的人的简单说明
![image](https://github.com/ViolaW/webop/blob/master/images/%E8%8B%B1%E6%96%87%E5%8E%9F%E7%89%88%E6%88%AA%E5%9B%BE2.png)

## 让内容简洁明了[原文地址](https://www.w3.org/WAI/tips/writing/#keep-content-clear-and-concise)
根据上下文使用简单的语言和格式。
* 写出简短、清晰的句子和段落。
* 避免使用不必要的复杂单词和短语。考虑为读者可能不知道的术语提供词汇表。
* 首次使用时展开首字母缩略词。例如，Web内容可访问性指南（WCAG）。
* 考虑为读者可能不知道的术语提供词汇表。
* 根据需要使用列表格式。
* 考虑使用图像、插图、视频、音频和符号来帮助3明含义。
![](https://github.com/ViolaW/webop/blob/master/images/%E8%8B%B1%E6%96%87%E5%8E%9F%E7%89%88%E6%88%AA%E5%9B%BE3.png)

示例：使内容可读和可理解
* 不必要的复杂
CPP：在发生车辆碰撞的情况下，公司指定的代表将寻求确定属于所有相关方的财产损失的程度和原因。一旦我们的代表获得信息，使我们能够了解因果关系，我们可以或不可能分配适当的金钱补偿。由此产生的决定可能会导致以下选项之一：索赔未经批准，并被指定为拒绝状态；索赔状态模棱两可，需要更多信息才能进行进一步处理；索赔被部分批准，并分配和签发了减少的付款，或索赔得到完全批准，并分配和签发总索赔付款。
* 更容易理解
索赔处理程序（CPP）：如果您发生车祸，我们的代理人将进行调查。调查结果将决定任何索赔付款。这可能导致：
批准的索赔-全额付款
部分批准的索赔-减少付款
未定索赔-需要更多信息
拒绝索赔-不付款
![](https://github.com/ViolaW/webop/blob/master/images/%E8%8B%B1%E6%96%87%E5%8E%9F%E7%89%88%E6%88%AA%E5%9B%BE4.png)

更多信息
* WCAG
*阅读水平3.1.5（理解3.1.5）
异常词3.1.3（理解3.1.3）
缩略语3.1.4（理解3.1.4）*

* 用户故事
阅读障碍的用户受益于易于阅读的文本
![](https://github.com/ViolaW/webop/blob/master/images/%E8%8B%B1%E6%96%87%E5%8E%9F%E7%89%88%E6%88%AA%E5%9B%BE5.png)


#### 了解有关辅助功能的更多信息
这些技巧是您需要考虑的一些事情，用以实现web可访问性。以下资源有助于您了解为什么可访问性很重要，以及使残疾人更容易访问web的指导原则。
* 辅助功能介绍-介绍辅助功能并提供指向许多有用资源的链接
* 可访问性原则-WCAG要求简介
* 残疾人如何使用网络-现实生活的例子显示了无障碍对残疾人的重要性
* 如何满足WCAG（快速参考）-所有WCAG要求和技术的可定制参考
![](https://github.com/ViolaW/webop/blob/master/images/%E8%8B%B1%E6%96%87%E5%8E%9F%E7%89%88%E6%88%AA%E5%9B%BE6.png)




