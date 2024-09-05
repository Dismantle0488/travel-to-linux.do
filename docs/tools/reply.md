# 回复增强

## 文件

- [屋舍](https://www.uhsea.com/)

## 插入音频

```html
<audio controls autoplay>
  <source src="粘贴链接到这里" type="audio/mp4">
</audio>
```

## 插入视频

```html
<div class="video-container">
    <video controls>
        <source src="视频文件链接.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
```

## 插入哔哩视频

```html
<iframe
src="//player.bilibili.com/player.html?bvid=BV1fx411N7bU&p=1&poster=1&danmaku=0&autoplay=0"
scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true">
</iframe>
```

aid 与 bvid 二选一即可

| 参数名   | 说明         | 用法                                  |
| -------- | ------------ | ------------------------------------- |
| aid      | 视频 ID      | aid=1234567                           |
| bvid     | 视频 ID      | bvid=BV1fx411N7bU                     |
| p        | 合集序号     | p=1                                   |
| poster   | 海报开关     | poster=1 （开） / poster=0 （关）     |
| danmaku  | 字幕开关     | danmaku=1 （开） / danmaku=0 （关）   |
| autoplay | 自动播放开关 | autoplay=1 （开） / autoplay=0 （关） |
| muted    | 静音开关     | muted=1（开） / muted=0（关）         |
