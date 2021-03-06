# MagicMirror
基于树莓派的自制魔镜，集成MagicMirror2，Google Assistant，Home assistant，Homebridge及中文聊天机器人。

欢迎加入项目 [Slack](https://join.slack.com/t/magicmirror-cn/shared_invite/MjExNjg5MzY0NTQ1LTE0OTk5MzQyNjktMjc5YjNmMjU5Mg) ！

# 硬件
1. 树莓派3； 
2. 显示屏（拆自旧索尼笔记本，15.4寸，物理分辨率1366 x 768）；
3. 驱动板（淘宝）；
4. 单向透视镜（淘宝定制）；
5. 木框（淘宝定制）

建议：
1. 2&3可以依实际情况选择拆解显示器，或购买单屏成品，建议接口位于侧面并支持HDMI输入；
2. 可加装红外、压感等触摸板或购置触摸显示屏实现触摸功能。

# 软件
### 一、系统
1. 安装最新Raspbian with Pixel系统，务必注意安装图形化操作界面系统。
2. 基础设置
3. 打开终端，进行基本更新，包括替换源至国内。

### 二、聊天机器人
聊天机器人有多种选择，英文对话推荐使用Alexa及Gooogle Assistant（需要翻墙），中文对话可使用up主自制简易聊天机器人，拥有相应资质亦可尝试申请使用阿里云、百度等聊天机器人，有能力的可以自行开发。

#### 1. Google Assistant
谷歌助手对树莓派支持良好，客制化程度高，没有语言及网络障碍情况下首推。安装后原生在后台虚拟空间运行。

具体安装指导见：

自制简易中文版安装教程请见：

GA可与IFTTT进行联动，目前支持Yeelight智能灯具控制。

### 三、Home Assistant&Homebridge
官方网站：
GitHub：

本人于少数派发布的完整教程：https://sspai.com/post/38849


配合魔镜iFrame模块及触摸屏支持，可实现在镜子上操作家居。

**注：Home Assistant 本身是一个非常强大的平台，如果你具有开发能力，你会发现HASS和MagicMirror很多时候可以实现相同的功能，以至于只需在浏览器中打开HASS首页即可。但本篇教程偏重于后者，并尝试整合2个系统，取舍协调在于你自己。**

### 四、MagicMirror
Github: https://github.com/MichMich/MagicMirror
MM是一个模块化高度集成的魔镜项目，已经运营数年。客制化程度非常高。

具体教程见另一文件。


### 五、文件清单：
.css 黑色背景的Homeassistant界面，以配合魔镜整体环境。





