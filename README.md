SummerNote
==========
#####version：2014-9-30 21:12:57
###SummerNote简介：
国外某大神基于bootstrap开发的一款文本编辑器，这里只是share一个设置好的中文版本，并提供一些中文说明。
###SummerNote介绍：
国外某大神基于bootstrap2.x和3.x开发的一款文本编辑器，其中还使用了font-awesome字体。（ps：国内关于SummerNote能查到的都是一些简短声明，一年前就一篇简短介绍，也是那个时候研究的）
###SummerNote使用：
* 引入头文件：
```html
<!-- include libries(jQuery, bootstrap, fontawesome) -->
<script type="text/javascript" src="js/jquery-1.9.1.min.js"></script> 
<link rel="stylesheet" href="css/bootstrap.min.css" />
<script type="text/javascript" src="js/bootstrap.min.js"></script>
<link rel="stylesheet" href="css/font-awesome.min.css" />

<!-- include summernote css/js-->
<link rel="stylesheet" href="css/summernote.css" />
<script type="text/javascript" src="js/summernote.js"></script>

<!-- include summernote lang-->
<script type="text/javascript" src="lang/summernote-zh-CN.js"></script>
<script>
	
	$(document).ready(function() {
  		$('#summernote').summernote();
});
</script>
```
  * 调整字体：js/summernote.js->>搜索lang->>改变lang：(对应的值为lang文件夹对应的后缀，例如zh-CN）；
  * 调整SummerNote窗口大小：js/summernote.js->搜索options->改变options：{width: ，height:}（参数对应整型px值）。

###SummerNote建议：
  * 使用bootstrap-3.2,jquery-1.9.1。Demo中已设置为中文，可根据个人需要按使用说明修改。
