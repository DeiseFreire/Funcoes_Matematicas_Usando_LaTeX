![LaTex](https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white) ![overleaf](https://img.shields.io/badge/Overleaf-47A141?style=for-the-badge&logo=Overleaf&logoColor=white) <a href="https://www.youtube.com/watch?v=zjsUvLKL8rU&list=PLZpH1iUcDo5jySyW1zOz5PV4Yg84VV-fg&index=11" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>

## 💕 Composição de Funções em LaTeX

Este documento LaTeX calcula a composição de funções `g \circ f(x)` para as funções `f(x) = \frac{1}{x}` e `g(x) = 3x + 1`.

## 💕 **Entrada**

* Função f(x) = 1/x
* Função g(x) = 3x + 1

## 💕 **Saída**

O documento determina a composição `g(f(x))` para cada caso:

(a) g(f(x)) = (3 + x) / x
(b) f(g(x)) = 1 / (3x + 1)
(c) g(g(x)) = 9x + 4
(d) f(f(x)) = x

## 💕 Sintaxe LaTex

```
\text{Dadas as funçôes $f\left( x \right) = \frac{1}{x}$ e $g\left( x \right) = 3x + 1$, determine: $g \circ f\left( x \right)$} \\

\text{$f\left( x \right) = \frac{1}{x}$ e $g\left( x \right) = 3x + 1$}  \\
(a) \mspace{9mu} g \circ f\left( x \right) = g\left( f\left( x \right) \right) = g\left(\frac{1}{x} \right) = 3 \cdot \frac{1}{x} + 1 =\frac{3 + x}{x} = \frac{x + 3}{x} \\

(b) \mspace{9mu} f \circ g\left( x \right) = f\left( g\left( x \right) \right) = f\left( 3x + 1 \right) = \frac{1}{3x +1} \\

(c) \mspace{9mu} g \circ g\left( x \right) = g\left( g\left( x \right) \right) = g\left( 3x + 1 \right) = 3 \cdot \left( 3x + 1 \right) + 1 = 9X + 3 + 1 = 9x + 4 \\

(d) \mspace{9mu} f \circ f\left( x \right) = f\left( f\left( x \right) \right) = f\left(\frac{1}{x} \right) = \frac{1}{\frac{1}{x}} = 1 \cdot \frac{x}{1} = x \\
```
## 💕 **Observações**

* O documento utiliza comandos LaTeX para formatar a matemática.
* Os resultados estão organizados por itens para melhor visualização.

## 💕 **Compilação**

Para compilar este documento LaTeX, você precisará de um compilador LaTeX como o pdflatex ou lualatex. Salve o código como um arquivo `.tex` (por exemplo, composicao_funcoes.tex) e execute o comando apropriado para gerar um arquivo PDF contendo o documento.

## 💕Image
![image](https://github.com/DeiseFreire/tex213117062024/blob/main/image.png)
