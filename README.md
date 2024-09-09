项目背景（需求）：
1.需要上线服务，要求可以从Postgresql(存放交易日历)中获取交易日历，并根据不同的交易所获取它的交易日期，并将这些交易日期组成一个集合返回，并且可以通过web路由的方式对交易日期进行标记，所标记的交易日会单独存放到一个数据库中。\n
2.需要开发一个同步web平台，可以实现实时同步删除和路由同步删除，需要删除的交易日期需要请求Market_Calender平台获取，然后根据Apollo和Msyql确定数据类型,日期tag以及在Minio存储桶中的位置同步到阿里云OSS桶中。\n

![image](https://github.com/user-attachments/assets/b20f20a3-73b0-426b-a4fb-14c919e3154c)
