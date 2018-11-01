# d_blog
基于django的小型博客网站
目前功能只有:
    1.用户登录注册
    2.邮箱验证激活（为方便测试，新注册用户默认为激活状态，若想设置为必须邮箱激活，可设置is_active字段为False）
    3.发表博客
    4.用户博客管理（按标题查询，修改，查看，删除）
    5.用户上传头像，修改个人信息
    6.首页展示所有用户发表的博客
    7.用户收藏博客
    8.查看我的收藏并管理（按标题查询，查看博客详情，者取消收藏）
    9.首页搜索关键字查询标题或者内容包含该关键字的博客
    注：博客的评论与回复功能和已有账户未激活功能还未添加，所以网站内容有点简单。