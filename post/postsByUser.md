# Get target user posts
---
# 请求类型: GET
# URL: https://jovanapi.top/user/{uid}/posts
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
                "id": 9,
                "categoryId": 3,
                "categoryName": "心路",
                "tagIds": null,
                "tags": null,
                "title": "我的佛法，我的正信",
                "content": "以前没接触佛教以前还觉得佛教是迷信，还觉得是骗老头老太太的，但是后来认识了一个信佛的朋友，平时闲聊之余也跟我讲些佛教智慧的一面，觉得可能自己对佛教的认识只停留在表面。\n在朋友的引导下自己也尝试着在现实生活中开始实践六波罗蜜，布施 持戒 忍辱 精进 禅定 智慧，也就是后来简化的戒定慧三学。说实话，渐渐的感觉自己的生活发生了很大的改善。\n我在现实生活里是个某鹅厂的前端，鹅厂压力很大，晋升也很困难。虽然工资相对其他行业更高一些但是说实话也更压抑。我只是一个普通家庭的孩子，在这个年代这让我内心过的非常痛苦。\n我不是个善于表达感情的人，也就是大家平时调侃的工科男吧。\n前段时间出现的程序员跳楼事件让我更加焦虑了。我不自觉地把自己代入了那个受害者，开始跟朋友唠叨。这么说起来那个时候也是我步入佛门的动机吧。\n实际上，正是因为佛教，我才知道之所以会觉得焦虑是因为对现实的贪执。\n大房子，美丽的妻子，跑车，奢侈品。现实社会的一切价值观都把你推往消费主义的深渊，把你的一切成功都捆绑在金钱上。只要有钱就牛逼，没钱的人就会被否定一切价值。也正是因为这样，我们真正步入了一个笑贫不笑娼的年代。\n实际上，每个人生来不同，我们只需要互相尊重就好。有的人会赚钱，有的人会唱歌，有的人会画画。而当我用佛陀的智慧暂且离开了消费主义的洪流时，回眼望来，一切正像金刚经所说的，一切有为法，如梦幻泡影，如露亦如电，应作如是观。\n感谢佛陀在2500年前带给人们的智慧，也感谢我的朋友告诉我这一切。今次发在禅迹论坛上也是朋友的邀请，无论大家是求财也好，求功德也好，求智慧也好希望大家都能在佛法中获得利益。",
                "images": null,
                "thumbW": null,
                "thumbH": null,
                "commentCount": 5,
                "points": 0,
                "isVote": false,
                "isFavorite": false,
                "isRecommend": null,
                "createUserId": 1006,
                "createUserName": "魅玩帮",
                "createUserAvatar": null,
                "createdOn": "2018-09-10T14:40:24.000+0800"
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
