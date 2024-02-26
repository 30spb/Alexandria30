# Теорема о решении квадратных уравнений (дискриминант)

## Формулировка {#формулировка}

Имеется квадратное уравнение вида $ax^2 + bx + c$, где $a \neq 0$. <br>
Пусть $D = b^2 - 4ac$. <br>

Тогда утверждается, что если: <br>

<div style="overflow-x: auto" markdown="block">

- $D < 0$: уравнение не имеет решений
- $D = 0$: уравнение имеет ровно одно решение:
    - $x = - \frac{b}{2a}$
- $D > 0$: уравнение имеет ровно два решения:
    - $x_1 = - \frac{b + \sqrt{D}}{2a}$
    - $x_2 = - \frac{b - \sqrt{D}}{2a}$

</div>

## Доказательство {#доказательство}

<!-- God bless everyone who brave enough to read that latex code below ^^ -->

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

$\begin{array}{ll}
    ax^2 + bx + c = 0 \iff \\
    x^2 + \frac{bx}{a} + \frac{c}{a} = 0 \iff \\
    x^2 + 2 \frac{b}{2a} x + \frac{b^2}{4a^2} - \frac{b^2}{4a^2} + \frac{c}{a} = 0 \iff \\
    (x + \frac{b}{2a})^2 - (\frac{b^2}{4a^2} - \frac{c}{a}) = 0 \iff \\
    (x + \frac{b}{2a})^2 - \frac{b^2 - 4ac}{4a^2} = 0 \iff \\
    (x + \frac{b}{2a})^2 - \frac{D}{4a^2} = 0 \\
\end{array}$

</div>

- $D < 0$: <br>
    Сумма неотрицательного ($x + \frac{b}{2a}^2$) и положительного (-$\frac{-D}{4a^2}$) числа не может быть равна нулю. <br><br>

- $D = 0$: <br>
    <div style="overflow-x: auto; overflow-y: hidden" markdown="block">

    $\begin{array}{ll}
        (x + \frac{b}{2a})^2 = 0 \iff \\
        x + \frac{b}{2a} = 0 \iff \\
        x = -\frac{b}{2a}
    \end{array}$

    </div>

- $D > 0$: <br>

    <div style="overflow-x: auto; overflow-y: hidden" markdown="block">

    $\begin{array}{ll}
        (x + \frac{b}{2a} - \frac{\sqrt{D}}{2a})(x + \frac{b}{2a} + \frac{\sqrt{D}}{2a}) = 0 \iff \\
        (x + \frac{b}{2a} - \frac{\sqrt{D}}{2a})(x + \frac{b}{2a} + \frac{\sqrt{D}}{2a}) = 0 \iff \\
        \left[\begin{array}{lr}
            x + \frac{b}{2a} - \frac{\sqrt{D}}{2a} = 0 \\
            x + \frac{b}{2a} + \frac{\sqrt{D}}{2a} = 0
        \end{array}\right. \iff \\
        \left[\begin{array}{lr}
            x = - \frac{b}{2a} + \frac{\sqrt{D}}{2a} \\
            x = - \frac{b}{2a} - \frac{\sqrt{D}}{2a}
        \end{array}\right. \iff \\
        \left[\begin{array}{lr}
            x = - \frac{b + \sqrt{D}}{2a} \\
            x = - \frac{b - \sqrt{D}}{2a}
        \end{array}\right. \iff \\
        x = - \frac{b \pm \sqrt{D}}{2a}
    \end{array}$

    </div>

---

Над статьей работали:

- Лавелин Михаил ([Тг](https://t.me/mikhaillav)): редактор

Выражаем благодарность:

- Олегу Вадимовичу, за конспект для данной статьи
