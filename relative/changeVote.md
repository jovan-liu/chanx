# Change Post Vote 更改帖子点赞状态
---
# 请求类型: POST
# URL: https://jovanapi.top/posts/vote
# 请求头（headers）：Content-Type=application/x-www-form-urlencoded
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId | 用户ID   | Long
postId  | 帖子ID        | String
isVote   | true（点赞）/false （取消点赞）         | Boolean
# Tip: 评论点赞，只需将post换成comment就行，如https://jovanapi.top/comments/vote?userId=1000&commentId=1&isVote=true, 故不再另写API
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "userId": 1002,
        "postId": 1,
        "isVote": true
    }
}
</code></pre>
