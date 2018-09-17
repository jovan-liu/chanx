# Update User Notify
---
# 请求类型: PUT
# URL: https://jovanapi.top/usernotifies/read
# 参数:
参数名 | 说明    | 类型
----- |-------- | ----
id | 用户消息ID  | Long
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "id": 3,
        "userId": 1000,
        "notifyId": 4,
        "isRead": true,
        "createdOn": "2018-09-17T13:45:19.000+0800",
        "updatedOn": "2018-09-17T13:45:31.574+0800"
    }
}
</code></pre>
