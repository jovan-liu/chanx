# Get user fans 查询用户粉丝列表
---
# 请求类型: GET
# URL: https://jovanapi.top/user/{followUserId}/fans/fans
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
pageNum   | 第几页         | Integer
pageSize  | 一页多少         | Integer
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "total": 2,
        "list": [ // 粉丝列表
            {
                "fansUserId": 1001, // 粉丝用户ID
                "followUserId": 1000, // 当前用户ID
                "groupId": -1,
                "isFollow": "",
                "createdOn": "2018-09-12T15:01:13.000+0800"
            },
            {
                "fansUserId": 1002,
                "followUserId": 1000,
                "groupId": -1,
                "isFollow": "",
                "createdOn": "2018-09-12T15:01:20.000+0800"
            }
        ],
        "pageNum": 1,
        "pageSize": 4,
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
