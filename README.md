# 禅行APP API

---

# 请求API返回code说明
GET  ->  200  
POST/PUT ->  201  
DELETE  ->   204   
ERROR   ->   500 or other  
Not Found  ->  404  

# 用户模块
[用户注册](https://github.com/jovan-liu/chanx/blob/master/user/register.md)  

# 论坛模块
论坛由帖子（post）及评论（comment）两部分组成
# post
[查询精华帖子列表](https://github.com/jovan-liu/chanx/blob/master/post/recommendPosts.md)  
[根据分类ID获取分页帖子列表](https://github.com/jovan-liu/chanx/blob/master/post/postsByCategoryId.md)  
[根据ID获取帖子](https://github.com/jovan-liu/chanx/blob/master/post/get.md)  
[新增帖子](https://github.com/jovan-liu/chanx/blob/master/post/save.md)  
[修改帖子]()  （暂未提供该API）  
[删除帖子]()  （暂未提供该API）  

# comment
[根据帖子ID分页获取评论列表](https://github.com/jovan-liu/chanx/blob/master/comment/commentsByPostId.md)  
[根据ID获取评论](https://github.com/jovan-liu/chanx/blob/master/comment/get.md)  
[新增评论](https://github.com/jovan-liu/chanx/blob/master/comment/save.md)  
[修改评论]()  （暂未提供该API）  
[删除评论]()  （暂未提供该API）  

# 点赞模块
[更改点赞状态](https://github.com/jovan-liu/chanx/blob/master/relative/changeVote.md)  

# 商品模块
[分页获取商品列表](https://github.com/jovan-liu/post_system/blob/master/item/page.md)  （暂未提供该API）  
[根据ID获取商品](https://github.com/jovan-liu/post_system/blob/master/item/get.md)  （暂未提供该API）  
[根据ID删除商品](https://github.com/jovan-liu/post_system/blob/master/item/delete.md)  （暂未提供该API）  
