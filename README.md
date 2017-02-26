# Tree-Widget
Simple UI to learn OOP<br />
[Demo: Tree Widget](https://robbyvan.github.io/Tree-Widget/index.html)<br /> (May not display correctly in browers that does not support ES6)

## Syntax
```js
   var UIInstance = new TreeNode(nodeConfig, outputId);
   
   @param {Object} nodeConfig
   nodeConfig = {
    nodeContent = nodeConfig.nodeContent || "";
   }
  
   @param {String} outputId // Id of the output field for the treewidget
   
```
  

## Examples
```js
   /* Instantiate root */
   const root = new TreeNode({nodeContent: 'Engineering'}, 'tree-panel');
   root.init(root.nodeContent);
```
<br />
![](./sample.jpeg)
