# Push User Token
---
# 请求类型: POST
# URL: https://jovanapi.top/push/token
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
userId | 用户ID   | Long
mobileOS | 手机操作系统（例如：android, ios, windows phone..）  | String
token   | 设备令牌         | String
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "userId": 1000,
        "mobileOs": "android",
        "token": "testtoken111111111111",
        "createdOn": "2018-09-17T13:01:19.528+0800",
        "updatedOn": "2018-09-17T13:01:19.528+0800"
    }
}
</code></pre>
