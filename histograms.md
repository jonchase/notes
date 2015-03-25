Some different histogram implementations:

* https://github.com/HdrHistogram/HdrHistogram
* https://github.com/tdunning/t-digest
* https://github.com/dropwizard/metrics/blob/master/metrics-core/src/main/java/com/codahale/metrics/Histogram.java
* https://hadoop.apache.org/docs/current/api/org/apache/hadoop/mapreduce/lib/aggregate/ValueHistogram.html
* https://github.com/twitter/ostrich/blob/master/src/main/scala/com/twitter/ostrich/stats/Histogram.scala
* https://github.com/apache/cassandra/blob/trunk/src/java/org/apache/cassandra/utils/EstimatedHistogram.java
* https://github.com/apache/cassandra/blob/trunk/src/java/org/apache/cassandra/utils/StreamingHistogram.java

### Druid

* http://druid.io/docs/latest/ApproxHisto.html
* https://github.com/druid-io/druid/blob/master/extensions/histogram/src/main/java/io/druid/query/aggregation/histogram/ApproximateHistogram.java
* http://jmlr.org/papers/volume11/ben-haim10a/ben-haim10a.pdf