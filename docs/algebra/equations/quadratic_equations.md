# Квадратные уравнения {#квадратные-уравнения}

## Определение {#определение}

Квадратным называется уравнение вида $ax^2 + bx + c$, где $a \neq 0$.

## Способы решения {#способы-решения}

### Удачные случаи {#удачные-случаи}

Если $b = 0$ или $с = 0$ не нужны специальные приемы для решения такого уравнения.

- $b = 0$: <br>
    - Если $c > 0$, то решений нет <br>

    - Если $c \le 0$: <br>

        <div style="overflow-x: auto; overflow-y: hidden" markdown="block">

        $\begin{array}{ll}
            x^2 - c = 0 \iff \\
            (x - \sqrt c)(x + \sqrt c) = 0 \iff \\
            \left[\begin{array}{lr}
                x - \sqrt c = 0 \\
                x + \sqrt c = 0
            \end{array}\right. \iff \\
            x = \pm \sqrt c
        \end{array}$

        </div>

- $с = 0$: <br>

    <div style="overflow-x: auto; overflow-y: hidden" markdown="block">

    $\begin{array}{ll}
        x^2 - bx = 0 \iff \\
        x(x - b) = 0 \iff \\
        \left[\begin{array}{lr}
            x = 0  \\
            x - b = 0
        \end{array}\right. \iff \\
        \left[\begin{array}{lr}
            x = 0  \\
            x = b
        \end{array}\right.
    \end{array}$

    </div>

### Остальные случаи {#остальные-случаи}

В случае если $a \neq 0$, $b \neq 0$ и $с \neq 0$ можно использовать следующие теоремы:

- [Теорема о решении квадратных уравнений (дискриминант)](./discriminant.md)

---
| Author         | Contact                       | Role     |
|----------------|-------------------------------|----------|
| Ренёв О.В.     |                               | Автор    |
| Лавелин Михаил | [Тг](https://t.me/mikhaillav) | Редактор |
