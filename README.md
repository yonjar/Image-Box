# Image-Box

一个简单的、基于jQuery的图片灯箱JS插件。
其实本来只是想写给博客用的，因为 Material Design Lite 没有图片灯箱效果，就手动撸了一个简单的比较初级的，类似Materialize的灯箱效果那样的JS插件出来。
遵循Apache Public Lincense开源。

# 使用方法：
1.在 header 引入 jQuery，ImageBox.css，ImageBox.js：
```
<link rel="stylesheet" type="text/css" href="ImageBox.css">
<script src="jquery.min.js"></script>
<script src="ImageBox.js"></script>
```

2.为需要使用灯箱效果的图片添加"ImageBox"的Class：
```
<img src="233.jpg" class="ImageBox">
```
如果一个DIV层中有很多图片，可以使用jQuery代码批量添加“ImageBox”的Class：
```
<script>
$("div img").addClass("ImageBox");
</script>
```
