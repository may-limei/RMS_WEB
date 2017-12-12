# 基于EPICS和web技术实时监测系统

<pre>EPICS是一套开源的分布式软件架构，具有比较开放的系统结构和齐全的功能组件，基于EPICS开发在线监测系统可大大的降低系统成本，提高系统的兼容性。EPICS软件体系是典型客户端服务器形式，现有的客户端软件都存在一定的问题，例如EDM软件美观度和可视化能力不足，CSS基于java的架构体系体系过于臃肿，QtEpics控件支持不够完善等，再加上客户端软件统有的缺点：界面文件更新不便利等，驱使我们开发一种基于B/S架构的EPICS应用。本文介绍了基于Nodejs的EPICS插件开发网站服务器，利用比较成熟的Bootstrap和Jquery框架开发前端界面，利用echart插件实现数据可视化的EPICS在线监测技术。本项技术已应用到了中科院核能先导专项钍基熔盐堆辐射监测系统上面。在数据实时性、数据可视化、数据安全性方面都优于原来的系统</pre>