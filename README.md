# 使用步骤
1、下载下来该项目，导入到idea里；如果是线上环境，用mvn clean install 打包后，然后把jar包导入到线上环境

2、修改application.properties和bootstrap.properties中的配置项

3、找到Main方法

4、运行

# 注意事项
使用时请注意，将{namespaceId}替换成mse上的namespaceId
![image](https://user-images.githubusercontent.com/58767027/205231384-1aadb172-b00d-40d5-b367-cbc3e6449ed1.png)

将{accessKey}和{secretKey}替换成用户阿里云账号的AK和SK，获取方法请参考：https://help.aliyun.com/document_detail/451821.html?spm=a2c4g.11186623.0.0.31504225uaCy99

{regionId}替换为用户所在地域，如杭州用户：cn-hangzhou 上海用户： cn-shanghai
