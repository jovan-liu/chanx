# Get Post
---
# 请求类型: GET
# URL: https://jovanapi.top/posts/{id}
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId   | 用户ID (可选) | Long
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "id": 1,
        "categoryId": 1,
        "categoryName": "论道",
        "title": "jovan test post 1",
        "content": "jovan test post content 1",
        "images": null,
        "commentCount": 2,
        "points": 1,
        "isVote": false,
        "isCollect": true, // 当前用户是否收藏此帖子
        "isRecommend": false,
        "isFollow": false, // 当前用户是否关注该帖子用户
        "createUserId": 1000,
        "createUserName": "无名氏",
        "createUserAvatar": "avatar.png", // 创建帖子用户头像
        "createUserSignature": "Signature A", // 创建帖子用户个性签名
        "createdOn": "2018-08-03T16:06:48.000+0800"
    }
}
</code></pre>
