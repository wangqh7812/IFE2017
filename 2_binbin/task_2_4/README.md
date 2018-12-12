<label> 标签为 input 元素定义标签（label）。

label 元素不会向用户呈现任何特殊的样式。不过，它为鼠标用户改善了可用性，因为如果用户点击 label 元素内的文本，则会切换到控件本身。

<label> 标签的 for 属性应该等于相关元素的 id 元素，以便将它们捆绑起来。

## 关于insertBefore
* 父节点一定要确定
* 像这样是不行的
    document.getElementsByTagName('ul')
* 得这样才可以
    document.getElementsByTagName('ul')[0]