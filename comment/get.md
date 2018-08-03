# Get Comment
---
# 请求类型: Get
# URL: https://jovanapi.top/comments/{id}
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId   | 用户ID（可选） | Long
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "id": 1,
        "postId": 1,
        "parentId": null,
        "content": "jovan test comment 1 for post 1",
        "points": 2,
        "isVote": false,
        "fromUid": 1001,
        "fromUserName": "无名氏",
        "toUid": null,
        "toUserName": null,
        "createdOn": "2018-08-03T16:08:20.000+0800"
    }
}
</code></pre>
