# 基于Vue.js的音乐播放器

#### 视图

* 推荐页
* 排行榜
  * 排行榜详情
* 歌手页                                                -->  最终都指向播放音乐界面  滚动歌词
  * 歌手详情
* 搜索页 
* 收藏和历史记录

#### 技术栈 /库

Vue + Vuex + Vue-Router + Vue-cli + better-scroll + Axios + SCSS + vue-lazyload

比较重要的点在于播放音乐列表的数据设计，其他组件的操作都会影响播放状态，所以音乐播放界面改变状态的都是由vuex来管理。

#### 数据请求

API接口用的是[NeteaseCloudMusicApi](https://binaryify.github.io/NeteaseCloudMusicApi/#/?id=neteasecloudmusicapi)

效果图：![](https://s1.ax1x.com/2018/12/09/F8WWCD.gif)




