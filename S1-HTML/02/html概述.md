# html概述

###  HTML 基本结构与属性

- HTML ：超文本 标记 语言

- 超文本 ： 文本内容 + 非文本内容 （图片 / 视频 / 音频 等）
- 标记 ： 标签，<单词>
  - 单标签
  - 双标签
  - 创建标签的快捷键 ：单词输入 + <kbd>tab</kbd>
  - 标签的属性
- 语言 ： 编程语言



### HTML初始代码

在vscode中的生成快捷键 : `!` + <kbd>tab</kbd>

```html
<!DOCTYPE html> <!-- 文档声明-->
<html lang="en"> <!-- 最外层标签 -->
<!-- lang 国际编码，让网页不出现乱码
        en : 英文网站
        zh-CN : 中文网站
-->
<head>
    <meta charset="UTF-8">  <!-- 元信息 ：是指编写网页中的一些赋值信息-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> <!-- 设置网页的标题-->
</head>
<body>  <!-- 文档可见区域 -->
    ! + tab
</body>
</html>
```



### HTML中的注释

注释是可以在代码中可看，不展示出来

```html
<!-- hello world -->

<!--
	在浏览器中看不到
	在代码中可看
-->
```

意义

- 对开发人员有提示意义
- 暂时不用的代码注释起来，以后可能会用

快捷键

- <kbd>ctrl</kbd> + <kbd> / </kbd> 
- <kbd> shift </kbd> + <kbd> alt </kbd> + <kbd> a </kbd> 

### HTML语义化

定义 ： 更具网页内容的结构，选择适合的HTML标签进行编写

好处：

	1. 在没有CSS的情况下，页面也能体现出很好的内容结构
 	2. 有利于SEO，让搜索引擎爬虫更好的理解网页
 	3. 方便其他设备解析（屏幕阅读器，盲人阅读器）
 	4. 便于团队开发与维护

