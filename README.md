# NUIST_AutoHealthReport
## 南京信息工程大学每日健康打卡自动化

### 8月9日升级
本自动化升级后无需抓包等繁琐操作，在Paste_To_Me.txt中输入学校账户密码即可！

### 简介
本项目基于dsus4wang学长的 [打卡自动化](https://github.com/dsus4wang/NUIST_AutoDailyHealthReport) 项目，添加了Github Actions动作，允许将项目部署在actions中定时自动运行，并简化了使用步骤。
### 注意
使用本自动化需要对github有 [入门了解](https://www.runoob.com/w3cnote/git-guide.html) ！

## **fork本仓库后务必将仓库属性设为私有，以防止信息泄露！**

-----------
### 用法

1. 打开Paste_To_Me.txt,在第一行填入学校账号，第二行填入密码。保存然后commit。
2. 打开仓库页面中actions选项卡，稍等一会你应该能看到开头的workflow！至此部署结束，脚本将会在每天七点为你打卡！
3. 如果你发现workflow运行不成功，那么进去re-run一遍。或者检查你的配置是否有问题。