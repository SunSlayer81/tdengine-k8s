# tdengine-k8s
taos,tdengine,docker,k8s

# TDengine cluster for kubernetes

# TDengine cluster for docker

# What is TDengine？

TDengine is an open-sourced big data platform under [GNU AGPL v3.0](http://www.gnu.org/licenses/agpl-3.0.html), designed and optimized for the Internet of Things (IoT), Connected Cars, Industrial IoT, and IT Infrastructure and Application Monitoring. Besides the 10x faster time-series database, it provides caching, stream computing, message queuing and other functionalities to reduce the complexity and cost of development and operation.

- **10x Faster on Insert/Query Speeds**: Through the innovative design on storage, on a single-core machine, over 20K requests can be processed, millions of data points can be ingested, and over 10 million data points can be retrieved in a second. It is 10 times faster than other databases.

- **1/5 Hardware/Cloud Service Costs**: Compared with typical big data solutions, less than 1/5 of computing resources are required. Via column-based storage and tuned compression algorithms for different data types, less than 1/10 of storage space is needed.

- **Full Stack for Time-Series Data**: By integrating a database with message queuing, caching, and stream computing features together, it is no longer necessary to integrate Kafka/Redis/HBase/Spark or other software. It makes the system architecture much simpler and more robust.

- **Powerful Data Analysis**: Whether it is 10 years or one minute ago, data can be queried just by specifying the time range. Data can be aggregated over time, multiple time streams or both. Ad Hoc queries or analyses can be executed via TDengine shell, Python, R or Matlab.

- **Seamless Integration with Other Tools**: Telegraf, Grafana, Matlab, R, and other tools can be integrated with TDengine without a line of code. MQTT, OPC, Hadoop, Spark, and many others will be integrated soon.

- **Zero Management, No Learning Curve**: It takes only seconds to download, install, and run it successfully; there are no other dependencies. Automatic partitioning on tables or DBs. Standard SQL is used, with C/C++, Python, JDBC, Go and RESTful connectors.

# Documentation
For user manual, system design and architecture, engineering blogs, refer to [TDengine Documentation](https://www.taosdata.com/en/documentation/)(中文版请点击[这里](https://www.taosdata.com/cn/documentation20/))
 for details. The documentation from our website can also be downloaded locally from *documentation/tdenginedocs-en* or *documentation/tdenginedocs-cn*.

# TODO
TDengine配置文件全字段支持