# Get User
---
# 请求类型: GET
# URL: https://jovanapi.top/user
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
id    | 用户ID （可选） | Long
deviceId | 手机设备ID（可选）  | String
loginUserId | 当前用户ID（可选）      | Long
# Tip: id或deviceId至少要传一个，即为查询的目标用户ID；loginUserId为当前用户ID
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "id": 1000,
        "userName": "管理员",
        "avatar": null,
        "deviceId": "jovan_test_device_id_1",
        "hardwareId": null,
        "mobileOS": "android",
        "modelNumber": "MI 6",
        "modelVersion": "9.6.0",
        "appVersion": "1.0.0",
        "hardwareVersion": null,
        "followNum": false, // 关注数量
        "fansNum": false, // 粉丝数量
        "isFollow": false, // 是否关注
        "createdOn": "2018-08-03T16:05:43.000+0800",
        "updatedOn": "2018-08-09T21:04:59.000+0800"
    }
}
</code></pre>
