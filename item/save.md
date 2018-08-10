# Save Item
---
# 请求类型: POST
# URL: https://jovanapi.top/items
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
itemName | 商品名称   | String
itemCode  | 商品代码  | String
itemDesc  | 商品描述  | String
price    |  商品价格  | double
icon     | 商品图片   | String
url      | 商品链接   | String
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 1,
        "itemName": "item 1",
        "itemCode": "test",
        "itemDesc": "jovan test",
        "price": 5,
        "icon": "test icon",
        "url": "test url",
        "createdOn": "2018-08-10T15:35:15.361+0800"
    }
}
</code></pre>
