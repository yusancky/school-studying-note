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

求出使 $x \in (-1, 3)$ 是 $x \in \lbrace x | 1 - a < x < 1 + a \rbrace$ 的必要不充分条件的实数 $a$ 的取值范围。

{{< expand "答案和解析" >}}
【错解】$(0, 2]$

【答案】$(-\infty, 2]$

【错因分析】当 $a \leq 0$ 时，$B = \varnothing \subsetneqq A$，仍满足必要不充分条件的要求。

{{< alert theme="info" dir="ltr" >}}
对于任意非空集合 $A$，$m \in A$ 是 $m \in \varnothing$ 的必要不充分条件。
{{< /alert >}}
{{< /expand >}}

----
