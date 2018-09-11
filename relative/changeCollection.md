# Change Post Collection 更改帖子收藏状态
---
# 请求类型: POST
# URL: https://jovanapi.top/posts/collection
# 请求头（headers）：Content-Type=application/x-www-form-urlencoded
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId | 用户ID   | Long
postId  | 帖子ID        | String
isCollect   | true（收藏）/false （取消收藏）         | Boolean
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "userId": 1001,
        "postId": 9,
        "isCollect": true
    }
}
</code></pre>
