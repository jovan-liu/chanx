# 搜索经书
---
# 请求类型: GET
# URL: https://jovanapi.top/books/search
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
name  | 经书名称   | String
# Tip: 可模糊查询，例如搜索“金刚”，可以查到《金刚经》
# 返回值:
{
    "code": 200,
    "msg": "Get resources successfully",
    "data": [
        {
            "id": 1,
            "name": "金刚经",
            "author": "鸠摩罗什",
            "content": "<div >\r\n\t<font color=\"gray\" size=\"1\">&nbsp;ná&nbsp;&nbsp;mó&nbsp;·&nbsp;hé&nbsp;&nbsp;là&nbsp;&nbsp;dá&nbsp;&nbsp;nā&nbsp;·&nbsp;duō&nbsp;&nbsp;là&nbsp;&nbsp;yà&nbsp;&nbsp;yē。</font>\r\n\t<br>\r\n\t<font color=\"black\" size=\"4\" style=\"letter-spacing: 1px;\">南无·喝啰怛那·哆啰夜耶。</font>\r\n</div>",
            "iconUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/jgj%403x.png",
            "normalName": "金刚经_白话版.txt",
            "normalUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/c223141e311570e99f05bd90d7ade325.txt",
            "ancientName": "金刚经_古译版.txt",
            "ancientUrl": "https://s3-us-west-2.amazonaws.com/test-chanx-image/book/cc2bf4f751787df9e9a62857ac69059c.txt",
            "createdOn": "2018-08-28T17:54:27.000+0800"
        }
    ]
}
</code></pre>
