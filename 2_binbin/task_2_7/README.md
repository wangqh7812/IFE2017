# 二叉树的遍历
## 前序遍历
```javascript
function preOrder(node){
    if(node){
        arr.push(node);
        preOrder(node.firstElementChild);
        preOrder(node.lastElementChild);
    }  
}
```
## 中序遍历
```javascript
function preOrder(node){
    if(node){
        preOrder(node.firstElementChild);
        arr.push(node);
        preOrder(node.lastElementChild);
    }  
}
```
## 后序遍历
```javascript
function preOrder(node){
    if(node){
        preOrder(node.firstElementChild);
        preOrder(node.lastElementChild);
        arr.push(node);
    }  
}
```
