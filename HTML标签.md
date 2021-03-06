# HTML标签

## label

label只有两个属性for（规定 label 绑定到哪个表单元素）和form（规定 label 字段所属的一个或多个表单）
<label> 标签为 input 元素定义标注（标记）。

label 元素不会向用户呈现任何特殊效果。不过，它为鼠标用户改进了可用性。如果您在 label 元素内点击文本，就会触发此控件。就是说，当用户选择该标签时，浏览器就会自动将焦点转到和标签相关的表单控件上。

<label> 标签的 for 属性应当与相关元素的 id 属性相同。

form 属性规定 label 所属的一个或多个表单。

form 属性的值必须是其所属的表单的 id。

如需引用一个以上的表单，请使用空格分隔的列表。

## form

<form> 标签用于为用户输入创建 HTML 表单。

表单能够包含 input 元素，比如文本字段、复选框、单选框、提交按钮等等。

表单还可以包含 menus、textarea、fieldset、legend 和 label 元素。

表单用于向服务器传输数据。

## input

disabled指当 input 元素加载时禁用此元素。input内容不会随着表单提交
readonly规定输入字段为只读。input内容会随着表单提交。
无论设置readonly还是disabled，通过js脚本都能更改input的value（亲测可以）

![img](img/input.png)

## a

_blank	在新窗口中打开被链接文档。
_self	默认。在相同的框架中打开被链接文档。
_parent	在父框架集中打开被链接文档。
_top	在整个窗口中打开被链接文档。
framename	在指定的框架中打开被链接文档。

## meta

<meta> 元素可提供有关页面的元信息（meta-information），比如针对搜索引擎和更新频度的描述和关键词。
<meta> 标签永远位于 head 元素内部。
<meta> 标签的属性定义了与文档相关联的名称/值对。

## 自关闭标签

HTML5中：
自关闭的斜线(/)对 ：area, base, br, col, command, embed, hr, img, input, keygen, link, meta, param, source, track, wbr空标签无效，言即不再需要自闭合(/)这个小尾巴了，如果要写上也是可以的。
