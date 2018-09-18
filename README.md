# QA Client For HUST'S QA System
- author:fox
- email:cszhenyuhu@foxmail.com
- 如果程序有bug请描述bug产生的情况，附上错误截图，我收到邮件后会及时更新！
- 有需要添加的新功能，也请发送到邮箱，我有空或许会实现！

## 运行方式
- 用户需要安装java8环境
- 为了方便用户的使用，我已经把程序在java8下编译好的jar包放在${PROJECT_ROOT}/lib下，名字为qa.jar。用户可以直接clone本仓库到本地，在终端切换到项目的lib目录并运行 java -jar qa.jar即可运行。
- 当系统安装了JRE环境时，直接在文件管理界面中双击运行qa.jar即可运行，但是这样操作日志将无法显示在终端。


### 登陆
点击登陆按钮登陆本系统，登陆成功或者失败都会有提示，程序可能在登陆过程中，出现卡顿，
这是正常的网络波动，导致的线程卡顿，稍等几秒或者十几秒便可。
第一次登录后，可以选择记住账户密码到本地文件，下次启动将自动从本地文件加载用户登录。


### 添加单日qa：
在主界面日历选择日期
界面右边 较窄的文本框为title，
较宽的文本框为具体内容，输入完毕后点击“添加按钮”即可添加到所指定日期的QA记录中


### 更新特定日期qa：
在日历中选择日期，程序会自动刷新该天的qa记录到界面下方的表格，双击相应表格，修改内容后，右键表格，选择弹出按钮的更新操作，即可更新，该操作支持批量更新，即可选择多条记录同时更新

### 删除单日qa
可点击左上角日历选项，选择日期，程序会自动刷新该天的qa记录到界面下方的表格中
同时选中一条或者多条记录，右键表格，点击删除

### 批量添加
点击查询按钮，可以先查询两个日期之间的qa记录例如查询9-1到9-10号之间的qa记录，发现从9-3，至9-10号的qa记录都没有写，则将日历起始日期调整为9-3👌。
选择要添加的起始日期和终止日期，将内容填写一键添加按钮上方的方框内，点击一键添加按钮即可添加完毕
* 注：添加和更新操作只限操作当天的QA记录，如果不是操作当天的记录，那么运行程序的日期需要为周六或者周末

