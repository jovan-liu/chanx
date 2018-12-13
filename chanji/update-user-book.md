# 更新用户经书
---
# 请求类型: PUT
# URL: https://jovanapi.top/user/book/update
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId | 用户ID   | Long
bookId | 经书ID   | Long
type   | 类型，添加为1，删除为-1     | Integer
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 1140,
        "userName": "无名氏",
        "avatar": "",
        "avatarType": "",
        "signature": "",
        "authType": "wechat",
        "deviceId": "oFheP1kDazLe28du9pZA4-0JMv8I",
        "hardwareId": "",
        "mobileOS": "iOS",
        "modelNumber": "iPhone 7 Plus",
        "modelVersion": "10.0.1",
        "appVersion": "6.6.3",
        "hardwareVersion": "",
        "followNum": "",
        "fansNum": "",
        "isFollow": "",
        "bookIds": "2,3",
        "books": "",
        "level": 2,
        "levelName": "离垢",
        "points": 3,
        "userSign": "",
        "createdOn": "2018-11-19T14:42:31.000+0800",
        "updatedOn": "2018-12-13T21:01:54.645+0800"
    }
}
</code></pre>
