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
[更新用户信息](https://github.com/jovan-liu/chanx/blob/master/user/update.md)  
[获取用户信息](https://github.com/jovan-liu/chanx/blob/master/user/get.md)  
[上报用户设备token](https://github.com/jovan-liu/chanx/blob/master/user/pushToken.md)  

# 关注模块
[根据用户ID查询关注列表](https://github.com/jovan-liu/chanx/blob/master/fans/findFollow.md)  
[根据用户ID查询粉丝列表](https://github.com/jovan-liu/chanx/blob/master/fans/findFans.md)  
[添加关注](https://github.com/jovan-liu/chanx/blob/master/fans/addFollow.md)  
[取消关注](https://github.com/jovan-liu/chanx/blob/master/fans/deleteFollow.md)  

# 论坛模块
论坛由帖子（post）及评论（comment）两部分组成
# post
[查询精华帖子列表](https://github.com/jovan-liu/chanx/blob/master/post/recommendPosts.md)  
[根据分类ID获取分页帖子列表](https://github.com/jovan-liu/chanx/blob/master/post/postsByCategoryId.md)  
[根据ID获取帖子](https://github.com/jovan-liu/chanx/blob/master/post/get.md)  
[新增帖子](https://github.com/jovan-liu/chanx/blob/master/post/save.md)  
[修改帖子]()  （暂未提供该API）  
[删除帖子](https://github.com/jovan-liu/chanx/blob/master/post/delete.md)   
[根据目标用户ID获取帖子列表](https://github.com/jovan-liu/chanx/blob/master/post/postsByUser.md)   
[根据目标用户ID获取收藏帖子列表](https://github.com/jovan-liu/chanx/blob/master/post/collectionPosts.md)   
[根据用户ID获取帖子历史记录列表](https://github.com/jovan-liu/chanx/blob/master/post/postHistoryByPage.md)   

# comment
[根据帖子ID分页获取评论列表](https://github.com/jovan-liu/chanx/blob/master/comment/commentsByPostId.md)  
[根据ID获取评论](https://github.com/jovan-liu/chanx/blob/master/comment/get.md)  
[新增评论](https://github.com/jovan-liu/chanx/blob/master/comment/save.md)  
[修改评论]()  （暂未提供该API）  
[删除评论](https://github.com/jovan-liu/chanx/blob/master/comment/delete.md)    
[根据目标用户ID获取评论评论](https://github.com/jovan-liu/chanx/blob/master/comment/commentsByUser.md)    

# 点赞模块
[更改点赞状态](https://github.com/jovan-liu/chanx/blob/master/relative/changeVote.md)  

# 收藏模块
[更改收藏状态](https://github.com/jovan-liu/chanx/blob/master/relative/changeCollection.md)  

# 商品模块
[分页获取商品列表](https://github.com/jovan-liu/chanx/blob/master/item/page.md)   
[根据ID获取商品](https://github.com/jovan-liu/chanx/blob/master/item/get.md)    
[新增商品](https://github.com/jovan-liu/chanx/blob/master/item/save.md)    
[更新商品](https://github.com/jovan-liu/chanx/blob/master/item/update.md)    
[根据ID删除商品](https://github.com/jovan-liu/chanx/blob/master/item/delete.md)    

# 经文模块
[分页获取经文列表](https://github.com/jovan-liu/chanx/blob/master/book/page.md)   
[根据ID获取经文](https://github.com/jovan-liu/chanx/blob/master/book/get.md)    
[获取经文阅读精度](https://github.com/jovan-liu/chanx/blob/master/relative/getBookRelative.md)    
[添加经文阅读精度](https://github.com/jovan-liu/chanx/blob/master/relative/saveBookRelatives.md)    
[修改经文阅读精度](https://github.com/jovan-liu/chanx/blob/master/relative/updateBookRelative.md)(后台使用)    
[删除经文阅读精度](https://github.com/jovan-liu/chanx/blob/master/relative/deleteBookRelative.md)    

# 通知模块
[根据用户ID分页获取通知列表](https://github.com/jovan-liu/chanx/blob/master/userNotify/page.md)   
[阅读通知](https://github.com/jovan-liu/chanx/blob/master/userNotify/read.md)    
