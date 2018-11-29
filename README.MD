### 分布式日志收集系统

#### 1.解决方案
a.将服务器上的日志实时收集，统一存储到中心系统。

b.对日志建立索引，通过搜索即可找到相应日志。

c.通过提供友好的web界面，通过web即可完成日志搜索。

#### 2.系统架构
<img src="https://ws1.sinaimg.cn/large/70ecf2fbly1fv398apz0ej21700uqtb2.jpg" height=350 width=450>

##### 2.1系统组件介绍
a.logAgent: 日志收集客户端，用来收集服务器上的日志。

b.kafka: 高吞吐量的分布式消息队列。

c.ES(elasticsearch): 开源搜索引擎，提供基于http restful的web接口


