
# 1 技术基础
1. mysql-binlog体系
2. canal/flink数据抽取
3. mq消息队列

注： oracle中类似的是GoldenGate体系，用于得到数据的变更内容

# 2 业务场景
1. 用于多端数据同步，如mysql（db）同步到Elastic Search（ES）、Redis（缓存）等
2. 用于处理一些自动化流程的场景，如监听消息并接入一些业务流程等



# 3 参考资料
1. [# 手把手告诉你如何监听 MySQL binlog 实现数据变化后的实时通知！](https://ost.51cto.com/posts/16999)
2. 