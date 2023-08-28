---
title: "必修一"
date: 2023-01-01T00:00:00+08:00
draft: false
libraries:
- katex
---

## 第一章 集合与常用逻辑用语

----

已知集合 $A = \lbrace  a + 1, a^2 + 4a - 9, 2021  \rbrace$。若 $-4 \in A$，则实数 $a$ 的值为（ ）。

A. $-5$

B. $1$

C. $5$ 或 $-1$

D. $-5$ 或 $1$

{{< expand "答案和解析" >}}
【错项】D

【答案】B

【解析】当 $a = -5$ 时， $a + 1 = a^2 + 4a - 9 = -4$，不满足集合中 **元素的互异性**，故 $a \not = -5$。
{{< /expand >}}

----

集合 $A = \lbrace \frac{6}{3 - x} \in \mathbf{Z} | x \in \mathbf{N}^* \rbrace$，用列举法可以表示为（ ）。

A. $\lbrace 3, 6 \rbrace$

B. $\lbrace 1, 2, 4, 5, 6, 9 \rbrace$

C. $\lbrace -6, -3, -2, -1, 3, 6 \rbrace$

D. $\lbrace -6, -3, -2, -1, 2, 3, 6 \rbrace$

{{< expand "答案和解析" >}}
【错项】B

【答案】C

【错因分析】B 项的集合为集合 $A$ 的 **条件值** $x$ 组成的集合，并非**元素值** $\frac{6}{3 - x}$ 组成的集合。
{{< /expand >}}

----

给出下列说法：

①空集没有子集；

②任何集合至少有两个子集；

③空集是任何集合的真子集；

④若 $\varnothing \subseteq A$，则 $A \not = \varnothing$。

其中正确的说法有____个。

{{< expand "答案和解析" >}}
【错解】2

【答案】0

{{< alert theme="warning" dir="ltr" >}}
**空集是任何集合的子集，是任何非空集合的真子集。**
{{< /alert >}}
{{< /expand >}}

----

已知集合 $A = \lbrace x | 0 < x - a \le 5 \rbrace, B = \lbrace x | -\frac a 2 < x \le 6 \rbrace$。若 $B \subseteq A$，则实数 $a$ 的取值范围为____。

{{< expand "答案和解析" >}}
【答案】$[-\infty, -12]$

【解析】当 $B = \varnothing$ 即 $a \leq -12$ 时，$B \subseteq A$ 恒成立；当 $B \not = \varnothing$ 即 $a > -12$ 时，需要 $-\frac a 2 \geq a$ 和 $6 \leq a + 5$ 同时成立，无实数解。综上所述，$a \leq -12$。
{{< /expand >}}

----

已知全集 $S = \lbrace 1, 2, 3, \dots, 10 \rbrace$ 的子集 $A$ 满足 $A \cap \lbrace 1, 2, 3 \rbrace \not = \varnothing , A \cup \lbrace 4, 5, 6 \rbrace \not = S$，则集合 $A$ 的个数为____。

{{< expand "答案和解析" >}}
【答案】888

【解析】根据题意，$\lbrace 1, 2, 3 \rbrace$ 中至少有一个元素属于 $A$，$\lbrace 1, 2, 3, 7, 8, 9, 10 \rbrace$ 中至少有一个元素不属于 $A$。当 $\lbrace 1, 2, 3 \rbrace \subseteq A$ 时，可以任意选择 $\lbrace 4, 5, 6 \rbrace$ 中的元素和 $\lbrace 7, 8, 9, 10 \rbrace$ 的真子集中的元素，共有 $2^3 \times (2^4 - 1)$ 个符合题意的集合；否则，共有 $2^7$ 个符合题意的集合。综上所述，共有 $2^3 \times (2^4-1) + 2^7 = 888$ 个符合题意的集合。
{{< /expand >}}

----

使 $x \in (-1, 3)$ 是 $x \in \lbrace x | 1 - a < x < 1 + a \rbrace$ 的必要不充分条件的实数 $a$ 的取值范围是____。

{{< expand "答案和解析" >}}
【错解】$(0, 2]$

【答案】$(-\infty, 2]$

【错因分析】当 $a \leq 0$ 时，$B = \varnothing \subsetneqq A$，仍满足必要不充分条件的要求。

{{< alert theme="info" dir="ltr" >}}
对于任意非空集合 $A$，$m \in A$ 是 $m \in \varnothing$ 的必要不充分条件。
{{< /alert >}}
{{< /expand >}}

----

命题“$\forall x > -3, \frac{3}{2x - 4} < 0$”的否定形式是____。

{{< expand "答案和解析" >}}
【错解】$\exists x > -3, \frac{3}{2x - 4} \geq 0$

【答案】$\exists x > -3, \frac{3}{2x - 4} \geq 0 \text{ 或 } 2x - 4 = 0$
{{< /expand >}}

----

若 $\lbrace x | ax - 6 = 0 \rbrace \cup \lbrace 2, 3 \rbrace = \lbrace 2, 3 \rbrace$，则实数 $a$ 的所有可能的值构成的集合是____。

{{< expand "答案和解析" >}}
【错解】$\lbrace 2, 3 \rbrace$

【答案】\lbrace 0, 2, 3 \rbrace$

【错因分析】当 $a = 0$ 时，$\lbrace x | ax - 6 = 0 \rbrace = \varnothing$，符合题意。
{{< /expand >}}

----

命题“$\forall x \in \mathbf{R}, \exists n \in \mathbf{N}^*, n \geq x^2$”的否定形式是____。

A. $\forall x \in \mathbf{R}, \exists n \in \mathbf{N}^*, n < x^2$

B. $\forall x \in \mathbf{R}, \forall n \in \mathbf{N}^*, n < x^2$

C. $\exists x \in \mathbf{R}, \exists n \in \mathbf{N}^*, n < x^2$

D. $\exists x \in \mathbf{R}, \forall n \in \mathbf{N}^*, n < x^2$

{{< expand "答案和解析" >}}
【错项】B

【答案】D
{{< /expand >}}

----

## 第二章 一元二次函数、方程和不等式

----

已知 $-3 \leq a + b \leq 2, -1 \leq a - b \leq 4$，$3a - 2b$ 的取值范围为____。

{{< expand "答案和解析" >}}
【答案】$[-4, 11]$

【解析】考虑将 $a + b$ 和 $a - b$ 整体代入至 $3a - 2b = \frac 1 2 (a + b) + \frac 5 2 (a - b)$。
{{< /expand >}}

----

已知非负实数 $x, y, z$ 满足 $3x + 2y + z = 5, 2x + y - 3z = 1$，求 $u = 3x + y - 7z$ 的取值范围。

{{< expand "答案和解析" >}}
由已知可消元知 $x = 7z - 3 \geq 0, y = -11z + 7 \geq 0, z \geq 0$，故 $\frac 3 7 \leq z \leq \frac{7}{11}$。

把上式代入知 $u = 3z - 2$，结合 $z$ 的取值范围可知 $-\frac 5 7 \leq u \leq -\frac{1}{11}$。
{{< /expand >}}

----

已知 $a, b, c$ 为三角形三边长，求证 $(a + b + c) ^ 2 < 4(ab + ac + bc)$。

{{< expand "答案和解析" >}}
$$
\begin{aligned}
(a + b + c) ^ 2 &= a ^ 2 + b ^ 2 + c ^ 2 + 2(ab + ac + bc) \\
&= a \times a + b \times b + c \times c + 2(ab + ac + bc) \\
&\lt a(b + c) + b(a + c) + c(a + b) + 2(ab + ac + bc) \\
&= 4(ab + ac + bc)
\end{aligned}
$$
{{< /expand >}}

----

若正实数 $x, y$ 满足 $(x - y) ^ 2 = (xy) ^ 3$，求 $\frac 1 x + \frac 1 y$ 的最小值。

{{< expand "答案和解析" >}}
$$
\begin{aligned}
(x - y) ^ 2 &= (xy) ^ 3 \\
\frac{(x - y) ^ 2}{(xy) ^ 2} &= xy \\
(\frac 1 x - \frac 1 y) ^ 2 &= xy \\
(\frac 1 x + \frac 1 y) ^ 2 - \frac{4}{xy} &= xy \\
(\frac 1 x + \frac 1 y) &= \sqrt{xy + \frac{4}{xy}} \\
&\geq \sqrt{2 \sqrt{4}} \\
&= 2 \\
\end{aligned}
$$
{{< /expand >}}

----
