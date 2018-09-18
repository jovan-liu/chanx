# User Notify page
---
# 请求类型: GET
# URL: https://jovanapi.top/usernotifies/{userId}
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
        "total": 1,
        "list": [
            {
                "id": 24, // ID
                "userId": 1007, // 当前用户ID
                "notifyId": 24, // 通知ID
                "isRead": false, // 是否已读
                "targetType": "Post", // 目标类型
                "targetId": 10, // 目标ID
                "targetCategoryId":1, // 目标分类ID（如果目标类型为Post或Comment,提供此参数进行分类判断）
                "targetCategoryName":"论道", // 目标分类名称
                "sender": 1001, // 通知触发者ID
                "senderName": "jovan.liu.2.test", // 通知触发者名称
                "content": "收藏了你在论道的言论", // 内容
                "createdOn": "2018-09-17T16:39:59.000+0800",
                "updatedOn": "2018-09-17T16:39:59.000+0800"
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
