### :root 伪类
匹配文档树的根元素。对于 HTML 来说，:root 表示 <html> 元素，除了优先级更高之外，与 html 选择器相同

### 常见的基于关系的选择器
|选择器 | 选择的元素|
---- | ---
|A E | 元素A的任一后代元素E (后代节点指A的子节点，子节点的子节点，以此类推) |
|A > E | 元素A的任一子元素E(也就是直系后代)  |
|B + E | 元素B的任一下一个兄弟元素E |
|B ~ E | B元素后面的拥有共同父元素的兄弟元素E |