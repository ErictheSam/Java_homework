1.程序的编译方法：
用android studio打开本zip中的项目代码目录，然后点击Build-Build APK来编译成apk文件，然后在手机上安装apk文件。支持安卓9.0版本的系统。

2.程序的使用方法：
程序分为两个权限，第一是游客模式，支持除了收藏之外的其它操作，当用户登录之后便进入用户模式，可以收藏文档并且进行同步。
程序共有三个主要页面，最左侧的页是新闻页，上拉刷新新闻下拉加载新闻，点击每一条新闻的标题可以进入浏览，点击下方的x可以指定新闻中一个或多个关键词作为屏蔽关键词。在本页面上向右划动出现一个新闻类别列表，点击列表可以选择不同的类别新闻。上方的菜单有三个按钮，最左侧的按钮是搜索，点开可以通过关键词搜索新闻，并保存历史关键词。中间的按钮是多类别新闻选择，拖动不同类别的新闻可以到“选中内容”区可以查看多个类别的新闻。右侧的菜单中包括切换日间/夜间模式和清空缓存两项。由于我们认为收藏是在缓存的基础上，在清空缓存的同时就会清空收藏。
点进新闻之后即时缓存，并进入正文查看页面。页面的上方菜单也有三个按钮，左边的按钮是分享，调用安卓的分享api;中间的按钮是收藏/取消收藏，分别在toast中显示当前操作的名称;右侧的菜单中包括切换日间/夜间模式和推荐新闻两项。点击“推荐新闻”可以通过关键词推荐新的一篇新闻并进入它的正文查看页面。推荐是可以递归执行的。
主页面中间的一页是收藏页，上拉刷新收藏下拉加载收藏，点击标题可以进入浏览。上方的菜单有两个按钮，其中左侧的按钮是清空收藏，右侧的按钮是切换日间/夜间模式。
主页面右侧的一页是用户页，在游客模式显示注册/登录页面，用户需填写用户名，密码和服务器IP来注册或者登录。在登录成功之后，进入用户模式，则显示用户界面，用户可以点击loggout按钮退出登录，此时将删除本机端的所有收藏。

3.一些注意事项:
因为服务器搭在组员的电脑上，所以请助教测试的时候添加一下微信:shenyibo413，从而知道服务器的确切ip地址，然后进行进一步的操作。
