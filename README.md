## MySQL 系统字典库的根目录
* MySQL 的information_schema、mysql schema、performance_schema中，记录着MySQL Server内部的数据字典信息、锁信息、索引统计信息、复制状态信息、性能数据信息等，囊括了MySQL Server内部暴露出来的绝大部分信息，通过这些信息我们可以更加全面、方便、快捷地掌握MySQL Server内部运行的状态信息。但长久一来，网络上能够找到针对这方面的知识比较全面的除了官方手册之外，基本上还是官方手册，虽然我们在更早之前（本人就职于 杭州沃趣科技 期间），通过公司的公众号、ITPUB、CSDN、知乎等等平台完整地推送过相关的文章，但从实际的效果来看，最后对大家来说，也基本上是过眼云烟，因为在这些平台中推送的文章，本质上来讲，是碎片化的，甚至还存在着不同内容主题之间交叉推送的情况，想要回头翻看却纠结于在查找相关内容上浪费太多时间。因此，现在，将这部分内容集中开源出来，以方便大家随时随地查阅。

* <b style="color:green">我们在2019年11月出版的新书《千金良方--MySQL 性能优化金字塔法则》一书中，也针对这几个系统字典库做了大量篇幅的介绍，并增加了大量的使用案例，如有购书需求可自行前往 京东、当当等平台购买。</b>

* <b style="color:red">提示：以下4个系列文章的内容，相比我们之前在任何公开平台中推动的内容，将更加详细</b>

### [information_schema详解](https://github.com/xiaoboluo768/mysql-system-schema/wiki/information_schema%E8%AF%A6%E8%A7%A3)
* information_schema 系列已完成上传

### [mysql schema详解](https://github.com/xiaoboluo768/mysql-system-schema/wiki/mysql-schema%E8%AF%A6%E8%A7%A3)
* mysql schema 系列已完成上传

### [performance_schema详解](https://github.com/xiaoboluo768/mysql-system-schema/wiki/performance_schema%E8%AF%A6%E8%A7%A3)
* performance_schema 系列已完成上传

### [sys schema详解](https://github.com/xiaoboluo768/mysql-system-schema/wiki/sys-schema%E8%AF%A6%E8%A7%A3)
* sys schema 系列即将上传

------

* 翻译、验证、测试、整理：罗小波
* QQ：309969177
* 提示：本系列文章的主体基于Oracle MySQL 官方 5.7 手册中，关于information_schema、mysql schema、performance_schema、sys schema的章节翻译整理，并额外添加了一些验证、测试数据。鉴于本人精力和能力有限，难免出现一些纰漏，欢迎大家踊跃指正！
