# Historia General de la Ciencia I
## Demostraciones del Teorema de Pitágoras
### Demostración Original

Es probable que la demostración pitagórica original se basara en las proporciones, y fuese parecida a la siguiente (extraída de _Explicar el mundo_, de S. Weinberg):

![image](https://github.com/edugrinan/philosophy/assets/118669606/d94e1ad2-f7d0-4d4f-94ea-4460bec1efc6)

Sea el triángulo APB rectángulo en el vértice P. Si trazamos la altura CP, dividimos el triángulo en otros dos triángulos que también son rectángulos (pues los dos ángulos en C son rectos). Se puede ver que los dos triángulos ACP y PCB son semejantes al original APB pues:
* Ambos tienen un ángulo recto.
* Ambos tienen un ángulo en común ($\alpha$).
* Por tanto, el tercer ángulo ($\beta$) debe ser igual en ambos triángulos (pues $\beta = 180° - 90° - \alpha$). 

Ahora, puesto que los tres ángulos son iguales, ambos triángulos son semejantes (es decir, las proporciones entre sus lados son idénticas). Lo mismo puede demostrarse sobre los triángulos APB y PCB. Así que los tres triángulos son semejantes.

Puesto que APB es semejante a ACP, se sigue, p.ej., que el cateto menor de ACP (AC) es a la hipotenusa de ACP (AP) como el cateto menor de APB (AP) es a la hipotenusa de APB (AB):

$$
\frac{AC}{AP} = \frac{AP}{AB} \Rightarrow AP^2 = AB*AC
$$

Y del mismo modo, puesto que APB es semejante a PCB, se sigue que:

$$
\frac{BC}{BP} = \frac{BP}{AB} \Rightarrow BP^2 = AB*BC
$$

Por tanto:

$$
AP^2 + BP^2 = AB * AC + AB * BC = AB * (AC + BC)
$$

Y usando que AC+BC = AB, se llega a que:

$$
AP^2 + BP^2 = AB^2 \blacksquare
$$

Esta demostración, como vemos, se basa en el uso de las proporciones, es decir, en operaciones aritméticas que realizamos usando fracciones. (Eso sí, ellos no lo harían con la notación algebraica empleada aquí, que fue desarrollada por los matemáticos árabes hacia el siglo X-XI dC, sino por métodos menos intuitivos).

Sin embargo, el descubrimiento de los números irracionales pudo hacer sospechosa esta demostración, ya que, si alguna de esas fracciones (p.ej., AC/AP) era irracional, eso implicaba que la proporción entre los lados AC y AP no podía expresarse como una fracción entre números naturales. Es lógico que los matemáticos griegos se preguntasen, entonces, si la demostración seguía siendo válida cuando dos lados de un triángulo eran irracionales entre sí.

Seguramente por este motivo, la demostración que da Euclides del teorema de Pitágoras (Proposición I.47 de los _Elementos_) no utiliza las proporciones entre los lados del triángulo, sino que se basa en un resultado geométrico distinto (la igualdad entre áreas de paralelogramos definidos entre las mismas dos rectas paralelas y con bases iguales), ya demostrado previamente en el libro I.

La teoría de las proporciones entre magnitudes racionales e irracionales no la desarrolla Euclides hasta el libro V de los Elementos. Una vez demostrados esos teoremas, se pueden aplicar a la demostración que hemos visto arriba para ver que es correcta, pero Euclides prefiere demostrar el teorema de Pitágoras a partir de los resultados más básicos posibles.

La prueba de Euclides procede mostrando que los siguientes triángulos tienen la misma área: AGC (rojo), AGB (verde), ACE (verde) (pues AB=AE; AG=AC, y el ángulo GAB = ángulo CAE = 90° + ángulo CAB), AKE (amarillo). Ahora AC2 = AGFC = 2 AGC y AKLE = 2 AKE, por tanto AC2 = AKLE.

Se demuestra igual que CB2 = KBDL. Y, como AB2 = AKLE + KBDL, se sigue que AB2 = AC2 + CB2
<img src="https://github.com/edugrinan/philosophy/assets/118669606/031acc54-dd74-4453-9bf6-57ce88e30f43" width="300">
