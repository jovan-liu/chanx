# Get comments by postId
---
# 请求类型: GET
# URL: https://jovanapi.top/posts/{pid}/comments
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
pageNum | 第几页   | Integer
pageSize  | 一页多少        | Integer
userId   | 用户ID（可选） | Long
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "total": 2,
        "list": [
            {
                "id": 1, // 评论ID
                "postId": 1, // 帖子ID
                "parentId": null, // 父评论ID
                "commentType": "Post", // 评论类型
                "content": "jovan test comment 1 for post 1", // 内容
                "points": 2, // 点赞数
                "isVote": true, // 当前用户是否点赞
                "fromUid": 1001, // 评论用户ID
                "fromUserName": "无名氏", // 评论用户名
                "toUid": 1000, // 被评论用户ID
                "toUserName": "无名氏", // 被评论用户名
                "createdOn": "2018-08-03T16:08:20.000+0800" // 创建时间
            },
            {
                "id": 2,
                "postId": 1,
                "parentId": 1,
                "commentType": "Comment",
                "content": "jovan test comment 2 for post 1",
                "points": 0,
                "isVote": false,
                "fromUid": 1000,
                "fromUserName": "无名氏",
                "toUid": 1001,
                "toUserName": "无名氏",
                "createdOn": "2018-08-03T16:09:08.000+0800"
            }
        ],
        "pageNum": 1,
        "pageSize": 2,
        "size": 2,
        "startRow": 1,
        "endRow": 2,
        "pages": 1,
        "prePage": 0,
        "nextPage": 0,
        "isFirstPage": true,
        "isLastPage": true,
        "hasPreviousPage": false,
        "hasNextPage": false,
        "navigatePages": 8,
        "navigatepageNums": [
            1
        ],
        "navigateFirstPage": 1,
        "navigateLastPage": 1,
        "firstPage": 1,
        "lastPage": 1
    }
}
</code></pre>
