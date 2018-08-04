# Get recommend posts
---
# 请求类型: GET
# URL: https://jovanapi.top/posts/recommend
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
		"list": [{
			"id": 1,
			"categoryId": 1,
			"categoryName": "论道",
			"title": "jovan test post 1",
			"content": "jovan test post content 1",
			"images": null,
			"commentCount": 2,
			"points": 2,
			"isVote": false,
			"isFavorite": false,
			"isRecommend": true,
			"createUserId": 1000,
			"createUserName": "无名氏",
			"createdOn": "2018-08-03T16:06:48.000+0800"
		}],
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
		"navigatepageNums": [1],
		"navigateFirstPage": 1,
		"navigateLastPage": 1,
		"firstPage": 1,
		"lastPage": 1
	}
}
</code></pre>
