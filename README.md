
# 项目目标
1. 使用**skynet_fly**开发企业级可上线游戏项目。
2. 完成可扩展支持服务集群部署。
3. 用**skynet_fly+vue**搭建安全可靠的admin后台，支持服务监控，警告日志查询，用户操作日志查询，游戏记录日志查询，数据看板。
4. 游戏可全区全服匹配。
5. 完成中国象棋游戏。
6. 后续添加球球大作战，自走棋等等游戏。

# 快速开始
拉取skynet_fly仓库
`git submodule update --init`
编译skynet_fly仓库

安装数据库
`sh dbinstall/setup.sh`

启动mysql
启动redis

启动所有服务
`sh script all_restart.sh`
