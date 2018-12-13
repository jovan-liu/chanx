# 更新用户信息，主要是提供用户添加经书的ID
---
# 请求类型: PUT
# URL: https://jovanapi.top/user/update
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
id | 用户ID   | Long
userName | 用户名（可选）  | String
avatar   | 用户头像 (可选)         | String
avatarType   | 用户头像图片类型（例如：amazon, aliyun）        | String
signature   | 个性签名 (可选)         | String
bookIds   | 经书ID，使用逗号分隔（例如： 1,2） | String
# Tip: 更新用户头像时请传avatarType参数
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
        "bookIds": "1,2", // 经书ID
        "books": [ // 经书列表
            {
                "id": 1,
                "name": "金刚经",
                "author": "鸠摩罗什",
                "content": "内容。。。。",
                "iconUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/jgj%403x.png",
                "normalName": "金刚经_白话版.txt",
                "normalUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/c223141e311570e99f05bd90d7ade325.txt",
                "ancientName": "金刚经_古译版.txt",
                "ancientUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/cc2bf4f751787df9e9a62857ac69059c.txt",
                "createdOn": "2018-08-28T17:54:27.000+0800"
            },
            {
                "id": 2,
                "name": "大悲咒",
                "author": "不空法师",
                "content": "内容。。。。",
                "iconUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/dbz%403x.png",
                "normalName": "大悲咒_白话版.txt",
                "normalUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/9e0412417772b8c25c435aac9ff34f0a.txt",
                "ancientName": "大悲咒_古译版.txt",
                "ancientUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/31404a4bec9e238836711285beae0344.txt",
                "createdOn": "2018-09-05T14:42:30.000+0800"
            }
        ],
        "level": 2,
        "levelName": "离垢",
        "points": 3,
        "userSign": "",
        "createdOn": "2018-11-19T14:42:31.000+0800",
        "updatedOn": "2018-12-13T15:42:18.000+0800"
    }
}
</code></pre>
