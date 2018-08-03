# Save Comment
---
# 请求类型: POST
# URL: https://jovanapi.top/comments
# 请求头（headers）: Content-Type=application/x-www-form-urlencoded
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
postId | 帖子ID   | Long
content  | 内容        | String
fromUid | 评论人ID | Long
fromUserName | 评论人用户名 | String
toUid      | 被评论人用户ID （可选） | Long
toUserName | 被评论人用户名 （可选） | String
parentId   | 父评论ID （可选） | Long
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 3,
        "postId": 2,
        "parentId": null,
        "content": "jovan test comment 3 for post 2",
        "points": null,
        "isVote": false,
        "fromUid": 1001,
        "fromUserName": "无名氏",
        "toUid": null,
        "toUserName": null,
        "createdOn": "2018-08-03T16:51:27.282+0800"
    }
}
</code></pre>
