# Теорема о решении квадратных уравнений (дискриминант)

## Формулировка {#формулировка}

Имеется квадратное уравнение вида $ax^2 + bx + c$, где $a \neq 0$. <br>
Пусть $D = b^2 - 4ac$. <br>

Тогда утверждается, что если: <br>

- $D < 0$: уравнение не имеет решений
- $D = 0$: уравнение имеет ровно одно решение:
    - $x = - \frac{b}{2a}$
- $D > 0$: уравнение имеет ровно два решения:
    - $x_1 = - \frac{b + \sqrt{D}}{2a}$
    - $x_2 = - \frac{b - \sqrt{D}}{2a}$

## Доказательство {#доказательство}

$ax^2 + bx + c = 0 \iff$ <br><br>
$x^2 + \frac{bx}{a} + \frac{c}{a} = 0 \iff$ <br><br>
$x^2 + 2 \frac{b}{2a} x + \frac{b^2}{4a^2} - \frac{b^2}{4a^2} + \frac{c}{a} = 0 \iff$ <br><br>
$(x + \frac{b}{2a})^2 - (\frac{b^2}{4a^2} - \frac{c}{a}) = 0 \iff$ <br><br>
$(x + \frac{b}{2a})^2 - \frac{b^2 - 4ac}{4a^2} = 0 \iff$ <br><br>
$(x + \frac{b}{2a})^2 - \frac{D}{4a^2} = 0$ <br><br>

- $D < 0$: <br>
    Сумма неотрицательного ($x + \frac{b}{2a}^2$) и положительного (-$\frac{-D}{4a^2}$) числа не может быть равна нулю.
- $D = 0$: <br>
    $(x + \frac{b}{2a})^2 = 0 \iff$ <br><br>
    $x + \frac{b}{2a} = 0 \iff$ <br><br>
    $x = -\frac{b}{2a}$ <br><br>
- $D > 0$: <br>
    $(x + \frac{b}{2a} - \frac{\sqrt{D}}{2a})(x + \frac{b}{2a} + \frac{\sqrt{D}}{2a}) = 0 \iff$ <br><br>
    $x + \frac{b}{2a} - \frac{\sqrt{D}}{2a} = 0 \lor x + \frac{b}{2a} + \frac{\sqrt{D}}{2a} = 0 \iff$ <br><br>
    $x = - \frac{b}{2a} + \frac{\sqrt{D}}{2a} \lor x = - \frac{b}{2a} - \frac{\sqrt{D}}{2a} \iff$ <br><br>
    $x = - \frac{b + \sqrt{D}}{2a} \lor x = - \frac{b - \sqrt{D}}{2a} \iff$ <br><br>
    $x = - \frac{b \pm \sqrt{D}}{2a}$

---
| Author         | Contact                       | Role     |
|----------------|-------------------------------|----------|
| Ренёв О.В.     |                               | Автор    |
| Лавелин Михаил | [Тг](https://t.me/mikhaillav) | Редактор |