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
        "isFavorite": false,
        "isRecommend": false,
        "createUserId": 1000,
        "createUserName": "无名氏",
        "createdOn": "2018-08-03T16:06:48.000+0800"
    }
}
</code></pre>
