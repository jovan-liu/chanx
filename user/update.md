# Update User
---
# 请求类型: PUT
# URL: https://jovanapi.top/user/update
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
id | 用户ID   | Long
userName | 用户名（可选）  | String
avatar   | 用户头像 (可选)         | String
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 1002,
        "userName": "jovan.liu3",
        "avatar": "test3.png",
        "deviceId": "jovan_test_device_id_3",
        "hardwareId": null,
        "mobileOS": "android",
        "modelNumber": "MI 6",
        "modelVersion": "9.6.2",
        "appVersion": "1.0",
        "hardwareVersion": null,
        "createdOn": "2018-08-03T13:14:06.000+0800",
        "updatedOn": "2018-08-09T20:55:21.000+0800"
    }
}
</code></pre>
