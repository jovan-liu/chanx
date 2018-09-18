# Get target user posts
---
# 请求类型: GET
# URL: https://jovanapi.top/user/{uid}/posts/history
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
pageNum | 第几页   | Integer
pageSize  | 一页多少        | Integer
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "total": 2,
        "list": [
            {
                "id": 1,
                "userId": 1000, // 用户ID
                "postId": 2, // 帖子ID
                "type": 1, // 历史记录类型，1：浏览帖子，2：帖子点赞
                "postCategoryId": 1, // 帖子分类ID
                "postCategoryName": "论道", / 帖子分类名称
                "postCreateUserId": 1000, // 创建帖子用户ID
                "postCreateUserName": "管理员", // 创建帖子用户名称
                "postCreateUserAvatar": "test3", // 创建帖子用户头像
                "createdOn": "2018-09-18T11:29:19.000+0800",
                "updatedOn": "2018-09-18T11:35:11.000+0800"
            },
            {
                "id": 2,
                "userId": 1000,
                "postId": 3,
                "type": 1,
                "postCategoryId": 1,
                "postCategoryName": "论道",
                "postCreateUserId": 1000,
                "postCreateUserName": "管理员",
                "postCreateUserAvatar": "test3",
                "createdOn": "2018-09-18T11:29:39.000+0800",
                "updatedOn": "2018-09-18T11:29:39.000+0800"
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
