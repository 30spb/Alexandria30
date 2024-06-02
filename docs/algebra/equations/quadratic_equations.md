# Квадратные уравнения {#квадратные-уравнения}

## Определение {#определение}

Квадратным называется уравнение вида $ax^2 + bx + c$, где $a \neq 0$.

## Способы решения {#способы-решения}

### Удачные случаи {#удачные-случаи}

Если $b = 0$ или $с = 0$ не нужны специальные приемы для решения такого уравнения.

- $b = 0$: <br>
    Получаем уравнение вида

    $\begin{array}{ll}
        ax^2 + c = 0 \Leftrightarrow
        x^2 = - \frac{c}{a}
    \end{array}$

    - Если $\frac{c}{a} > 0$, то решений нет <br>

    - Если $\frac{c}{a} \le 0$: <br>

        <div style="overflow-x: auto; overflow-y: hidden" markdown="block">

        $\begin{array}{ll}
            x = \sqrt{-\frac{c}{a}}
        \end{array}$

        </div>

- $с = 0$: <br>

    <div style="overflow-x: auto; overflow-y: hidden" markdown="block">

    $\begin{array}{ll}
        ax^2 + bx = 0 \iff \\
        x(ax + b) = 0 \iff \\
        \left[\begin{array}{lr}
            x = 0  \\
            ax + b = 0
        \end{array}\right. \iff \\
        \left[\begin{array}{lr}
            x = 0  \\
            ax = -b
        \end{array}\right. \iff \\
        \left[\begin{array}{lr}
            x = 0  \\
            x = -\frac{b}{a}
        \end{array}\right. \iff \\
    \end{array}$

    </div>

### Остальные случаи {#остальные-случаи}

В случае если $a \neq 0$, $b \neq 0$ и $с \neq 0$ можно использовать следующие теоремы:

- [Теорема о решении квадратных уравнений (дискриминант)](./discriminant.md)
- [Теорема Виета](viet_theorem.md)

---

Над статьей работали:

- Лавелин Михаил ([Тг](https://t.me/mikhaillav)): редактор
- Ефремов Дмитрий ([Тг](https://t.me/TheBestGoood)): редактор

Выражаем благодарность:

- Олегу Вадимовичу, за конспект для данной статьи
