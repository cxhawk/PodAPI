# PodAPI

播客2.0通过标准化时间轴信息让长音频内容更加吸引人

时间轴信息带来了更丰富的播客收听体验
包括但不止以下几点:

- 章节
这些时间点可以方便听众在长音频中找到感兴趣的地方

- 关键时间
用图片等其他形式表达无法用声音说明白的问题

- 精华片段
定位高光时刻，把长音频变成短音频

- 音乐
标注出节目中播放的音乐片段

# Spec
只需要在RSS中引入一个外部文件

`<podapi:metadata href='https://host.podapi.xyz/shapodcast/metadata.json5' type='application/json5'/>`
