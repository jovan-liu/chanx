# Update BookRelative
---
# 请求类型: PUT
# URL: https://jovanapi.top/bookrelatives
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId  | 用户ID   | Long
bookId  | 经文ID  | Long
chapter | 章节    | String
progressPer  | 进度百分比  | String
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "userId": 1002,
        "bookId": 1,
        "chapter": "4",
        "progressPer": "40%"
    }
}
</code></pre>
