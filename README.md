# 移动端全屏播放视频

兼容安卓和 ios

## Usage

```js
import fullPageVideo from 'vue-full-page-video';
import vue from 'vue';
vue.use(fullPageVideo);
const VideoSrc = 'xxx.mp4';
const fullPageVideoInstance = this.$fullPageVideo.play(VideoSrc);
```

## Methods

| 方法名 | 参数 | 说明         |
| ------ | ---- | ------------ |
| play   | -    | 播放视频     |
| pause  | -    | 暂停视频视频 |
| hide   | -    | 隐藏         |

## Events

| 事件名  | 回调参数 | 说明 |
| ------- | -------- | ---- |
| playing | -        |      |
| pause   | -        |      |
| ended   | -        |      |
| hide    | -        |      |
