# Get posts by categoryId
---
# 请求类型: GET
# URL: https://jovanapi.top/categories/{cid}/posts
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
        "total": 1,
        "list": [
            {
                "id": 1, // 帖子ID
                "categoryId": 1, // 分类ID
                "categoryName": "论道", // 分类名称
                "tagIds": "1,2", // 标签ID数组
                "tags": [ // 标签集合
                    {
                        "id": 1,
                        "name": "编辑精选",
                        "desc": null,
                        "createdOn": "2018-08-15T11:14:34.000+0800"
                    },
                    {
                        "id": 1,
                        "name": "编辑精选",
                        "desc": null,
                        "createdOn": "2018-08-15T11:14:34.000+0800"
                    }
                ],
                "title": "jovan test post 1", // 标题
                "content": "jovan test post content 1", // 内容
                "images": null, // 图片字符串，传到图片存储器后返回的值
                "thumbW": null, // 图片尺寸宽度
                "thumbH": null, // 图片尺寸高度
                "commentCount": 2, // 评论总数
                "points": 1, // 点赞数
                "isVote": false, // 当前用户是否点赞
                "isCollect": null, // 当前用户是否收藏
                "isRecommend": null, // 是否为推荐的帖子
                "createUserId": 1000, // 创建用户ID
                "createUserName": "无名氏", // 创建用户名
                "createdOn": "2018-08-03T16:06:48.000+0800" // 创建时间
            }
        ],
        "pageNum": 1,
        "pageSize": 4,
        "size": 1,
        "startRow": 1,
        "endRow": 1,
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
