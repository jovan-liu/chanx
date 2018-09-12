# Add follow 添加关注
---
# 请求类型: POST
# URL: https://jovanapi.top/user/follow
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
fansUserId | 当前用户ID   | Long
followUserId   | 关注用户ID         | Long
groupId  | 关注分组ID（可选，默认值为-1）   | Long
# Tip: 为了方便扩展关注的分组，预先设置了groupId参数，当前默认值为-1，若要填写也请填-1
# 返回值:
<pre><code>
{
    "code": 201,
    "msg": "Post or put resources successfully",
    "data": {
        "fansUserId": 1002,
        "followUserId": 1001,
        "groupId": -1,
        "createdOn": "2018-09-12T15:50:52.694+0800"
    }
}
</code></pre>
