# 用户签到
---
# 请求类型: POST
# URL: https://jovanapi.top/user/read
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId  | 用户ID   | Long
# 返回值:

{
    "code": 201,
    "msg": "The user is first sign in",
    "data": {
        "id": 1002,
        "userName": "无名氏",
        "avatar": "",
        "avatarType": "",
        "signature": "",
        "authType": "",
        "deviceId": "jovan_test_device_id_3",
        "hardwareId": "",
        "mobileOS": "ios",
        "modelNumber": "iPhone 7",
        "modelVersion": "10.0.0",
        "appVersion": "1.0.0",
        "hardwareVersion": "",
        "followNum": "",
        "fansNum": "",
        "isFollow": "",
        "bookIds": "",
        "books": "",
        "level": 1,
        "levelName": "欢喜",
        "points": 1,
        "userSign": {
            "id": 6,
            "userId": 1002,
            "count": 1,
            "maxCount": 1,
            "totalCount": 1,
            "lastSignOn": "2018-12-13T15:32:43.556+0800",
            "createdOn": "2018-12-13T15:32:43.556+0800"
        },
        "createdOn": "2018-08-03T16:23:46.000+0800",
        "updatedOn": "2018-12-13T15:32:43.556+0800"
    }
}
