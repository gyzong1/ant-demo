# ant-demo

本项目目标 基于ant 项目 集成JFrog Artifactory 收集Build info，进行构建信息记录

环境准备
1.搭建Artifactory 可以参考https://jiewadevops.atlassian.net/wiki/spaces/knowledge/pages/319782941/JFrog+Artifactory+POC+Guide
2.在Artifactory 创建 ant-generic-local 仓库
3.上传项目依赖的jar 包到 ant-generic-local/project-a/v1/ 
4.在本地安装ant 参考：https://blog.csdn.net/lt326030434/article/details/80192742
5.在本地安装jfrog cli 参考：https://www.jfrog.com/confluence/display/CLI/JFrog+CLI



构建发布
1.git clone git@github.com:lyqwaterway/ant-demo.git
2.进入项目目录执行 ant publish
3.查看 artifactory builds 菜单，可以看到相关构建信息
