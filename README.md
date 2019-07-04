# React Demo 学习笔记

## TODO LIST
- [x] 课前准备  
    - [x] 前置知识  
- [x] 环境准备  
- [x] 概览  
    - [x] 通过 Props 传递数据  
    - [x] 给组件添加交互功能  
- [ ] 游戏完善  
    - [x] 状态提升  
    - [x] 函数式组件  
    - [x] 轮流落子  
    - [ ] 判断出胜者  
- [ ] 时间旅行  
    - [ ] 保存历史记录  
    - [ ] 再次提升状态  
    - [ ] 展示历史步骤记录  
    - [ ] 选择一个 key  
    - [ ] 实现时间旅行  

## 问题收集
- 在 `click` 事件中使用 `this.setState({value: 'X'})` 来设置 `value` 值，为什么不能直接赋值，形如 `this.state.value = 'X'`

## 最佳实践
- 通常会将代表事件的监听 `prop` 命名为 `on[Event]`，将处理事件的监听方法命名为 `handle[Event]` 这样的格式。
