# 使用Spring Data Repositories

抽象Spring Data repository的目标是显著减少所需的数据访问层实现对各种持久存储的代码量。

>Spring Data repository 文档和你的模块。
这一章节解释了Spring Data repository 的核心概念和它的接口。
这一章的信息是从Spring Data通用模块取得。它使用的是Java Persistence API(JPA)模块的配置和示例代码。 你可以使用适用于XML的命名空间和声明来扩展特定模块。命名空间参考覆盖所有被支持repositoryAPI的Spring Data 模块和支持的XML配置, Repository 查询关键字覆盖查询支持通常的repository抽象方法关键字。对于你特殊功能的详细信息可以在相关模块的章节查看。