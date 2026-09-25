---
title: 2.1.1 - Section2.1.1
---

This is section 2.1.1.

---

## Inner Section

The right-side _Table of Contents_ (**ToC**) is generated from inner section headings (`##`, `###`, ...).

### Subsection

- Subscript: H<sub>2</sub>O  
  A paragraph.
  1. Level 2  
     A paragraph.
     1. Level 3  
        A paragraph.
        - Level 4
- Superscript: x<sup>2</sup>
  - Level 2
- A inline formula: $E = mc^2$
- A formula block:

$$
\int_{a}^{b} f(x) \, dx = F(b) - F(a)
$$

---

## Links

[Link](https://bradhezh.github.io/markdown-example/)  
https://bradhezh.github.io/markdown-example/

[Brad](mailto:bradhezh@gmail.com)  
bradhezh@gmail.com

Click [<img src='/markdown-example/img/favicon.ico' />](/img/docusaurus-social-card.jpg)

<figure align="center">
  <img src="/markdown-example/img/docusaurus.png" alt="Docusaurus" />
  <figcaption><strong>Figure 1.1:</strong> Description</figcaption>
</figure>

## Tables

| Left             |      Center      |            Right |
| :--------------- | :--------------: | ---------------: |
| left             |      center      |            right |
| ---------------- | ---------------- | ---------------- |

<table>
  <thead>
    <tr><th rowspan="2">Head</th><th colspan="2">Head</th></tr>
    <tr><th>Head</th><th>Head</th></tr>
  </thead>
  <tbody>
    <tr><td colspan="2" align="center">cell</td><td align="right">cell</td></tr>
  </tbody>
</table>

## Code Blocks

```typescript title="src/app.ts" showLineNumbers {1,6}
interface User {
  id: number;
  name: string;
}

function hello(user: User) {
  return `Hello, ${user.name}!`;
}

const brad = { id: 0, name: "Brad" };
console.log(hello(brad));
```
