青龙面板 薅羊毛 微信阅读 多用户高收益<br>
~单微信号每日收益2块左右 3000金币=0.3元即可提现到微信钱包<br>
~6秒一篇文章得120金币 每小时30篇 每天6轮 180篇文章共21600金币=2.16元<br>
--
在微信中打开  https://zl0114225029-1314804847.cos.ap-nanjing.myqcloud.com/index.html?upuid=10688156
--
打开后自动转跳阅读文章 空白页关闭后 重新打开 <br>
转跳到文章页面停6秒 返回上一页 重复操作30次即可 <br>
可以在安卓或苹果手机中的微信里操作 也可以用PC版微信的自带浏览器等等<br>
单个微信号 可以自己写个简单的模拟按键延迟点击脚本 并且不会有验证文章卡住的问题 
--
青龙面板可以在windows系统 安卓手机 软路由 linux docker 等安装均可 <br>
安装教程自动百度 这次从可以打开青龙面板 5700端口开始<br>
青龙面板-定时任务-新建任务<br>
名称随意 脚本复制下面内容
```Shell
ql repo https://ghproxy.com/https://github.com/jiasai007/wxyd.git
```
定时规则 
```Shell
0 0 0 * * 1
```
点击 确定 后在操作栏中 点击 运行 该脚本

运行成功后 设置 微信阅读 脚本 定时规则为 0 */30 * * * ? 

青龙需要抓包m.*.shop域名下cookie,
在环境变量 新建 wxyd 多账户换行隔开
