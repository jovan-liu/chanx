# Save BookRelative
---
# 请求类型: POST
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
        "userId": 1002, // 用户ID
        "bookId": 1, // 经文ID
        "chapter": "3", // 章节
        "progressPer": "30%" // 进度百分比
    }
}
</code></pre>
