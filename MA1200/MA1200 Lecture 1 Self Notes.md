## MA1200 Lecture 1 Self Notes

## Polar Form

$\forall P(x,y), x\neq 0, r:=\sqrt{x^2+y^2}, \theta:=\arctan(\frac{y}{x}),$

|        | x > 0  | x < 0 |
|  ----  | ----   |  ---- |
| $y > 0$ | 1st quadrant => $0+\theta$ | 2nd quadrant => $180^\circ-\theta$ |
| $y < 0$ | 4th quadrant => $360^\circ-\theta$ | 3rd quadrant => $-180^\circ+\theta$ |



## Parabola

### Formulas

| Equations | Vertex | AoS | Focus | $F_{l}$ | Directrix |
| ---- | ---- | ---- | ---- | ---- | ---- |
| $(y-k)^2=4p(x-h)$ | $(h,k)$ | $y=k$ | $(h+p,k)$ | $p$ | $x=k-p$ |
| $(x-h)^2=4p(y-k)$ | $(h,k)$ | $x=h$ | $(h,k+p)$ | $p$ | $y=k-p$ |
| $y=ax^2+bx+c$ | $(-\frac{b}{2a},\frac{4ac-b^2}{4a})$ | $x=-\frac{b}{2a}$ | $(h,k+\frac{1}{4a})$ | $\frac{1}{4a}$ | $y=\frac{4ac-b^2-1}{4a}$ |

### Determining Equations based on Graphs

- Determine Concavity

  | Equations         | $p>0$                      | $p<0$                     |
  | ----------------- | -------------------------- | ------------------------- |
  | $(y-k)^2=4p(x-h)$ | "tails" point to the right | "tails" point to the left |
  | $(x-h)^2=4p(y-k)$ | "tails" point upwards      | "tails" point down        |

- Find Vertex

- Find $\triangle=b^2-4ac$ ,

  | $\triangle>0$  | $\triangle=0$ | $\triangle<0$ |
  | -------------- | ------------- | ------------- |
  | Two real roots | One real root | No real root  |



# Ellipse

## Formulas

| Equation     | $\frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1,\ a>b$ | $\frac{(x-h)^2}{b^2}+\frac{(y-k)^2}{a^2}=1,\ a>b$ |
| ------------ | ------------------------------------------------- | ------------------------------------------------- |
| Eccentricity | $e=\frac{\sqrt{a^2-b^2}}{a}, a>b$                 | $e=\frac{\sqrt{a^2-b^2}}{a}, a>b$                 |
| Centre       | $(h,k)$                                           | $(h,k)$                                           |
| Shape        | Fat and short                                     | Thin and long                                     |
| Major Axis   | $y=k\ (\text{len: }2a)$                           | $x=h\ (\text{len: }2a)$                           |
| Minor Axis   | $x=h\ (\text{len: }2b)$                           | $y=k\ (\text{len: }2b)$                           |
| Vertices     | $(h\pm a,0)$                                      | $(0,k\pm a)$                                      |
| Co-Vertices  | $(0,k\pm b)$                                      | $(h\pm b,0)$                                      |
| Directrices  | $x=h\pm \frac{a}{e}$                              | $y=k\pm \frac{a}{e}$                              |
| Foci         | $(h\pm ae, k)$                                    | $(h, k\pm ae)$                                    |

Extra Formulas

| Area                      | $(\pi)(ab)$                                                  |
| ------------------------- | ------------------------------------------------------------ |
| Perimeter Approximation   | $\pi(a+b)(1+\frac{p}{10+\sqrt{4-p}}), p=3(\frac{a-b}{a+b})^2$ |
| Lantus Recta Length       | $\frac{2b^2}{a}$                                             |
| Semi-lantus Rectum Length | $\frac{b^2}{a}$                                              |
| Parametric Form           | $x=h+a\cos(t),y=b+\sin(t)$                                   |



## Deduction

$\sqrt{(x-(-c))^2+y^2}+\sqrt{(x-(c))^2+y^2}=2a$

$\sqrt{(x+c)^2+y^2}+\sqrt{(x-c)^2+y^2}=2a$

$\sqrt{(x-c)^2+y^2}=2a-\sqrt{(x+c)^2+y^2}$

$(x-c)^2+y^2=4a^2-4a\sqrt{(x+c)^2+y^2}+((x+c)^2+y^2)$

$-4cx=4a^2-4a\sqrt{(x+c)^2+y^2}$

$4a\sqrt{(x+c)^2+y^2}=4a^2+4cx$

$\sqrt{a^2(x+c)^2+a^2y^2}=a^2+cx$

$a^2(x+c)^2+a^2y^2=(a^2+cx)^2$

$a^2x^2+2a^2cx+a^2c^2+a^2y^2=a^4+2a^2cx+c^2x^2$

$a^2x^2+a^2c^2+a^2y^2=a^4+c^2x^2$

$a^2x^2-c^2x^2+a^2y^2=a^4-a^2c^2$

$(a^2-c^2)x^2+a^2y^2=a^2(a^2-c^2)$

let $b=\sqrt{a^2-c^2}$, then

$b^2x^2+a^2y^2=a^2b^2$

$\frac{(x)^2}{a^2}+\frac{(y)^2}{b^2}=1,\ a>b$
