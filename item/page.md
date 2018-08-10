# Item page
---
# 请求类型: GET
# URL: https://jovanapi.top/items
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
                "id": 1,
                "itemName": "item 1", // 商品名称
                "itemCode": "test", // 商品代码
                "itemDesc": "jovan test", // 商品描述
                "price": 5, // 商品价格
                "icon": "test icon 1", // 商品图片
                "url": "test url", // 商品链接
                "createdOn": "2018-08-10T15:35:15.000+0800"
            }
        ],
        "pageNum": 1,
        "pageSize": 1,
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
