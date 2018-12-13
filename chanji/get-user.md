# 获取用户信息
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
        "id": 1001,
        "userName": "# -- !#(@",
        "avatar": "",
        "avatarType": "",
        "signature": "# -- !#test",
        "authType": "",
        "deviceId": "jovan_test_device_id_2",
        "hardwareId": "",
        "mobileOS": "android",
        "modelNumber": "MI 8",
        "modelVersion": "9.6.1",
        "appVersion": "1.0.0",
        "hardwareVersion": "",
        "followNum": 0,
        "fansNum": 0,
        "isFollow": "",
        "bookIds": "1,2",
        "books": "",
        "level": 1,
        "levelName": "欢喜",
        "points": 1,
        "userSign": {
            "id": 4,
            "userId": 1001,
            "count": 1,
            "maxCount": 1,
            "totalCount": 1,
            "lastSignOn": "2018-12-13T15:10:16.000+0800",
            "createdOn": "2018-12-13T15:10:16.000+0800"
        },
        "createdOn": "2018-08-03T16:05:56.000+0800",
        "updatedOn": "2018-12-13T15:10:16.000+0800"
    }
}
</code></pre>
