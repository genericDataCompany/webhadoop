WebHadoop
=========
### 环境要求	
1. 需要所有人都配置相同的开发环境
2. Hadoop: Hortonworks
3. Github 建立项目
4. 需要每一个人都可以打包
5. 目的：磨合团队
6. 风险：各位都有工作，所以我们需要有项目管理，无论多大的项目。

### 需求梳理	
1. 期望在安全模式（Kerberos）的HDFS实现与自带web console类似功能
2. 界面可以实现HDFS权限控制
3. 实现权限控制（跟hdfs文件系统一致，类似操作系统的，主要就是界面用户与操作系统用户的映射问题）
4. 提供JobTracker的界面 （非必须）

### 技术问题点	
1. 安全机制（kerberos）下restful 如何可用
2. restful api 研究
3. restful 目前看客户不要求性能，应该只是查看
