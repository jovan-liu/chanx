# 获取经书列表
---
# 请求类型: GET
# URL: https://jovanapi.top/user/{uid}/books
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
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
        "bookIds": "1,2", // 经书ID
        "books": [ // 经书列表
            {
                "id": 1,
                "name": "金刚经",
                "author": "鸠摩罗什",
                "content": "内容。。。",
                "iconUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/jgj%403x.png",
                "normalName": "金刚经_白话版.txt",
                "normalUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/c223141e311570e99f05bd90d7ade325.txt",
                "ancientName": "金刚经_古译版.txt",
                "ancientUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/cc2bf4f751787df9e9a62857ac69059c.txt",
                "bookRelative": { // 经书相关
                    "userId": 1140,
                    "bookId": 1,
                    "chapter": "",
                    "progressPer": "",
                    "todayCount": 1,
                    "totalCount": 1,
                    "lastReadOn": "2018-12-13T16:17:16.000+0800"
                },
                "createdOn": "2018-08-28T17:54:27.000+0800"
            },
            {
                "id": 2,
                "name": "大悲咒",
                "author": "不空法师",
                "content": "内容。。。",
                "iconUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/dbz%403x.png",
                "normalName": "大悲咒_白话版.txt",
                "normalUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/9e0412417772b8c25c435aac9ff34f0a.txt",
                "ancientName": "大悲咒_古译版.txt",
                "ancientUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/31404a4bec9e238836711285beae0344.txt",
                "bookRelative": "",
                "createdOn": "2018-09-05T14:42:30.000+0800"
            }
        ],
        "level": 2, // 用户等级
        "levelName": "离垢", // 用户等级名称
        "exProgress": "0.00" // 经验进度
        "points": 3, // 用户积分
        "isSign": false, // 用户当日是否签到
        "userSign": { // 用户签到信息
            "id": 1,
            "userId": 1140,
            "count": 3, // 用户连续签到次数
            "maxCount": 3, // 用户最大连续签到次数
            "totalCount": 3, // 用户总签到次数
            "lastSignOn": "2018-12-13T14:29:27.000+0800", // 用户最后签到的时间
            "createdOn": "2018-12-13T14:22:30.000+0800"
        },
        "unlockedCount": 2,
        "createdOn": "2018-11-19T14:42:31.000+0800",
        "updatedOn": "2018-12-13T15:42:18.000+0800"
    }
}
</code></pre>
