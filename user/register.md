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
        "id": 1002, // 用户ID
        "userName": "无名氏", // 用户名，默认为“无名氏”
        "avatar": null, // 用户头像
        "deviceId": "jovan_test_device_id_3", // 手机设备ID
        "hardwareId": null, // 硬件ID
        "mobileOS": "ios", // 手机操作系统
        "modelNumber": "iPhone 7", // 手机型号
        "modelVersion": "10.0.0", // 手机版本
        "appVersion": "1.0.0", // APP版本
        "hardwareVersion": null, // 硬件版本
        "createdOn": "2018-08-03T16:23:46.000+0800", // 创建时间
        "updatedOn": "2018-08-03T16:23:46.000+0800" // 修改时间
    }
}
</code></pre>
