# Historia General de la Ciencia I
## Más sobre Pitágoras
### Teorema de Pitágoras

> _En un triángulo rectángulo, el cuadrado de la hipotenusa es igual a la suma de los cuadrados de los catetos_

Los babilonios conocían, ya hacia el 1800 aC, numerosas “ternas pitagóricas” (enteros a, b, c, tales que a² + b² = c², y que permiten, por tanto, construir triángulos rectángulos). Pero el teorema, como propiedad general de los triángulos rectángulos, no limitada a números enteros, sólo fue formulado y demostrado en Grecia.

Un aspecto interesante del teorema es que su validez no es intuitivamente obvia en absoluto, al contrario que la de los teoremas de Tales.

Es probable que la demostración pitagórica original se basara en las proporciones, y fuese parecida a la que ofrecemos a continuación (extraída de Explicar el mundo, de S. Weinberg):

![image](https://github.com/edugrinan/philosophy/assets/118669606/d94e1ad2-f7d0-4d4f-94ea-4460bec1efc6)

Sea el triángulo APB rectángulo en el vértice P. Si trazamos la altura CP, dividimos el triángulo en otros dos triángulos que también son rectángulos (pues los dos ángulos en C son rectos). Podemos demostrar que los dos triángulos ACP y PCB son semejantes al triángulo original APB. Para ello:
-ambos tienen un ángulo recto
-ambos tienen un ángulo en común (α)
-por tanto, el tercer ángulo (β) debe ser igual en ambos triángulos (pues β = 180° - 90° - α).

Puesto que los tres ángulos son iguales, ambos triángulos son semejantes (es decir, las proporciones entre sus lados son idénticas). Lo mismo puede demostrarse sobre los triángulos APB y PCB. Así que los tres triángulos son semejantes.

Puesto que APB es semejante a ACP, se sigue, p.ej., que el cateto menor de ACP (AC) es a la hipotenusa de ACP (AP) como el cateto menor de APB (AP) es a la hipotenusa de APB (AB):

AC/AP = AP/AB

Y del mismo modo, puesto que APB es semejante a PCB, se sigue que:

BC/BP = BP/AB

De AC/AP = AP/AB, se sigue:

AP2 = ABxAC

De BC/BP = BP/AB, se sigue:

BP2 = ABxBC

Por tanto:

AP2 + BP2 = (ABxAC) + (ABxBC)
	= AB (AC + BC)

¡Pero AC+BC = AB! Por tanto:

AP2 + BP2 = AB2 

Esta demostración, como vemos, se basa en el uso de las proporciones, es decir, en operaciones aritméticas que realizamos usando fracciones. (Eso sí, ellos no lo harían con la notación algebraica empleada aquí, que fue desarrollada por los matemáticos árabes hacia el siglo X-XI dC, sino por métodos menos intuitivos).

El descubrimiento de los números irracionales pudo hacer sospechosa esta demostración, ya que, si alguna de esas fracciones (p.ej., AC/AP) era irracional, eso implicaba que la proporción entre los lados AC y AP no podía expresarse como una fracción entre números naturales.

Es lógico que los matemáticos griegos se preguntasen, entonces, si la demostración seguía siendo válida cuando dos lados de un triángulo eran irracionales entre sí. 

Seguramente por este motivo, la demostración que da Euclides del teorema de Pitágoras (prop. 47, libro I de los Elementos) no utiliza las proporciones entre los lados del triángulo, sino que se basa en un resultado geométrico distinto (la igualdad entre áreas de paralelogramos definidos entre las mismas dos rectas paralelas y con bases iguales), ya demostrado previamente en el libro I.

La teoría de las proporciones entre magnitudes racionales e irracionales no la desarrolla Euclides hasta el libro V de los Elementos. Una vez demostrados esos teoremas, se pueden aplicar a la demostración que hemos visto arriba para ver que es correcta, pero Euclides prefiere demostrar el teorema de Pitágoras a partir de los resultados más básicos posibles.

La prueba de Euclides procede mostrando que los siguientes triángulos tienen la misma área: AGC (rojo), AGB (verde), ACE (verde) (pues AB=AE; AG=AC, y el ángulo GAB = ángulo CAE = 90° + ángulo CAB), AKE (amarillo). Ahora AC2 = AGFC = 2 AGC y AKLE = 2 AKE, por tanto AC2 = AKLE.

Se demuestra igual que CB2 = KBDL. Y, como AB2 = AKLE + KBDL, se sigue que AB2 = AC2 + CB2

![image](https://github.com/edugrinan/philosophy/assets/118669606/031acc54-dd74-4453-9bf6-57ce88e30f43)
