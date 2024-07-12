Maven
===

此备忘单列出了一些常见的 Maven 命令。

清除本地仓库下面的snapshot旧版本

如果

```
mvn dependency:purge-local-repository -Dinclude=com.package1,com.package2
```
