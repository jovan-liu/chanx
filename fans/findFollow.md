# Get user follow 查询用户关注列表
---
# 请求类型: GET
# URL: https://jovanapi.top/user/{fansUserId}/fans/follow
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
fansUserId | 用户ID   | Long
groupId  | 关注分组ID（可选，默认值为-1）        | Long
pageNum   | 第几页         | Integer
pageSize  | 一页多少         | Integer
# Tip: 为了方便扩展关注的分组，预先设置了groupId参数，当前默认值为-1，若要填写也请填-1
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "total": 1,
        "list": [ // 关注列表
            {
                "fansUserId": 1001, // 用户ID
                "followUserId": 1000, // 关注用户ID
                "groupId": -1, // 关注分组ID
                "createdOn": "2018-09-12T15:01:13.000+0800" // 创建时间
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
