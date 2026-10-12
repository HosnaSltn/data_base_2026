# Basic LaTeX

This file is a short reference guide to help you write your answers in LaTeX using the provided exercise template.

## 1. Introduction and Learning Resources

This file covers the basic commands you may need, including text formatting, mathematical expressions, lists, matrices, sets, and logical expressions. You do not need to master LaTeX; the goal is simply to learn enough to write clear and well-formatted answers.

If you are new to LaTeX, the following resources can help you get started:

- [**Overleaf: LaTeX Video Tutorials for Beginners**](https://www.overleaf.com/learn/latex/LaTeX_video_tutorial_for_beginners_%28video_1%29) — A seven-part video series that introduces LaTeX from the beginning. Start with Video 1 to learn how to use the editor and compile a document. You can watch other videos as needed.
    
- [**Learn LaTeX in 30 Minutes**](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes) — A concise written tutorial covering the basics.
    
- [**LaTeX Full Tutorial for Beginners — freeCodeCamp.org (YouTube)**](https://www.youtube.com/watch?v=ydOTMQC7np0): A more comprehensive video tutorial. You only need to focus on the parts relevant to your assignments, such as writing text, mathematical expressions, lists, and matrices.
    


You can use this file as a quick reference while completing your exercises. You are not expected to memorize the commands; look them up whenever you need them.

**Important:** Work within the provided template and preserve its existing structure and commands. You only need to write your answers in the designated areas.

## 2. Writing text

| What you want | LaTeX syntax |
|---|---|
|New paragraph|Leave a blank line|
|Bold text|`\textbf{bold text}`|
|Italic text|`\textit{italic text}`|
|Underlined text|`\underline{underlined text}`|
|Line break|`\\`|
|Percent sign (%)|`\%`|
|Dollar sign ($)|`\$`|
|Ampersand (&)|`\&`|

Example:
```
This is the first paragraph.

  

This is the second paragraph.

  

\textbf{Important:} This is bold text.
```

## 3. Writing mathematical expressions

|What you want|LaTeX syntax|
|---|---|
|Inline equation|`$a+b=c$`|
|Equation on a separate line|`\[a+b=c\]`|
|Fraction|`\frac{a}{b}`|
|Exponent|`x^2`|
|Subscript|`x_1`|
|Square root|`\sqrt{x}`|
|Greek letters|`\alpha`, `\beta`, `\theta`, `\lambda`|
|Summation|`\sum_{i=1}^{n} i`|
|Infinity|`\infty`|
|Not equal|`\neq`|
|Less than or equal to|`\leq`|
|Greater than or equal to|`\geq`|
|Approximately equal|`\approx`|
|Multiplication|`\times`|
|Set membership|`\in`|
  
Displayed equation:
```
\[

x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}

\]
```

For multiple aligned equations:
```
\[

\begin{aligned}

x+y &= 5 \\

x-y &= 1

\end{aligned}

\]
```
  
## 4. Writing lists

For a bulleted list:
```
\begin{itemize}

  \item First item

  \item Second item

  \item Third item

\end{itemize}
```

For a numbered list:
```
\begin{enumerate}

  \item First step

  \item Second step

  \item Third step

\end{enumerate}
```

## 5. Writing matrices

Example of a $2\times2$ matrix:
```
\[

A = \begin{bmatrix}

1 & 2 \\

3 & 4

\end{bmatrix}

\]
```

- `&` separates columns.

- `\\` starts a new row.

- `bmatrix` creates square brackets.

## 6. Writing sets and logical expressions

|What you want|LaTeX syntax|
|---|---|
|Set braces|`\{1,2,3\}`|
|Empty set|`\emptyset`|
|Union|`\cup`|
|Intersection|`\cap`|
|Subset|`\subseteq`|
|For all|`\forall`|
|There exists|`\exists`|
|Logical AND|`\land`|
|Logical OR|`\lor`|
|Implies|`\Rightarrow`|
|If and only if|`\Leftrightarrow`|

Example:
```
\[

A \subseteq B \Rightarrow A \cap B = A

\]
```