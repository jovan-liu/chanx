# Save Post
---
# 请求类型: POST
# URL: https://jovanapi.top/posts
# 请求头（headers）：Content-Type=application/x-www-form-urlencoded
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
categoryId | 分类ID（1：论道、 2：读经、 3：心路）   | Integer
title   | 标题          | String
content | 内容  | String
images  | 图片链接 (可选) | String
createUserId | 创建人ID | Long
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 4,
        "categoryId": 1,
        "categoryName": "论道",
        "title": "jovan test post 4",
        "content": "jovan test post content 4",
        "images": null,
        "commentCount": null,
        "points": null,
        "isVote": false,
        "isFavorite": false,
        "isRecommend": false,
        "createUserId": 1000,
        "createUserName": "无名氏",
        "createdOn": "2018-08-03T16:39:55.635+0800"
    }
}
</code></pre>
