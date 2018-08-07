# Save Comment
---
# 请求类型: POST
# URL: https://jovanapi.top/comments
# 请求头（headers）: Content-Type=application/x-www-form-urlencoded
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
postId | 帖子ID   | Long
commentType  | 评论类型：Post Comment        | String
content  | 内容        | String
fromUid | 评论人ID | Long
toUid      | 被评论人用户ID （可选） | Long
parentId   | 父评论ID （可选） | Long
# Tip: 若评论类型为Comment时，parentId为必传，且值必须为已有的评论ID
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 3,
        "postId": 2,
        "parentId": null,
        "commentType": "Post",
        "content": "jovan test comment 3 for post 2",
        "points": null,
        "isVote": false,
        "fromUid": 1001,
        "fromUserName": "无名氏",
        "toUid": 1000,
        "toUserName": "无名氏",
        "createdOn": "2018-08-03T16:51:27.282+0800"
    }
}
</code></pre>
