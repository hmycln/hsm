小草论坛绳梦阁论坛(官方网站)夜来香论坛官网

*number类型的input元素是一种专门用来输入数字的文本框，并且在提交时候检查输入的内容是否为数字，它具有min、max和step属性。

<input name="num" type=number value=123 min=10 max=100 step=5 >

    1

*Range是一种只允许输入一段范围内数值的文本框，它具有min、max和step属性默认是0-100

<input name=num2 type=range value=50 min=10 step=5 >

    1

*output 定义不同类型的输出

<!-- range滑动块的值显示在output元素中 -->
<input type=range value=50 onchange="num.value=value" min=10 max=100 step=5 >
<output id=num >50</output> <br>

    1
    2
    3

*Color 用来选择颜色，它提供了一个颜色选择器。

Color:<input type=color name=color >

    1

*File 文件选择框，可以通过指定multiple属性一次性选择多个文件，value的值是一个逗号分隔的一个或多个文件名。同时通过MIME类型指定给accept属性，可以限制选择文件的种类。

file：<input type=file multiple accept="image/*" name=pic >

    1

*novalidate ===========>在form标签里面使用使所有HTML5新增的验证失效
formnovalidate=========>在input元素使用，使改元素HTML5新增验证失效（另外加的验证不会失效如require）
HTML5新增多媒体播放元素
*audio元素用于播放音频文件
