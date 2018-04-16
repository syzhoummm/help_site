# App 分析词汇



### **用户**
**定义** ：使用app的用户。

用户以设备为判断标准，在移动统计中，每个独立设备认为是一个独立用户，有自己的唯一ID。用户唯一ID在几个字段中获取，按照如下的顺序。

安卓：AndroidID->IMEI->随机数

iOS：IDFV->随机数

大部分情况下，用户ID都不会取到随机数。用户ID会保存在用户手机上。这就是说，如果用户不删除应用，一台设备的ID是固定的。如果用户删除应用再安装，取随机数的用户ID会生成新的随机数，被认为是新的用户，其他情况用户ID仍然不变。

**备注** ：下载未激活不能算是用户。

---
### **新用户**
**定义** ：第一次联网使用App的用户。 

**说明** ：用户使用过App后卸载，并且再次安装使用，那么只要该用户的设备没有更换或重置，则两次视为同一个用户，即第二次安装不算作新增用户。特殊情况是用户ID取到了随机数的时候，请参见上方“用户”的定义。

---
### **活跃用户**
**定义** ：打开应用的用户即为活跃用户，不考虑用户的使用情况。每天一台设备打开多次会被计为一个活跃用户。

**说明** ：活跃用户通常都会有一个时间范围做约束的，例如日活跃用户、周活跃用户、月活跃用户等。活跃用户指标是一个应用用户规模的体现，同样也是衡量一个应用质量的最基本指标，结合留存率、流失率、使用时长等指标还可以体现用户粘性。

---
### **赢回/唤醒用户**
**定义** ：针对已经流失的用户，采取用户赢回策略生效后，重新开始使用应用的用户。

---
#### **累计用户**
**定义** ：从产品上线开始的总用户量。

---


### **一次性用户**
**定义** ： 自从首次打开应用日后再也没启动过应用的用户。

---
### **升级用户**

**定义** ：从老版本升级到该版本的用户记为该版本的升级用户。

---
###**启动次数**
**定义** ：应用发生启动行为的次数。用户数是从规模上描述应用，而启动次数是从访客角度衡量访问质量的分析指标。如果一个应用的用户体验足够好，用户粘性足够高，同一个用户一天中会多次启动应用，那么启动次数就会明显大于访客数。

---
### **使用频率**

**定义** ：在一定时期内，同一个用户启动应用的次数。如在一天之内，同一个用户一共进行有效启动6次，那么该用户的日使用频率就是6次。

**说明** ：使用频率和日启动次数类似，只是从另外一个角度衡量用户粘性，一个应用通常情况下用户粘性越高，那么用户的平均使用频率也就越高。

---
### **使用间隔**
**定义** ：用户上次使用(session)应用的时间与再次使用的时间差。

**说明** ：使用间隔也从侧面反映了应用的用户粘性，通常情况下使用间隔越短说明用户越依赖应用，也就是说应用的用户粘性越高。也可以据此来决定推送消息的时机和发版频率。


---

### **错误次数**
**定义** ：在规定的时间段内，App出现异常退出现象的次数总和 。

**说明** ：通常情况下，App错误集中于两种：死机或强退，这样的现象都会严重影响用户体验，所以错误次数发生的越高，用户体验越差。降低错误次数是开发者应该时刻关注的重要指标。


---

### **错误率**
**定义** ：错误或者异常发生的概率，错误次数/启动次数。

**说明** ：产品质量是一个应用发展壮大的基石，与网站不同，移动应用一旦被分发之后就无法再收回，应用错误率高会降低用户对产品的信任和口碑。通过对应用的质量监控，找到错误代码并及时发布修复版本，可以有效弥补这一问题。