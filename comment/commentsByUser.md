# Get target user comments
---
# 请求类型: GET
# URL: https://jovanapi.top/user/{uid}/comments
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
pageNum | 第几页   | Integer
pageSize  | 一页多少        | Integer
userId   | 用户ID（可选） | Long
# 返回值:
<pre><code>
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": {
        "total": 1,
        "list": [
            {
                "id": 5,
                "postId": 9,
                "postTitle": "我的佛法，我的正信",
                "parentId": null,
                "commentType": "Post",
                "content": "“现实社会的一切价值观都把你推往消费主义的深渊，把你的一切成功都捆绑在金钱上。只要有钱就牛逼，没钱的人就会被否定一切价值。也正是因为这样，我们真正步入了一个笑贫不笑娼的年代。”双手赞同呀！！",
                "points": 0,
                "isVote": false,
                "fromUid": 1016,
                "fromUserName": "卡菌",
                "fromUserAvatar": null,
                "fromUserSignature": null,
                "toUid": 1006,
                "toUserName": "魅玩帮",
                "createdOn": "2018-09-10T15:11:14.000+0800"
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
