---
layout: post
title: "File Api"
date: 2015-03-30 20:33
categories: File
---

###在Web中使用文件
- input
`<input type="file" multiple>`
document.querySelector('input[type=="file"]).files[n]
>- name **文件名,只读字符串,不包含任何路径信息.**
>- size **文件大小,单位为字节,只读的64位整数.**
>- type **MIME类型,只读字符串,如果类型未知,则返回空字符串.**
- 拖拽


####FileReader####
>异步的读取存储在用户计算机上的文件(或者原始数据缓冲)内容,可以使用File对象或者Blob对象来指定所要处理的文件或数据.

####createObjectURL####
>使用对象URL来显示图片