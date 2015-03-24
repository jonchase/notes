SparkSql doesn't contain a specific interface for registering custom Hive UDAFs, but it's still possible:

```java
sqlContext.sql("create temporary function foobar as 'com.myco.FoobarUDAF'");

sqlContext.sql("select foobar(some_column) from some_table");
```
