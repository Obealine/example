# Markdown 语法示例

这是一个展示 Markdown 常用语法的示例文件。

## 基础格式

**粗体文本**  
*斜体文本*  
~~删除线文本~~  
`行内代码`  

> 引用文本：Markdown 让写作变得简单高效
> - John Gruber

## 列表

### 无序列表
- 项目一
- 项目二
  - 子项目 A
  - 子项目 B
- 项目三

### 有序列表
1. 第一步
2. 第二步
3. 第三步

## 链接与图片

[访问 OpenAI](https://openai.com)  
![替代文本](https://via.placeholder.com/150 "占位图")

## 代码块

行内代码：`print("Hello, World!")`

Python 代码块：
```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        yield a
        a, b = b, a + b

print(list(fibonacci(10)))
```

JavaScript 代码块：
```javascript
// 箭头函数示例
const greet = (name) => {
  return `Hello, ${name}!`;
};

console.log(greet('Markdown'));
```

## 表格

| 功能         | 语法          | 示例       |
|--------------|---------------|------------|
| 表头         | `---`         | 第二行分隔 |
| 左对齐       | `:---`        | 文本左对齐 |
| 居中对齐     | `:---:`       | 文本居中   |
| 右对齐       | `---:`        | 文本右对齐 |

| 姓名       | 年龄 | 职业       |
|------------|------|------------|
| 张三       | 28   | 工程师     |
| 李四       | 32   | 设计师     |
| 王五       | 45   | 产品经理   |

## 高级元素

### 任务列表
- [x] 完成需求分析
- [ ] 编写代码
- [ ] 测试功能
- [ ] 部署上线

### 数学公式（LaTeX）
行内公式：$E = mc^2$

块级公式：
$$
\int_{a}^{b} x^2 dx = \left[ \frac{x^3}{3} \right]_a^b
$$

### 脚注
这是一个带脚注的文本[^1]。

[^1]: 这里是脚注的详细内容。

### 分隔线
---

## HTML 嵌入
<details>
<summary>点击展开详情</summary>
这里是被折叠的内容，支持 HTML 混合使用
</details>

## Emoji 表情
:rocket: :sparkles: :books:  
✅ 已完成 ⚠️ 警告 ❌ 错误

---

> **提示**：  
> 1. 大多数 Markdown 解析器支持这些语法  
> 2. 不同平台可能有细微差异（如 GitHub/GitLab）  
> 3. 使用 `.md` 或 `.markdown` 作为文件扩展名

保存此文件为 `example.md` 即可开始使用！