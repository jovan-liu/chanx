# Register User
---
# 请求类型: POST
# URL: https://jovanapi.top/user/register
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
authType | 身份验证类型(例如：app, wechat)   | String
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
        "id": 1151,
        "userName": "无名氏",
        "avatar": "",
        "avatarType": "",
        "signature": "",
        "authType": "shadow",
        "deviceId": "testdeviceid77481543562167899",
        "hardwareId": "",
        "mobileOS": "iOS",
        "modelNumber": "iPhone X",
        "modelVersion": "11.4.1",
        "appVersion": "1.0.4",
        "hardwareVersion": "",
        "followNum": "",
        "fansNum": "",
        "isFollow": "",
        "bookIds": "", // 用户添加的经书ID， 格式： 1,2
        "books": "", // 经书列表
        "level": 1, // 用户等级
        "levelName": "欢喜", // 用户等级名称
        "points": 1, // 用户积分
        "userSign": { // 用户签到信息
            "id": 5,
            "userId": 1151,
            "count": 1, // 用户连续签到次数
            "maxCount": 1, // 用户最大连续敲到次数
            "totalCount": 1, // 用户总签到次数
            "lastSignOn": "2018-12-13T15:21:17.993+0800", // 用户最后签到的时间
            "createdOn": "2018-12-13T15:21:17.993+0800"
        },
        "createdOn": "2018-12-13T15:21:18.000+0800",
        "updatedOn": "2018-12-13T15:21:17.993+0800"
    }
}
</code></pre>
