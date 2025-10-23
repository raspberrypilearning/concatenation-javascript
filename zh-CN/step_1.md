你可以在 JavaScript 中组合文本（字符串）和变量。

“字符串”是 JavaScript 和其他编程语言中的一种数据类型。 数据类型是一组数据，它告诉程序我们如何使用数据。

你可以使用连接或模板文字来格式化字符串。

### 连接

你可以使用 `+` 运算符将字符串组合在一起。

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const superhero = "钢铁侠";
const power = "盔甲套装";
// 连接字符串的示例
const description = "超级英雄" + superhero + " 拥有 " + power + "。";
console.log(description);

\--- /code ---

### 模板字符串

你可以使用反引号 `` ` `` 将变量嵌入这些符号中：`${}`，从而将变量的内容包含在字符串中。

下面是一个示例。

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const name = "蜘蛛侠";
const age = 25;
// 使用模板文字的示例
const message = `你好, ${name}！ 你已经 ${age} 岁了。`;
console.log(message);

\--- /code ---
