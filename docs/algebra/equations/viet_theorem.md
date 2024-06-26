# Теорема Виета

## Формулировка {#формулировка}

Числа x~1~, x~2~ тогда и только тогда являются корнями [квадратного уравнения](quadratic_equations.md#определение), когда для них выполняются, следующие соотношения.

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

$\begin{cases}
    x_1 + x_2 = - \frac{b}{a} \\
    x_1 \cdot x_2 = \frac{c}{a}
\end{cases}$

</div>

## Доказательство {#доказательство}

### Прямое утверждение {#прямое-утверждение}

Если x~1~, x~2~ - корни, то выполняется [соотношения](#формулировка).

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

Пусть

$\begin{array}{ll}
    x_1 = - \frac{b + \sqrt D}{2a} \\
    x_2 = - \frac{b - \sqrt D}{2a} \\
\end{array}$

</div>

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

Тогда

$\begin{cases}
    x_1 + x_2 = \frac{-b + \sqrt D - \sqrt D - b}{2a} = - \frac{2b}{2a} = - \frac{b}{a}\\
    x_1 \cdot x_2 = \frac{(-b + \sqrt D) (-b - \sqrt D)}{4a^2} = \frac{b^2 - D}{4a^2} = \frac{b^2 - b^2 + 4ac}{4a^2} = \frac{c}{a} \\
\end{cases}$

</div>

### Обратное утверждение {#обратное-утверждение}

Если выполняется [соотношения](#формулировка), то x~1~, x~2~ - корни.

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

Рассмотрим выражение $a(x - x_1)(x - x_2)$.

$\begin{array}{ll}
    a(x - x_1)(x - x_2) = \\
    a(x^2 - x(x_1 + x_2) + x_1x_2) = \\
    a(x^2 + x \frac{b}{a} + \frac{c}{a}) = \\
    ax^2 + bx + c \\
\end{array}$

</div>

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

x~1~, x~2~ - корни уравнения $a(x - x_1)(x - x_2) = 0$ (обращают его в ноль).

А значит и корни уравнения $ax^2 + bx + c = 0$.

</div>

## Теорема о разложении квадратного трехчлена на множители (следствие) {#теорема-о-разложении-квадратного-трехчлена-на-множители}

### Формулировка {#формулировка-теоремы-о-разложении-квадратного-трехчлена-на-множители}

<div style="overflow-x: auto; overflow-y: hidden" markdown="block">

Если [квадратное уравнение](quadratic_equations.md#определение) имеет два корня, то верно равенство $ax^2 + bx + c = a(x - x_1)(x - x_2)$

</div>

### Доказательство {#доказательство-теоремы-о-разложении-квадратного-трехчлена-на-множители}

См. [Доказательство обратного утверждения теоремы Виета](#обратное-утверждение)

---

Над статьей работали:

- Лавелин Михаил ([Тг](https://t.me/mikhaillav)): редактор

Выражаем благодарность:

- Олегу Вадимовичу, за конспект для данной статьи
