# Tree-Widget
Simple UI to learn OOP<br />
[Demo: Tree Widget](https://robbyvan.github.io/Tree-Widget/index.html)<br /> (May not display correctly in browers that does not support ES6)
![](./sample.jpeg)

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

        /*Add Initial nodes*/
        root.addTreeNode('Computer Science');
        root.children[0].addTreeNode('Data Structure and Algorithms');
        root.children[0].addTreeNode('Operating System');
        root.children[0].addTreeNode('Programming Languages');
        root.children[0].children[2].addTreeNode('JavaScript');
        root.children[0].children[2].addTreeNode('C++');
        root.children[0].addTreeNode('Database');
        root.children[0].addTreeNode('Computer Networks');
        root.addTreeNode('Electrical Engineering');
        root.children[1].addTreeNode('Analog Circuit');
        root.children[1].addTreeNode('Digital Circuit');
        root.children[1].addTreeNode('Computer Networks');

        root.children[1].addTreeNode('Computer Networks');
```

