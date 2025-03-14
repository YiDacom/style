# docker从自己阿里云拉取镜像
解决执行docker pull命令拉取docker镜像时无反应，一直在循环尝试：
1：参考解决：(https://blog.csdn.net/weixin_46203834/article/details/140556611)
2：修改workflows/blank文件中最后一行同步命令，修改需要拉取的镜像文件
3：阿里云中查看，docker登录拉取镜像成功：https://cr.console.aliyun.com/repository/cn-guangzhou/liyida/nacos-server/details
