# [ 有效的括号 ][title]

## 描述
给定一个只包括 '('，')'，'{'，'}'，'['，']' 的字符串，判断字符串是否有效。

有效字符串需满足：
  左括号必须用相同类型的右括号闭合。
  左括号必须以正确的顺序闭合。
  注意空字符串可被认为是有效字符串。

**示例:**
```
1:
    输入: "()"
    输出: true

2:
    输入: "()[]{}"
    输出: true

3:
    输入: "(]"
    输出: false

4:
    输入: "([)]"
    输出: false

5:
    输入: "{[]}"
    输出: true
```


**标签:** 栈 &  字符串


## 思路
解法： 栈
    利用栈先进先出的特点，确认括号的是否按正确闭合
    
    
## 结语
    合理运用各种数据结构
  
[title]: https://leetcode-cn.com/problems/valid-parentheses/
