# Tag 组件

## 如何创建一个 tag 组件
1. 左侧使用 span 来循环显示输入的 tag
2. 右侧是一个 输入框
3. 每次输入框中检测是否敲击了 enter，就把数据添加到 tags 数组中，然后 tags 数组循环，遍历循环到 input 左侧使用 span 来渲染
4. 每次 input 中删除到没有数据的时候，这时候如果继续敲击 backspace ，就把左侧的一个 tag 删除，直到删除到没有 tags 
