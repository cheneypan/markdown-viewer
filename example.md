# Markdown Viewer 示例文档

这是一个用于测试 Markdown Viewer 功能的示例文档。

## 功能特性

### 1. Markdown 基础语法

支持所有标准 Markdown 语法：

- **粗体文本**
- *斜体文本*
- `行内代码`
- ~~删除线~~

### 2. 代码块

```javascript
function hello() {
    console.log("Hello, Markdown Viewer!");
}
```

### 3. 表格

| 功能 | 状态 | 说明 |
|------|------|------|
| Markdown 解析 | ✅ | 支持 |
| Mermaid 图表 | ✅ | 支持 |
| 代码高亮 | ✅ | 支持 |
| 目录导航 | ✅ | 支持 |

## Mermaid 图表示例

### 流程图

```mermaid
graph TD
    A[开始] --> B{是否登录?}
    B -->|是| C[显示主页]
    B -->|否| D[跳转登录页]
    D --> E[用户登录]
    E --> C
    C --> F[结束]
```

### 时序图

```mermaid
sequenceDiagram
    participant 用户
    participant 浏览器
    participant 服务器
    用户->>浏览器: 打开网页
    浏览器->>服务器: 发送请求
    服务器-->>浏览器: 返回数据
    浏览器-->>用户: 显示内容
```

### 饼图

```mermaid
pie showData
    title 功能占比
    "Markdown解析" : 40
    "Mermaid渲染" : 30
    "代码高亮" : 20
    "其他功能" : 10
```

## 引用块

> Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
> 
> — John Gruber

## 任务列表

- [x] 支持 Markdown 解析
- [x] 支持 Mermaid 图表
- [x] 支持代码高亮
- [x] 支持目录导航
- [x] 支持深色模式
- [ ] 更多功能开发中...

---

感谢使用 Markdown Viewer！
