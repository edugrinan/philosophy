# Historia General de la Ciencia I
## La matemática griega desde la época de Euclides
### Introducción
Durante la primera mitad del siglo IV a. C., **Platón** convirtió el *quadrivium pitagórico* (aritmética, geometría, astronomía y música) en un elemento básico de la enseñanza de la Academia y formó en torno suyo una importante escuela de matemáticos entre la que se encontraban figuras como Eudoxo, Teeteto o Menecmo. Así mismo, Platón hizo de la matemática un elemento clave de su cosmovisión.

Su discípulo **Aristóteles de Estagira**, no daba primacía ontológica a los entes matemáticos, pero sí consideró la matemática como el paradigma de conocimiento científico, y estableció el ideal de conocimiento demostrativo en los *Segundos Analíticos* o *Analíticos Posteriores*. En estos, expone que toda demostración debe fundarse en principios ya conocidos que deben ser, o bien demostrables, o bien *primeros principios* (proposiciones auto-evidentes o tan fundamentales que no admiten demostración). También expresa que la demostración directa es siempre preferible a la reducción al absurdo, porque esta última no muestra la causa formal de lo demostrado.

### Los *Elementos* de Euclides
Apenas se sabe de Euclides que vivió en Alejandría entre los siglos IV y III a. C.; como tampoco se sabe con seguridad qué parte de sus *Elementos* es original y qué parte es una recopilación de obras anteriores. Sí parece que la ordenación sistemática y deductiva (axiomática) del conjunto se debe al propio Euclides. 

En los *Elementos* el autor distingue:
* Definiciones: "_un punto es lo que no tiene partes_", "_una línea recta es aquella que yace por igual respecto de los puntos que están en ella_".
* Nociones comunes: "_dos cosas iguales a una tercera son iguales entre sí_", "_el todo es mayor que la parte_".
* Postulados. Son 5:
  1. Dos puntos distintos cualesquiera determinan un segmento de recta.
  2. Un segmento de recta se puede extender indefinidamente en una línea recta.
  3. Se puede trazar una circunferencia dados un centro y un radio cualquiera.
  4. Todos los ángulos rectos son iguales entre sí.
  5. Si una línea recta corta a otras dos, de tal manera que la suma de los dos ángulos interiores del mismo lado sea menor que dos rectos, dichas dos rectas se cortan, al prolongarlas, por el lado en el que están los ángulos menores que dos rectos. [^1]

De esta forma, cada paso que se da en la obra se deduce de la combinación de alguno de estos principios, o de otra proposición que ya se ha demostrado.

*Nota.* Todos los libros (salvo los 8, 9, 12 y 13) contienen *definiciones*, pero sólo el Libro 1 contiene *nociones comunes* y *postulados*. La ausencia de postulados es especialmente extraña en los libros sobre aritmética, donde ninguna de sus proposiciones es derivada de los teoremas de libros anteriores.

Es interesante como en el Libro II se desarrolla una suerte de _álgebra geométrica_ que permite realizar operaciones para las que actualmente empleamos conceptos matemáticos entonces inexistentes como ecuaciones o variables. El Teorema de Pitágoras, sin embargo, es abordado en el **Libro I. Proposición 47**, antes de la presentación de esta, por lo que su demostración se basa en que dos triángulos o paralelogramos cuyas bases son iguales y están en las mismas paralelas tienen áreas iguales (proposición I.36).

Veamos algunos ejemplos de proposiciones:

**Libro VI. Proposición 13.** Dadas dos rectas, hallar una media proporcional.
> _Sea X la longitud de la recta AB, e Y la de la recta BC. Formamos la recta AC combinando X e Y, que será el diámetro de un semicírculo. Sobre el punto B elevamos una recta q ue intersecta con el círculo en el punto D. La recta BD tiene una longitud igual a la media proporcional (o geométrica) entre X e Y, es decir,_ $\sqrt {XY}$ .
<img src="https://github.com/edugrinan/philosophy/assets/118669606/0ea3a7cd-7708-4220-bf7a-d93354599caf" width="400">

_Prueba_: Usando el segundo Teorema de Tales, el ángulo D es recto. Como los triángulos ABD y DBC son semejantes, AB/BD es igual a BD/BC.

**Libro IX. Proposición 20.** Teorema de Euclides.
> _Hay más números primos que cualquier cantidad propuesta de números primos_

_Prueba. Reducción al absurdo_: Supongamos que hubiese una cantidad dada de números primos, $A, B, ..., C$. Sea D igual a $A\*B\*…\*C + 1$:
1. Si D es primo, ya se ha conseguido un número primo mayor que $A, B, ..., C$, en contra de lo que habíamos supuesto.
2. Si D no es primo, por la proposición VII.31, D será divisible por algún número primo. Pero no es divisible por ninguno de los A, B, ..., C (da resto 1). Luego D será divisible por algún número primo no comprendido en $A, B, ..., C$. Por lo tanto, $A, B, ..., C$ no pueden ser todos los números primos.

[^1]: Los matemáticos de la Antigüedad ya mostraron extrañeza por la diferencia cualitativa entre el 5º postulado y los otros 4, y pensaron que tenía que ser posible deducirlo a partir de los anteriores y de nociones básicas. No fue hasta el siglo XIX cuando se demostró su independencia, al construirse las *geometrías no euclídeas*, en las cuales ese postulado no se cumple.

### La matemática griega posterior a Euclides
Los siglos III y II a. C. constituyen la Edad de Oro de la matemática griega.

#### Apolonio
De Apolonio sólo ha sobrevivido su tratado sobre las Cónicas, que amplía y sistematiza los descubrimientos de Menecmo; fue él quien les dio los nombres de _elipse_, _parábola_ e _hipérbola_. También se deben a Apolonio los conceptos astronómicos de _excéntrica_, _epiciclo_ y _deferente_, que más tarde serán desarrollados por Hiparco y Ptolomeo.

#### Arquímedes
Arquímedes introdujo la noción de peso como una magnitud con propiedades matemáticas análogas a las de longitud y volumen, ampliando así el dominio de la matemática euclídea desde la geometría pura a la _mecánica_ (equilibrio de líneas y planos) y la _hidrostática_ (teoría de los cuerpos flotantes)

En la **mecánica** (_Sobre el equilibrio de los planos_), estudió el concepto de **centro de gravedad**: punto en el que una línea o figura se mantendría en equilibrio si estuviese apoyada en él. A partir de esta idea, demostró la ya conocida **ley de la palanca** y determinó los centros de gravedad de numerosas figuras y cuerpos geométricos.

En **hidrostática** (_Sobre los cuerpos flotantes_), formuló el **principio de Arquímedes**, considerando los pesos a los que están sometidos los volúmenes de un líquido en la esfera de la tierra, y sustituyendo mentalmente esos volúmenes por otros idénticos de materiales más o menos pesados.
