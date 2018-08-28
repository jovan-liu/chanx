# Book page
---
# 请求类型: GET
# URL: https://jovanapi.top/books
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
                "id": 1, // 经文ID
                "name": "金刚经", // 经文名称
                "author": "鸠摩罗什", // 作者
                "iconUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/jgj%403x.png", // 封面图URL
                "normalUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/%E9%87%91%E5%88%9A%E7%BB%8F_%E7%99%BD%E8%A9%B1%E7%89%88.txt", // 白话版URL
                "ancientUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/%E9%87%91%E5%88%9A%E7%BB%8F_%E5%8F%A4%E8%AF%91%E7%89%88.txt", // 古译版URL
                "createdOn": "2018-08-28T17:54:27.000+0800" // 创建时间
            }
        ],
        "pageNum": 1,
        "pageSize": 2,
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
