---
layout: post
title: "Mideosource"
date: 2015-01-06 17:55
categories: Html5
---

### MideoSource ###
- video
- MediaSource
- createObjectURL
- addSourceBuffer
- appendBuffer
- video->play

----

1. 在页面的 HTML 部分中定义 HTML5 video 元素。
2. 使用 JavaScript 创建 MediaSource 对象。
3. 使用 createObjectURL 创建虚拟 URL，并将 MediaSource 对象作为源。
4. 将虚拟 URL 分配到视频元素的 src 属性。
5. 使用 addSourceBuffer 创建 SourceBuffer，包含你添加的 MIME 类型的视频。
6. 从媒体文件联机获取视频初始化分段，并使用 appendBuffer 将其添加到 SourceBuffer 中。
7. 从媒体文件获取视频数据的分段，并使用 appendBuffer 将其附加到 SourceBuffer 中。
8. 在 video 元素上调用 play 方法。
9. 重复步骤 7 直到完成。