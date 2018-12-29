# 获取卡片列表
---
# 请求类型: GET
# URL: https://jovanapi.top/user/{uid}/cards
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
        "signature": "小米",
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
        "bookIds": "2",
        "books": "",
        "level": 1,
        "levelName": "欢喜地",
        "levelDesc": "由发闻行。\r\n正法光明等持光明之所显示。\r\n是故此地名发光地。", // 等级描述
        "exProgress": 0.5,
        "points": 2,
        "isSign": "",
        "userSign": "",
        "unlockedCount": 3, // 下次解锁所需天数
        "cards": [ // 卡片列表
            {
                "id": 1,
                "name": "缘起1", // 卡片名称
                "desc": "一切有为法皆为缘起1", // 卡片描述
                "iconUrl": "https://chanji.oss-cn-shenzhen.aliyuncs.com/test-image/card.png", // 卡片封面
                "signCount": 2, // 获取该卡片所需签到数
                "createdOn": "2018-12-29T10:52:48.000+0800",
                "updatedOn": "2018-12-29T10:52:48.000+0800"
            }
        ],
        "createdOn": "2018-11-19T14:42:31.000+0800",
        "updatedOn": "2018-12-29T13:32:31.000+0800"
    }
}
</code></pre>
