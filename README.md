# myRss

### Rss订阅源获取

1. 使用[rsshub](https://docs.rsshub.app/)

   1. twitter用户时间线
      [支持浏览器扩展](https://github.com/DIYgod/RSSHub-Radar) [支持 RSSBud](https://github.com/Cay-Zhang/RSSBud)

      作者: [@DIYgod ](https://github.com/DIYgod)[@yindaheng98 ](https://github.com/yindaheng98)[@Rongronggg9](https://github.com/Rongronggg9)

      举例: https://rsshub.app/twitter/user/DIYgod

      路由: `/twitter/user/:id/:routeParams?`

      参数:

      1. `id`, 必选 - 用户名；特别地，以 `+` 开头则代表[唯一 ID](https://github.com/DIYgod/RSSHub/issues/12221)，如 `+44196397`
      2. `routeParams`, 可选 - 额外参数；请参阅上面的说明和表格；特别地，当 `routeParams=exclude_replies`时去除回复，`routeParams=exclude_rts`去除转推，`routeParams=exclude_rts_replies`去除回复和转推，默认包含全部回复和转推。

   2. 微博时间线

      1. ```
         https://rsshub.app/weibo/user/(uid)/readable=1&authorNameBold=1&showAuthorInTitle=1&showAuthorInDesc=1&showAuthorAvatarInDesc=1&showEmojiForRetweet=1&showRetweetTextInTitle=0&addLinkForPics=1&showTimestampInDescription=1&showTimestampInDescription=1&heightOfPics=150
         ```

2. 博客主页rss

### Rss阅读器

1. Windows: [quiteRss](https://quiterss.org/)
2. ios: reeder
3. Android: [read you](https://github.com/Ashinch/ReadYou)