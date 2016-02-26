# MySQL-Binlog
连接到MySQL数据库，基于Netty框架，实时解析MySQL的二进制日志binlog而非定时查询数据库，提取出用户级感兴趣的事件:INSERT,UPDATE,DELETE,供后续分析如事件抛到大数据系统进行分析。目前支持的事件包括:ROTATE, FORMAT_DESCRIPTION, QUERY,TABLE_MAP, [WRITE_ROWS,EXT_WRITE_ROWS] [UPDATE_ROWS,EXT_UPDATE_ROWS] [DELETE_ROWS,EXT_DELETE_ROWS] XID ROWS_QUERY --- JDK版本:建议选择1.8,已经实现web界面和ZK集群，直接查看《MySQL-Binlog使用文档.doc》根据指示一步步操作即可。使用过程中有问题或者bug,请进入官方群: 398822659
