# auto-delete-weibo

自动批量删除微博

# 使用方法

1. 安装此 [UserScript](https://greasyfork.org/scripts/396380-auto-delete-weibo/code/Auto%20delete%20weibo.user.js)，如果不知道`UserScript`是什么就算了别往下看了
1. 启用此脚本
1. 打开微博个人主页 比如 `https://weibo.com/p/1005051111681197/home` 可以通过点击主页的累计微博数字获得此链接
1. **在URL末尾加上`?is_all=1&delete=yes`** 也就是变成 `https://weibo.com/p/1005051111681197/home?is_all=1&delete=yes`
1. 开着浏览器等删除干净。为了避免操作频繁，使用模拟点击实现，且间隔较慢，需要耐心等待。

# LICENSE
WTFPL
