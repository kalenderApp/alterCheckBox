alterCheckBox
=============
使用方法：
1. 选择想要重写样式的 CheckBox 元素。
2. 调用函数。
3. 设置相应的样式。选中和未选中样式。
   默认为 checked 选中 和 unchecked 未选中。

例如：
    <pre>
    $(".checkbox").alterCheckBox({
        checked:"checked",
        unchecked:"unchecked"
    });
    </pre>
    或者重写样式：
    <pre>
    $(".checkbox2").alterCheckBox({
        checked:"checked2",
        unchecked:"unchecked2"
    });
     </pre>