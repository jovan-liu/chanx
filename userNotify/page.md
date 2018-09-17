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
        "total": 3,
        "list": [
            {
                "id": 3,
                "userId": 1000,
                "notifyId": 4,
                "isRead": true,
                "createdOn": "2018-09-17T13:45:19.000+0800",
                "updatedOn": "2018-09-17T13:45:32.000+0800"
            },
            {
                "id": 2,
                "userId": 1000,
                "notifyId": 3,
                "isRead": true,
                "createdOn": "2018-09-17T13:44:06.000+0800",
                "updatedOn": "2018-09-17T13:44:26.000+0800"
            },
            {
                "id": 1,
                "userId": 1000,
                "notifyId": 2,
                "isRead": true,
                "createdOn": "2018-09-17T13:39:31.000+0800",
                "updatedOn": "2018-09-17T13:42:45.000+0800"
            }
        ],
        "pageNum": 1,
        "pageSize": 4,
        "size": 3,
        "startRow": 1,
        "endRow": 3,
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
        "lastPage": 1,
        "firstPage": 1
    }
}
</code></pre>
