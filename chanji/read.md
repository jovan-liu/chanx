# 用户阅读经书
---
# 请求类型: POST
# URL: https://jovanapi.top/book/read
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId  | 用户ID   | Long
bookId  | 经文ID  | Long
todayCount  | 今日阅读数（可选） | Integer
isSign  | 用户是否签到 | Boolean
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "bookRelative": {
            "userId": 1001,
            "bookId": 1,
            "chapter": "",
            "progressPer": "",
            "todayCount": 3, // 今日阅读次数
            "totalCount": 5, // 总阅读次数
            "lastReadOn": "2018-12-13T15:48:28.123+0800" // 最后阅读的时间
        },
        isSign: true
        
    }
}
</code></pre>
