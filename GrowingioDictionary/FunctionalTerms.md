# GrowingIO 功能词汇

##圈选

###**元素 **  
**定义**：页面的组成部分，如图片，文字和链接等。

---
###**圈选/定义**  
**定义**："圈选：通过点击选中页面中的元素，查看该元素的点击浏览数据。圈选的同时可以将这个元素的数据定义成指标，方便在日后的分析中使用。"

---
###**高亮定义 **  
**定义**：将已经定义过的元素，用高亮的形式标识出来，以避免重复定义。

---

###**定义整页 ** 
**定义**：定义当前所在页面，方便分析该页面整体的数据。

---

###**匹配条件 ** 
**定义**：圈选过程中，对选中元素进行各种条件的匹配。匹配内容包括下面会提到的的位置，文本等。

---
###**位置（列表） ** 
**定义**：即元素在列表中出现的位置，显示为数字，如1，2，3...。

---
###**文本 ** 
**定义**：即元素里的文字内容。  

**举例**：以圈中“立即注册”为例，如果打开文本匹配，则将分析页面中所有“立即注册”的元素；反之，则只分析圈选元素的数据。

---
###**设为维度 ** 

**定义**：可以将此标签中所出现的“内容”， 作为维度，对其它指标数据做聚合。 

---
###**容器 **
**定义**：APP专用术语。指APP页面上放置图片/文字/按钮 等元素的地方。

---

###**自动模式 ** 
**定义**：通过GrowingIO 内置算法让圈选数据更精确到一种模式。  

**备注**：页面元素的xpath通常会因为很多情况而发生变化，例如：显示效果，使用用户的个人设置，渲染顺序，浏览器差异化等等原因。GrowingIO 在统计一个页面元素的浏览/点击数量时，虽然所有数据都会收集上来，但是不清楚同一个元素包含了哪些差异化的xpath数据。所以之前圈选逻辑的问题在于，用户在圈选时，永远是以一个xpath来进行圈选，这就导致元素的浏览/点击数量偏小。自动圈选的主要功能就是，找到每一个元素所有不同的xpath，并将这些xpath出现的浏览/点击数量进行合并，从而保证元素数据的准确性。

---


##管理

###**项目/产品/组织 **   
**定义**：一个组织下有多个项目，项目下可以有多个产品。成员可以从属与多个组织，以及多个项目。产品没有所属成员一说。

---
###**权限 **    
**定义**：目前权限分为管理者，采集者，普通用户三个级别，每个级别可以对低级别用户的权限做权限调整（不高于自己）和禁止/恢复 操作。  



##功能  

###**用户分群** 
**功能说明**：在精细化分析中，对满足一定条件的用户进行分组分析。详细案例：[3.5.用户分群](https://help.growingio.com/usersegmentation.html)  

---
###**用户细查**  

**功能说明**：用户细查可以展示单个用户的详情，以及单个用户在您的网站／应用内的行为流。案例详情：
[用户细查](https://help.growingio.com/Features/insights.html)  

---
###**留存**    
**功能说明**：留存，顾名思义，就是用户在你的网站/app中留下来、持续使用的意思。留存主要用来衡量应用对用户的吸引程度、用户对应用的粘性、渠道用户质量及广告投放效果等。常用的留存指标有次日留存、周留存和月留存等。 案例详情：[3.6.留存](https://help.growingio.com/retention.html)

###**实时分析**  
**功能说明**：目的是通过对网站／App的实时监控，让客户实时掌握用户情况和及时作出反应。

###**热力图**  
**功能说明**：
热图功能中，可以通过页面本身的热区来监测页面内容的热度，点击越多的内容越亮，反之则越暗，GrowingIO 的热图是根据页面中的内容来绘制热区，自动过滤页面空白处的无效点击，比基于位置的热图绘制更准确。[热力图](https://help.growingio.com/Features/heatmap.html)






---
###**看板**  

**定义**：多个相关单图组合成的整体报表。将一个业务相关单图放在一起整合成看板, 可以从各个维度全面了解该业务的运营情况。  
制作方法参见：[3.4.2.看板](https://help.growingio.com/Features/allchart/dashboard.html)

---
###**标签**   
**定义**：对一个单一事件的定义：对一任意一页面，或不同页面中文本，图片，按钮等进行的定义。   
制作方法参见：[3.3.4.圈选](https://help.growingio.com/Features/circle/tag.html)

---
###**指标**   
**定义**：标签的某一个行为(比如点击或者浏览)的聚合。指标是分析对象，也是生成图表的必备条件，通常用作为图表的Y轴。指标可由单个标签生成，或者由多个标签运算而得。  
制作方法参见：[3.3.5.指标](https://help.growingio.com/Features/circle/metric.html ) 

---
##可视化作图  
###**横向柱图**   
**定义**：横向柱状图可以将数据按照一定的维度划分，以分析同一个指标在不同纬度的表现情况。Y轴需要添加一个指标，X轴需要一个维度。

---
###**纵向柱图** 

**定义**：展示指标随着时间的变化趋势。

---
###**线图**   
**定义**：线图能够很好的展现指标随着时间的变化趋势，可以将一到五个指标拖到Y轴,作为分析对象。X轴固定为时间，可以对时间属性进行选择，例如：天，小时。

---
###**气泡图**  
**定义**：气泡图是散点图的升级，散点图使用的是成组的X、Y值，只能制作二维图表，一般气泡图使用的是成组的X、Y、Z值，可以在平面上制作三维图表，X和Y分别对应坐标轴，Z用来确定气泡的大小；在此基础上，GrowingIO还提供了第四个可选指标，用气泡的颜色来表示，您可以根据场景灵活选择是否需要使用该指标。  



---
###**表格**   
**定义**：以矩阵方式呈现数据。

---
###**双向柱图**   
**定义**：双向柱状图可以清楚的展现同一个指标中，最高和最低的数值。Y轴需要添加一个指标，X轴需要添加一个维度。  

**举例**：双向柱图帮您展示指标的两端数据。比如付费用户活跃度的双向柱图（以活跃度大小作为双向柱图的指标）。活跃度前十的付费用户，（由于对产品使用度高）续购，增购可能性大。活跃度后十位的客户，对产品使用度低，有流失风险，应该尽早介入。

---
###**数值**    
**定义**：数值图可以最直观的展现关键数据，需要拖入一个指标，可以加入维度进行平均值运算。

---
###**漏斗图**   
**定义**：漏斗图是用来分析转化情况的重要工具，漏斗图将显示一个指标到下一个指标的转化率。可以添加二到五个指标。  

**备注**：漏斗图目前只能统计用户量，即使拖入了 visit 指标，数据也只显示 Unique User 总数。








