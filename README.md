# Movie Robot 产品手册
用户社区Discord：https://discord.gg/SMauZCXgKx
这里有最全面的产品动态，实时问答，玩法分享，体验激活申请区

TG Channel：https://t.me/aimovierobot 适合单项接收一些信息

[Movie Robot WIki](https://yee329.notion.site/Movie-Robot-Wiki-9abef8c648c840fca47a0bf308957f85)

**新人指南系列**
* 1.[检查清单](https://www.notion.so/yee329/1-d8479e45ecbd4ed487726f86ddcfc3fd)
* 2.[Docker应用启动与升级](https://yee329.notion.site/2-Docker-09e1db16b2b14040840bd2f5660e666c)
* 3.[通过网页完成首次初始化](https://yee329.notion.site/3-42680818afd84891b254bfa456f3dd3e)
* 4.[资源站点设置与养护](https://yee329.notion.site/4-28702cf23a834c2380eb8ff34de68ea5)
* 5.[设置智能下载开启全自动观影](https://yee329.notion.site/5-745da2776daa4fc7b5e2ddb3170aa11a)
* 6.[使用微信接收通知&搜索订阅](https://yee329.notion.site/45883b2da80c4d7b87c979ad77097a95)
* 7.[玩转过滤器与排序规则](https://yee329.notion.site/12f6d44243194c8c96a7e000b9dde023)

完整WIKI地址：https://yee329.notion.site/Movie-Robot-Wiki-9abef8c648c840fca47a0bf308957f85

# 产品大图
<img alt="产品大图" src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/Movie Robot.jpg"/>

**免责声明：本产品不提供任何影片资源，不与任何内容提供方有直接合作，所有内容均来自安装者自己配置的内容站点。配置后，本产品会利用爬虫技术以合法合理的频次，访问内容站点拉取资源。**

## Movie Robot是什么？
* “聪明”的自动化调度工具
  * 影视发现与查找，多种渠道均支持多用户体系，可以让家人、朋友，通过任意渠道订阅
    * 豆瓣APP、豆瓣小程序想看
    * 通过微信搜索与订阅
    * 通过私有化媒体发现服务提交订阅
  * 订阅追新与洗版
    * 在配置好的站点中，定时或实时，准确无误的找到订阅中想看，且符合所需品质的资源
    * 出现更好品质值得收藏的资源时，自动完成下载、替换（删除原有）
  * 影视文件识别与整理，网络下载好的电影或剧集，都是杂乱的名称文件或文件夹，程序会自动将这些文件，识别成标准的名称、发行年份，并整理到指定目录。
  * 中文字幕自动下载，影片通过下载器完成后，本程序会自动启动中文字幕搜索任务，帮助你去字幕网站查找中文字幕，下载好后存储媒体服务器所需路径
* 完全私有化产品，不依赖任何云上数据和算子
  * 不共享任何内容和数据
  * 全部媒体元数据，和媒体资源，均来自第三方网站

# 使用须知
**本软件需付费购买激活码后可以使用，[付费方式&价格&权益介绍](https://yee329.notion.site/b712e719e79b47f58ff374737609d3be)**

# Docker官方镜像
https://registry.hub.docker.com/r/yipengfei/movie-robot/

# 前端源代码
https://github.com/pofey/movie-robot-frontend

# 主程序可开源的源码
程序中核心实现（事件处理、插件引擎），工具类，以及做插件开发时可能需要用到的内部实现全部开源，和主程序代码完全同步。为了插件开发者引用方便，代码独立到插件开发调试项目内。
https://github.com/pofey/movie-bot-dev

# 功能预览
## WebUI
### PC端：
<img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/sublist.jpg" width="926" height="551"/>
<img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/download_dashboard.jpg" width="926" height="551"/>
<img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/site_dashboard.jpg" width="926" height="551"/>
<img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/plugin_market.jpg" width="926" height="551"/>

### 移动端：
<img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/webui-search.jpg" width="300" height="650"/><img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/webui-downloading-dark.jpg" width="300" height="650"/>
<img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/search-ww.jpg" width="300" height="650"/><img src="https://raw.githubusercontent.com/pofey/movie_robot/main/doc/images/webui-downloading.jpg" width="300" height="650"/>
