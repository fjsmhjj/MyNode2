# 监控-拓扑
**该页面为拓扑图页面，如下图：**<br>
![](/images/aimonitor_map.png)

* Ai 通过拓扑图来展示应用的端到端调用关系、应用服务器与数据库、外部 服务的调用关系以及应用之间的调用关系。同时，通过在拓扑图中将相应模块 标记成不同颜色（灰色代表无数据;红色代表不满意;黄色代表一般;绿色代 表满意），让用户能够直观了解应用运行期间、各个环节的健康状况。

**应用程序：**

* 拓扑图中，能够展示出应用程序之间的调用关系，但最多只能展示 两级。<br>
* 点击应用程序图标，会弹出窗口，展示应用的响应时间、吞吐量、 错误率（吞吐量和错误率都会展示总数和每分钟数目）。<br>

**用户终端：**

* 用户终端是发出 http 请求的起点，即事务的起点。<br>
* 点击用户终端图标，会弹出窗口，提供“查看”链 接。再次点击，会跳转到 BI 产品的当前应用中。<br>
* BI 是 OneAPM 专为用户的“浏览器终端性能监控”而生的一款产品。与 Ai 一同使用，可以更好实现端 到端的完整流程监控。<br>

**外部服务：**

* 外部服务调用，即应用程序调用第三方提供的 API 并获得相应数据、服务的过程。<br>
* 点击外部服务图标，会弹出窗口，展示外部服务 的服务器名称、平均响应时间、调用次数和每分钟调用次数。<br>

**数据库：*** 数据库调用，即应用程序对数据库进行增、删、改、查操作的过程。<br>
* 点击数据库图标，会弹出窗口，展示数据库操作的名称、平均响应时间、调用次数和每分钟<br>
