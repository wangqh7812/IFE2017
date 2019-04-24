## parentNode
parentNode 属性可返回某节点的父节点。如果指定的节点没有父节点则返回 null 。

## HTML DOM appendChild() 方法
appendChild() 方法可向节点的子节点列表的末尾添加新的子节点。

* 提示：如果文档树中已经存在了 newchild，它将从文档树中删除，然后重新插入它的新位置。如果 newchild 是 DocumentFragment 节点，则不会直接插入它，而是把它的子节点按序插入当前节点的 childNodes[] 数组的末尾。

你可以使用 appendChild() 方法移除元素到另外一个元素。

##HTML DOM insertBefore() 方法
insertBefore() 方法可在已有的子节点前插入一个新的子节点。

提示： 如果你想创建一个新的文本列表项，在 LI 元素后你应该添加元素的文本节点，然后在列表中添加 LI元素。

你也可以使用 insertBefore 方法来 插入/移除 已存在的元素。

node.insertBefore(newnode,existingnode)

参数|类型|描述
----|----|----
newnode|节点对象|必须。要插入的节点对象
existingnode|节点对象|必须。要添加新的节点前的子节点。