# Register User
---
# 请求类型: POST
# URL: https://jovanapi.top/user/register
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
deviceId | 手机设备ID   | String
mobileOS | 手机操作系统（例如：android, ios, windows phone..）  | String
modelNumber   | 手机型号 (例如：iPhone 7)         | String
modelVersion  | 手机版本（例如：10.0.0）  | String
appVersion    | APP版本 （例如：1.0.0） | String
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 1002,
        "userName": "无名氏",
        "avatar": null,
        "deviceId": "jovan_test_device_id_3",
        "hardwareId": null,
        "mobileOS": "ios",
        "modelNumber": "iPhone 7",
        "modelVersion": "10.0.0",
        "appVersion": "1.0.0",
        "hardwareVersion": null,
        "createdOn": "2018-08-03T16:23:46.000+0800",
        "updatedOn": "2018-08-03T16:23:46.000+0800"
    }
}
</code></pre>
