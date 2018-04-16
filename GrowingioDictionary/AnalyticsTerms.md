# GrowingIO分析词汇

## 维度

### **页面 (*Web Page*)**  
**定义**：按 URI 列出的已访问网页。URI 是指网页网址中跟在域名后面的部分；例如 https://www.growingio.com/joinus 中的 URI 就是 /joinus。

**举例** : 页面可以区分跨页面元素在不同页面的表现情况。比如某些网站的导航栏在网站的每个页面都出现（在上述情况下导航栏就是跨页面元素）。

---



###**页面来源 (*Referral Path*)**
**定义**：页面来源帮您了解当前访问页面的上级页面。制作单图时以URI方式进行展现。  

**举例**：我们可以制作横向Bar图，观察目标页面（如注册页面，或者购买页面）由哪些页面引入，从而可以对那些表现低于预期的页面进行优化。    

**技术说明／备注**：GrowingIO 系统会统计每一个事件发生时所对应的页面来源。

---
###**域名 (*Domain*)**  
**定义**: 是由一串用点分隔的名字组成的Internet上某一台计算机或计算机组的名称，用于在数据传输时标识计算机的电子方位。域名就相当于一个家庭的门牌号码，别人通过这个号码可以很容易的找到你。比如说大家在网站URL栏目输入：www.growingio.com 就能进入 GrowingIO 的网站。

**举例**：GrowingIO 分析中你可以使用报表系统，选择域名作为维度，选择PV，UV等作为指标，分析不同子域名下的页面浏览访问量等。

---
   
###**浏览器 (*Browser *)** 
**定义**: 用户所用浏览器的类型，常见的值有：Chrome，Chrome Mobile，Safari，IE等该维度中不包括内部的版本号。

**举例**:可以使用浏览器来区分不同使用不同浏览器的用户对指标的贡献情况。

---
 ###** 浏览器版本（*Browser Version*）** 
 **定义**: 同「浏览器」，但是会按照不同的版本进行区分。如：Chrome 47.0.2526。

--- 
  ###** 操作系统（*Operating System *）**  
  **定义**:用户所使用的操作系统，包含PC和Mobile，如：Windows 8 ，Windows 7 ，Mac OS X ，Android。
 
---

 ###** 操作系统语言（*Operating System Lauguage *）** 
  **定义**:将操作系统的语言作为维度值，以统计不同的操作系统语言的使用情况。
  
  ---
  
   ###** 城市（*City *）** 
**定义**:以城市作为维度值，帮助了解不同城市的访问情况。目前只支持国内城市。
**技术说明／备注**：GrowingIO 基于IP地址得到城市地址。
     

 ---
 ###** 地区（*Area  *）** 
 **定义**:该维度包含国内省级以上行政区，以及国外地区。  
 
 **举例**:地区帮您了解各个地域带来的流量及转化情况。您也可以选择来源过滤，查看特定来源各地域的数据。
 **技术说明／备注**：GrowingIO 基于IP地址得到地区地址。
 
 ---
 ###** 国家代码（*Country Code *）** 
 **定义**:用户所在的国家的英文缩写，常见的维度值有：CN，US，JP，SG等。
 
 ---
###** 国家名称（*Country *）**   

**定义**:用户所在的国家的名称，常见的有：中国，美国，英国，新加坡等。

---
###** 网站／手机应用（*Web/App *）** 
**定义**:用于区分浏览器访问和App访问。

---
###** 访问来源（*Source  *）** 
 **定义**:访问来源可以帮助您了解该网站流量来源，访问来源可以是百度，谷歌，优酷等站外渠道，也可能是直接访问该网站。  
 
 **技术说明／备注**Traffic Source 的最细分的级别是Referring Sites，即哪些网站或是搜索引擎为你贡献了流量，但却无法细分到具体的广告。可以通过设置UTM参数来确定流量具体是哪个广告带来的。
 
 ###** 一级访问来源** 
  **定义**:一级访问来源将访问来源分为直接访问，搜索引擎，社交媒体，外部链接四大部分。
  **技术说明／备注**
直接访问：
refer为空，意味着用户可能通过直接输入域名或收藏夹访问
搜索引擎：
来自以下地址的均属于搜索引擎：www.baidu.com，m.baidu.com，bzclk.baidu.com， so.com, sogou.com（soso.com已指向这里）, bing.com, youdao.com，zhongsou.com，google.xx.xx（Google在全世界有各种各样的域名），sm.cn（神马搜索),yahoo.com
社交媒体：
来自以下地址均属于社交媒体：weibo.com，t.cn, weibo.cn,zhihu.com，linkedin.com，lnkd.in，renren.com，facebook.com，twitter.com，mp.weixin.qq.com，wx.qq.com，im.dingtalk.com，mp.weixinbridge.com
外部链接：
除了社交媒体，搜索网站之外的来源
 
 
 ---
###** 搜索词（*Search Query *）** 
 **定义**:
用户从搜索引擎进入网站所使用的搜索词；一般情况下付费搜索的搜索词可以被解析，而百度谷歌渠道自然搜索词无法获取。详情参见：[5.1.渠道跟踪](https://help.growingio.com/channeltrack.html)

---

###** 广告关键字（*utm_term *）**
 **定义**: GrowingIO 使用utm_term 来标识付费关键词。
 
---
###** 广告来源（*utm_source *）** 

 **定义**:GrowingIO 使用 utm_source 来标识 搜索 引擎、简报名称或其他来源。
 示例：utm_source=baidu。"
 
 ---
###** 广告媒介（*utm_medium *）** 
 **定义**:GrowingIO utm_medium标识广告传播媒介或者营销媒介。
 
 ---
###** 广告内容（*utm_content *）** 
 **定义**:GrowingIO 使用 utm_content 区分指向同一网址的 广告或链接。
示例：utm_content=logolink 或utm_content=textlink。  


 **举例**:在链接"http://www.example/com?utm_source=sina&utm_medium=banner&utm_content=linktag&utm_term=grow&utm_campaign=IloveWA  中  

|  utm参数| 含义 |
| -- | -- |
| utm_source | 指广告所处的网站位置 |
| utm_medium |指广告的具体形式  |
| utm_content |指广告的具体内容 |
|utm_campaign |指投放广告的这次营销活动的名称 |



具体设置方法请参见：[5.1.渠道跟踪](https://help.growingio.com/channeltrack.html)

**技术说明／备注**：UTM 广告系列参数对着陆页面的url进行标注，可以区别衡量各种营销渠道所带来的访客价值。在这里渠道归因采取的是非直接访问最后点击模型。  比如，访客于9:30分访问网站。我们进行渠道归因时，会统计在10:00点开始，回溯30天时间，其最后一次通过外站（非直接流量）进来时的UTM参数，关键词和refer URL。举个例子，访客A通过百度推广进入网站，然后通过sina Banner再次进入网站，最后一次通过直接输入URL进入网站完成购买，我们会认为这次转化由Sina Banner贡献。

 ---
 
 ###**用户传输字段**   
  **定义**:用户可以上传自定义用户属性类数据,并将其设为维度来针对自己的产品做更深度的细分。  
 **技术说明／备注**：   用户上传的自定义字段用CS1～CS20表示。其中CS1 强制填写userID数据；CS2建议填写CompanyID；CS3~CS20由用户自主设置；一般情况下用户可以通过接口(Server to Server)和JS将数据传递给我们。通过接口传递的数据，数据不是时时更新的，只有企业客户出发更新，GrowingIO 才能获得最新结果。若使用JS，数据则是时时更新的。
 具体设置方法请参见：[属性数据(CS)上传 API 说明文档](https://help.growingio.com/AttributeDataDocumentation.html)
   
   
   
   
---   
    
##指标



###** 页面浏览量（*Page View *）** 
 **定义**:访客实际浏览过的网页数(PV)的总和。  
  **技术说明／备注**：PageView 在如下情况下大于元素所在页面浏览量impression：
 1. 由于权限原因，时间原因，地域原因，某些 impression 不是每次都出现在页面上； 
 2. Pageview 加载一半，此时PV计为1， 未加载元素的impression计为0； 
 3. 页面静止一个 session 后，用户重新在页面上操作。Pageview 加1而 impression 不变。
 

---
###** 访问用户量（*User *）** 
 **定义**:指GrowingIO用来标记用户的u字段的去重数量，用来分析独立访问用户的数量。  
 **技术说明／备注**：当 cookie 改变，或者使用不同的设备登陆时，会被计算为新的用户。
 使用app的用户。用户以设备为判断标准，在移动统计中，每个独立设备认为是一个独立用户。Android系统根据IMEI号，iOS系统根据IDFV来标识一个独立用户。
 
---

###** 登录用户量（*Login User *）** 
 **定义**:登录用户的数量。
 
 
###** 新登录用户量（*Login User *）** 
 **定义**:新登录用户的数量。
 
  **技术说明／备注**：要想获得登录用户量，与新登录用户数量的统计，您需要上传用户属性字段。具体设置方法请参见：
 [属性数据(CS)上传 API 说明文档](https://help.growingio.com/AttributeDataDocumentation.html)
   
 
 ---
 
###** 访问量（*Visit *）** 
 **定义**:会话（session）的数量。
 
 **技术说明／备注**：访客从进入网站到离开网站的一系列活动记为一次访问，也称会话(Session),1次访问(会话)可能包含多个PV。
    App Visit计算方法：看不见App超过30秒到看见App（杀进程重启），visit会增加一次。
 
 ---
###** 跳出率（*Bounce Rate *）** 
 **定义**:所有会话（session）中，计算只有一个访问页面的会话占全部会话的比例。 ：用于衡量落地页质量。
 
 **技术说明／备注**："我们现在的跳出率是针对整个网站的, 计算方法是 只有一个页面的 访问数量 (visits/sessions)  / 总访问数
如果用户在第一个访问的页面点击刷新当前页面, 然后离开了, 虽然产生了2个page view, 但还是算作bounce。"

---
###** 新访问用户量（*New User *）** 
 **定义**: 一天的独立访客中，历史第一次访问您网站的访客数。   
 
  **应用**: 新访问用户一般会和其他指标或维度结合使用。您可以用新访问用户量来衡量广告推广的效果。例如一次推广带来多少新访客，这些访客在网站上停留了多少时间，转化率是多少。通过这些维度指标的结合，您可以评价这次推广是否达到期望。  
 
  **技术说明／备注**："九十天之内 cookie 第一次出现，GrowingIO 计为一位新访客／例子： 如果同一个U 在九十一天之前访问本站，今天再次访问，则这位访客（即使曾经访问过
）计算为新的访客。"
对于App新用户计算方法： 用户唯一ID获取方法：AndroidID->IMEI->随机数；iOS的IDFV->随机数。大部分情况下，用户ID都不会取到随机数。用户ID会保存在用户手机上。这就是说，如果用户不删除应用，一台设备的ID是固定的。如果用户删除应用再安装，取随机数的用户ID会生成新的随机数，被认为是新的用户，其他情况用户ID仍然不变。

---
###** 访问时长（*Average time on site *）** 
 **定义**: 平均每次访问(会话)在网站上的停留时间。平均访问时长=访问时长/访问次数。体现网站对访客的吸引程度。  
 
 ####**活跃天数**
**定义**:在一定时间范围内有过访问或者行为的天数。比如一位客户在七天内的5天有过访问／登陆行为，那么我们认为的活跃天数是5天。
**技术说明／备注** 在这里我们不考虑每一天的登陆频次，只要当天有过访问／登陆行为就可以视为当天活跃。
###** 平均页面停留时长** 
**定义**:平均每次访问(会话)在网站上不同页面的停留时间，可以分析不同页面吸引访客的程度。


 
 ---
 
  ##App专有维度
  
 ###** 设备品牌（*Device Brand *）** 
  **定义**:将不同设备的品牌作为维度值。
 
 ---
 ###** 设备型号（*Device Type *）** 
 
 **定义**:不同的设备型号作为维度值，可用于区分具体的机型。
 
 ---
 ###** 设备类型（*App/Pad *）** 

 **定义**:设备的类型，平板和手机，用于App分析
 
 ---
 ###** 安卓渠道（*Android Store *）** 

 **定义**:表示app下载地址（安卓市场）。
 
 ---
  ###** 设备方向（*Device Orientation *）** 
 

 **定义**:移动设备的方向，水平和竖直。
 

 
 











