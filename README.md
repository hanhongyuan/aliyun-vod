# aliyun-vod
使用阿里云的视频点播功能

# 注意事项，下面需要修改成自己的配置
#阿里云 vod
#不同的服务器，地址不同

aliyun.vod.file.keyid= 

aliyun.vod.file.keysecret=

## 上传报错:  java.lang.NoSuchMethodError: com.aliyuncs.vod.model.v20170321.CreateUploadVideoRequest.setSysConnectTimeout(Ljava/lang/Integer;)V
是有一个依赖导错了：

<dependency>
    <groupId>com.aliyun</groupId>
    <artifactId>aliyun-java-sdk-core</artifactId>
    <version>4.3.3</version>
</dependency>

## aliyun视频点播
![image](https://github.com/wangzhan6666/image/blob/master/aliyun-vod/%E9%98%BF%E9%87%8C%E4%BA%91%E8%A7%86%E9%A2%91%E7%82%B9%E6%92%AD.png)

## 测试结果
![image](https://github.com/wangzhan6666/image/blob/master/aliyun-vod/%E7%BB%93%E6%9E%9C.png)
