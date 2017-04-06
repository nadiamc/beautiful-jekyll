---
layout: post
title: Práctica de álgebra I
---

# RELACIONES

### Ejercicio 1
Sea A un conjunto cuyos elementos son 1, 2 y 3. Sea R una relación definida como todos aquellos pares ordenados (A; B) pertenecientes al producto cartesiano entre el conjunto de partes de A tales que A está contenido en B.

Probar que esta releción es una relación de orden.

#### Reflexividad:
Para afirmar que esta relación es reflexiva debemos ver que cada uno de los elementos del conjunto de partes de A
está relacionado con sí mismo. Es decir, si tomo un elemento H del conjunto de partes de A, tengo que ver que H esté relacionado con H; y, en este caso, por definición de esta relación, tengo que ver que H esté contenido en H.

Por propiedad de conjuntos, se sabe que cualquiera sea el conjunto A, siempre se cumple que A está contenido en A.

Por lo tanto, es cierto decir que H está contenido en H. O sea, la relación tratada es reflexiva.

#### Antisimetría:
Esta relación es antisimétrica si al tomar dos elementos del conjunto de partes de A, llamados H y T, tales que a T está contenido en H y H está contenido en T se implica que T es igual a H.

Veamos si es así. Tomamos H y T, dos elemento del conjunto de partes de A. Si H está relacionado con T, se tiene que H está contenido en T. Por otra parte, si T está relacionado con H, se tiene que T está contenido en H. Ahora, observando y recordando que la defición de igualdad de conjuntos, podemos inferir que el conjunto H es el mismo conjunto T. Por lo tanto, esta relación es antisimétrica.

#### Transitividad:
Para ver que es transitiva, tomemos tres elementos del conjunto de partes de A llamados Q, W, y Z, tales que Q está relacionado con W y, a su vez, W está relacionado con Z. De esto último, podemos deducir que Q está contenido en W y que W está contenido en Z.

Observando y recordando que la inclusión es una operación de conjuntos que posee la propiedad de transitividad, podemos inferir que entonces T está contenido en el conjunto Z.

Por lo tanto, esta relación es transitiva.

Se ha probado que la relación mencionada es una relación de orden.

### Ejercicio 2
Sea A el conjunto de los números naturales. Sea R una relación en A definida como todos los pares ordenado (a, b) tales que a es mayor oo giual a b.
Probar que es una relación de orden.

### Ejercicio 3
Sea A el conjunto de los números naturales. Sea R una relación en el conjunto de partes de A definida como todos los pares ordenados (A; B) tales que el conjunto llamado K que tiene a los elementos 2, 7 y 9 está contenido en el complemento de la diferencia simétrica entre A y B.
Probar que es una relación de equivalencia.

# FUNCIONES

### Definición
Una función de A en B es una relación R que está incluída en el producto cartesiano entre A y B tal
que para todo elemento del conjunto A existe un único elemento del conjunto B.

### Ejercicio 1
Sea R una relación definida por todos los pares ordenados (a, b), pertenecientes al producto cartesiano entre el conjunto de los números naturales, tales que a es igual al doble de b.
Decidir si R es una función.

#### Resolución
R no es una función porque existe al menos un elemento del conjunto de los números naturales, por ejemplo el 5, para el cuál no exite un b perteneciente a los naturales tal que 5 sea igual al doble de b. o sea, en otras palabras, no exite un b que al ser multiplicado por dos sea igual al 5. (5 no está relacionado con b perteneciente a los naturales)

### Ejercicio 2
Sea A el conjunto de todos los números naturales mayores o iguales a cero. Y sea B el conjunto del todos los números reales. Se define la relación R como el conjunto de todos los pares ordenados (a, b) pertencientes a AxB tales que a es igual al cuadrado de b.
Decidir si R es función.

#### Resolución
Para todos los a pertenecientes a A, existe un único b real talque al cuadrado sea igual a "a"???
No, si tomamos un a igual a 1, vemos que existen dos números reales tales que sus cuadrados son iguales a 1. Dichos dos números reales son el 1 y el -1. Por lo tanto, esta relación no es una función.

### Ejercicio 3
Sea A y B dos conjuntos cuyos elementos son los números reales mayores o iguales a cero, se define la relación R como los pares ordenados pertenecientes a AxB tals que a es igual al cuadrado de b.

#### Resolución

Veamos que esta relación sí es una función.

Cómo nos damos cuenta?
Debemos ver si R cumple con la definición de función. Para ello debemos ver que como a es igual al cuadrado de b, entonces al aplicar la raíz cuadrada en ambas partes de la igualdad, tenemos que la raíz cuadrada de a es igual a la raíz cuadrada de b al cuadrado.

 Cuáles son los que tales que la raíz cuadrada de su cuadrado es igual a la raíz cuadrada de a??
En primer lugar debemos notar que b podría ser cualquier valor positivo o negativo, ya que si b es negatiivo o positivo su vuadrado será el mismo tenemos que tener cuidado.

Debido a la última oración, es que se usa el módulo; es decir, que la raíz cuadrada de a es igual al módulo de b. Y si el módulo de b es igual a la raíz cuadrada de a, entonces tenemos dos posibles valores para b, raíz cuadrada negativa de a ó raíz cuadrada positiva de a.

Como sabemos que a pertenece a un conjunto no negativo, entonces no hace falta ver el signo de las dos posibles de b, o sea, valores de la raíz cuadrada negativa de a y raíz cuadrada positiva de a .

Entonces, recordando que b también es un cto. con valores no negativos. Por lo tanto, b es no negativo y de ésto se deduce que b es igual a la raíz cuadrada positiva de a.

### Definición
La imagen de una función f que va desde A hasta B es el conjunto de todos los b pertenecientes a tales que existe al menos un k perteneciente a A tal que b es igual a la imagen de a.

##### Definición hecha por mi
La imagen de una función f que va desde A hasta B, una relación que está incluída en AxB, es el conjunto de todos los b pertenecientes a B que están relacionados con al menos un a perteneciente al conjunto A.


### Definición de función inyectiva
Es aquella función que cumple con la siguiente implicación: si la imagen de a es igual a la imagen de a', entonces a es igual a a'.

También se puede definir con una implición equivalente llamada contrarecíproca: si a es distinto a a', entonces la imagen de a es distinta a la imagen de a'.

### Definición de función subreyectiva
Es aquella función cuyo conjunto imagen es igual al codominio de la función en cuestión.

### Definición de función biyectiva
Es aquella función que es inyectiva y sobreyectiva.

### Ejercicio 1
Decidir si las siguientes funciones son funciones inyectivas, sobreyectivas o biyectivas.

### a)
Si f es una función de reales en reales definida como f(x) igual al cuadrado de x.

No es inyectiva porque tanto 1 como -1 tienen la misma imagen.
No es sobreyectiva porque la imagen es un conjunto distinto al codominio. O sea, hay elmentos del codominio que no están en la imagen.
Como no es inyectiva y sobreyectiva, tampoco es biyectiva.

### b)
Si f es una función de números naturales en números naturales definida como f(x) igual al cuadrado de x.

Veamos si esta función es inyectiva. Recordemos que para ser inyectiva debe suceder que si dos elelmentos tienen la misma imagen, entonces estamos hablando del mismo elemento. Si tomo dos elementos, n y m, con la misma imagen, entonces f(n) es igual a f(m). Esto último es equivalente a decir que entonces el cuadrado de n es igual al cuadrado de m. entonces, al aplicar la función raíz cuadrada en ambas partes de la igualdad, tenemos que el módulo de m es igual al módulo de n; pero, como estamos tratando con números naturales, tenemos que n es igual a m. Por lo tanto, esta función es inyectiva.

Es sobreyectiva? para saberlo, debemos ver si se cumple la definición de sobreyectividad de una función. Recordemos que una función es sobreyectiva si y solo si el conjunto imagen es igual al conjunto del codominio. Entonces, el conjunto imagen es igual al conjunto de los números naturales?

Esta pregunta puede formularse de otra forma: para todo m perteneciente al conjunto de números naturales del dominio, existe al menos un n perteneciente al conjunto de los números naturales del dominio tal que la imagen de n es m?

Bueno, si tomamos al elemento 3 del codominio, veamos si existe al menos un n del dominio tal que la imagen de n es 3. Supongamos que sí existe tal n, entonces la imagen de ese n es 3. o sea, f(n) es igual  3; lo cual, según la definición de f, n al cuadrado es igual a 3. Y si estos dos valores son iguales entonces la raíz cuadrada de ambos también lo es.

Como la raíz cuadrada de n al cuadrado es el módulo de n que, a su vez, es igual a n porque n es un número natural;  entonces n es igual a la raíz cuadrada de 3. Pero... n es un número natural y la raíz de 3 no lo es!! Entonces... bomba! albsurdo! O sea, es contradictorio decir que n es igual a la raíz de 3.

Hemos entontrado un elemento del dominio que no pertenece al conjunto imagen, entonces estos conjuntos no son iguales, lo cuál indica que no se cumple la definición de función sobreyectiva, o sea, esta función no es sobreyectiva.


### c)
Si f es una función de números naturales a números naturales definida como n+1 para todo n impar, y n-1 para todo n par.

Queremos ver si es inyectiva, para ver si lo es debemos ver que la imagen de dos elementos implica que esos dos elementos son iguales.

Pero como la imagen de cualquier elemento del dominio, según la definición de f, depende de su paridad, entonces debemos considerar las combinaciones de pares de números que supondremos con igual imagen y ver si se deduce que se trata del mismo elemento.

Los casos serían los siguientes:

1) dos pares
2) dos impares
3) el primer elemento elegido par y el otro impar
4) el primer elemento impar y el otro par

Si en cada caso mencionado se cumple la definición de función inyectiva, entonces podríamos concluír que la función es inyectiva. Repito, para tooodos los casos. Ya que si no se cumple para alguno, entonces quiere decir que aunque dos elementos tengan la misma imagen no implica que ambos elementos sean el mismo.

Caso 1. Si tomamos dos elementos pares del dominio, llamados m y n, y tenemos que la imagen de m es igual a la imagen de n entonces n-1 es igual a m-1 y si sumamos un uno a ambos números, es equivalente a decir que n es igual a m.

Caso 2. Si tomamos dos elementos impares del dominio, llamados l y k, y tenemos que la imagen de l es igual a la imagen de k; o sea, l+1 es igual a k+1 y si restamos uno a ambos números llegamos a que l es igual a k.

Caso 3. Tomo un elemento par y otro elemento impar del dominio a los cuales llamaré u y t respectivamente. Si u es par, entonces su imagen es u-1, y si t es impar, su imagen es t+1. Como suponemos que las imagenes de u y t son iguales, entonces u-1 es igual a t+1. De esta última igualdad, al sumar 1 a ambos números deducimos que u es igual t+2.

Si recordamos que t es impar entonces t es igual a 2k+1 con k natural. Y si le sumamos 2 a t, tenemos que  2k+1+2 es igual a 2k+2+1, un número impar. Pero dijimos que u es par, no impar. Entonces tenemos una contradicción que proviene de suponer que dos elementos con distinta paridad tienen igual imagen, lo cual es falso.

Por lo tanto esta función no es inyectiva. Ya que, recordemos que la imagen de dos números distintos con distinta paridad) tienen distinta imagen. fin!!

Veamos si es sobreyectiva.


Para ver si es sobreyectiva, debemos ver que para todo k perteneciente al codominio existe n perteneciente al dominio tal que f(n) es igual a k.

Pero como la imagen depende de la paridad de n, tendremos que analizar por casos.
Antes de hcer el analisis considero necesario observar la función para tomar nota de su comportamiento.

Durante la observación tratemos de conjeturar el conjunto imagen.
Veamos que, en principio, la imagen de un elemento del codominio depende de la paridad del elemento en cuestión.

Si n perteneciente a los naturales es par, entonces la imagen me dará un número impar.
Si n perteneciente a los naturales es impar, entonces la imagen me darpa un número par.

De esto podemos conjeturar que la imagen de todos lo números pares del dominio son los números impares del codominio y que la imagen de todos lo números impares del dominio son los números pares del codominio. Y como la unión de pares e impares pertenecientes al codominio es todo el codominio, o sea, es todo el conjunto de los número naturales (ya que la imagen de 1 es 2, la imagen de 2 es 1, la imagen de 3 es 4, la imagen de 4 es 3....podemos conjeturar que la imagen es el conjunto de todos los números naturales.

Vamos a probarlo. Cómo hago?
Teniendo en cuenta la definición de dunción sobreyectiva, basta ver que la imagen es igual al codominio. Y por definición de la imagen, es lo mismo a querer ver que para todo k perteneciente al codominio existe al menos un n perteneciente al dominio tal que la imagen de n es igual a k.

Si k pertenece al codominio, entonces k pertenece a la unión de los números pares e impares.

Como la imagen depende de la paridad de f, entonces según las observaciones realizadas anteriormente debo ver si efectivamente la imagen de los pares del dominio es el conjunto de los impares del codominio y, a su vez, la imagen de los impares del dominio es el conjunto de los pares de codominio.


En este paso, pienso que hay dos formas de probarlo. Enunciaré a ambas a continuación.

##### Forma I:
Ver si existe n par tal que la imagen de n es igual a k impar.
Si k es impar y n par, entonces la imagen de n es n-1, un número impar.
Si k es par y n impar, entonces la imagen de n es n+1, un número par.

y como la unión entre los números pares e impares es igual al codominio, entonces la función es sobreyectiva.

##### Forma II:
Ver si existe n del dominio tal que su imagen es k impar.
Según la conjetura realizada anteriormente, la imagen de k impar le corresponde a algún n par, quiero ver si existe tal n.
Entonces, si tomo n par, tomo n igual a k+1 (un número impar mas 1 es un número par), esto último es equivalente a decir que la imagen de k+1 es igual a k+1-1 (por def. de la función). Por último, lo anterior es equivalente a decir que la imagen de tal n es igal a k.
Por lo tanto existe n del dominio tal que la imagen es k impar.

Ver si axiste n del dominio tal que su iamgen es k par.
También, según la conjetura realizada anteriormente, la imagen de k par le corresponde a algún n impar, quiero ver si existe tal n.
Entonces, si tomo n impar, tomo n igual k-1

nota: me conviene que sea k-1 porque al aplicar def. de f tendriamos la imagen de n igual a k , como queremos. Si tomaramos k+1 , que también es impar, no tendríamos la imagen igualda a k+2 que sería cualquier k del codominio mas dos unidades. O sea, no representaria a todos los pares del codominio ya que k comienza a tomar valores naturales y el par mas pequeño sería 4 (por lo que habríamos omitido al 2, un elemento que debería estar porque es par y natural).

Terminando con lo anterior, al tomar n igual a k-1 y evaluarlo en f tenemos que su imagen es k-1+1, o sea igual a k par como queríamos.
Port lo tanto existen n pertenecientes al dominio tales que la imagen de estos me dan todos los números k apres de codominio.

Por último, repitiendo lo que escribí anteriormente, como la unión de los impares naturales y pares naturles es igual al conjunto del codominio, podemos afirmar que la función en cuestión es sobreyectiva.


amo razonar!


Finalmente afirmamos que esta función es biyectiva porque es sobreyectiva e inyectiva.


### d)

sea f con dominio igual al cto. de los número naturales unión el cero y codominio igual al cto. de los enteros.

Defino f según la paridad de los elementos n del dominio. la imagen de los n pares será la mitad de n y la imagen de los n imapares será el negativo de la mitad de n+1.

Sea g una función con dominio igual al cto. de números enteros y codominio igual al cto. de los números naturales.

Defino g según la negatividad y no negatividad de los n elementos del dominio. Así, los elementos negativos del dominio tienen la imagen de el negativo del doble de n más una unidad, o sea, -2*n-1 que es igual a -(2*n+1). Y la imagen de los n no negativos es igual a el doble de n.

Calcular las composiciones de f compuesta con g y g compuesta con f.

Despues de hacer un razonamiento que alguna vez escribiré, me queda que gof es igual a n, para todo n natural. Y que fog es igual a n para todo n entero.

De aquí se realiza una operación que me dice que albas funciones parecen iguales pero en realidad son distintas ya que ambas son la función identidad de lugares distintos, o sea, de dominios y codominios distintos. También, si graficamos la función, notaremos la diferencia.

## Proposición
Sea f de A en B, será una función biyectiva si y solo si  existe una función g de B en A. tal que fog es igual a la identidad de B  y gof es igual a la identidad de A. En dicho caso, g es única y se nota como f^(-1), y se llama la inversa de f.

### e)
Defino una relación.
Sea A un cto. decimos que A está relacionado con B si y solo si existe biyección (una función biyectiva llamada f) de A en B. Es decir dos conjuntos están relacionados si y solo si existe una función biyectiva que tenga dominio A y codominio B.

Probar que la relación es una relación de equivalencia.

Veamos que es reflexiva. Si tomo cualquier conjunto A, notemos que para cada uno de ellos existe una función llamada identidad de A que tiene dominio en A y codominio en A y esta función es biyectiva; entonces, la relación es reflexiva.

Veamos si es simétrica. Si cto. A está relacionado con B, entonces, por definición de la relación, existe una función biyectiva de A en B. Además, según la proposición dada, por ser f una función biyectiva existe una función inversa llamada f^(-1) con dominio B y codominio A  tal que fog es igual a la identidad de B  y gof es igual a la identidad de A y por ello, también es biyectiva. De esto último se deduce que el cto. B está relacionado con A. Por lo tanto, la relación también es simétrica.

Veamos si es transitiva. Si tomo tres conjuntos A, B y C tales que A está relacionado con B y B está relacionado con C, entonces existe una función f de A en B que es biyectiva y una función g de B en C que también es biyectiva. Queremos ver que existe una biyección de A en C.


Teniendo en cuenta lo que queremos ver, debemos prestar atención, otra vez, a la proposición de funciones biyectivas. También debemos pensar en cómo sería lo que estamos buscando ver.

Como quiero una función que va de A en C, tenemos que conjeturar que la función buscada es la composición de las funciones f y g en algún orden. Dicho orden, debe elegirse teniendo en cuenta cuál es el cto. que queremos como dominio y cuál queremos como codominio.

 Como queremos que el dominio sea A y el codominio sea C, entonces de esto deducimos que la composición buscada empezaría a tomar elementos de A, o sea, que la composición empezaría aplicando la función f ya que ésta tiene como dominio al cto. A. Luego, la función compuesta buscada es gof.

 Entonces, podemos afirmar que existe la biyección (ya que la composición de biyecciones es otra biyección) llamada gof de A en C .

 Por lo tanto, podemos afirmar que la relación es una relación de equivalencia.

### f)
Ver si las siguentes relaciones son biyecciones o no lo son
Según la definición de relación que puse antes,

El cto J será igual al J igual al cto. de los naturales unidos al cero está relacionado con el conjunto O igual al cto. de los números enteros??
Existe al menos una biyección de J en O?

Sí! Ya que existe al menos una función biyectiva de J en O. Por ejemplo, la función de J en O cuya f(x) es igual a x/2 para los x pares y f(x) es igual a (-x-1)(1/2)  para los x impares.

### disgresión

Hay un tema con el maldito vocabulario.
Se usa el término biyección para referirse a que una función es biyectiva.
Se dice biyección a la función biyectiva.
En el ejercicio anterior, cuando probamos que la relación era transitiva, podríamos haberlo escrito así: si A está relacionado con B, entonces f de A en B es biyección. O sea, que la función f de A en B es una función biyectiva.


### ejercicios
Decir si los siguientes pares de conjuntos están relacionados o no, según la definción de relación que dice que dos ctos. A y B están relacionados si y solo si existe al menos una biyección de A en B. o sea, si existe una función de A en B que es biyectiva.

#### 1)
El cto. llamado H igual al cto. de los naturales unidos al cero está relacionado con el conjunto llamado G igual al cto. de los números enteros?
es lo mismo que preguntarse,
y..cuando estaban relacionados estos dos ctos. según la definición de la relación?
Estos ctos. están relacionados si existe al menos una biyección de H en G.
Existe tal biyección?
si! y podemos nombrar una. Me refiero a la funciones f del inciso d.

#### 2)
El cto. de los reales está relacionado con el cto. (-1, 1)?
implica que existe al menos una biyección de reales a (-1, 1)?
Me dicen que sí, pero no sé dar ningún ejemplo (TERMINAR)

#### 3)
(-1, 1) está relacionado con (cero, 1)?
Existe al menos un biyección de (-1, 1) a (cero, 1)?
También me dicen que sí, pero no sé dar ningún ejemplo (TERMINAR)

#### 4)
(cero, 1) está relacionado con (-1, 1)?
existe al menos una biyección de (cero, 1) a (-1, 1)?
También me dicen que sí,  y un ejemplo es la función g de (cero, 1) a (-1, 1) definida como
2*(x-1/2)  para todo x perteneciente al dominio.

#### 5)
el cto. de los número naturales está relacionado con los reales?
Existe al menos una biyección de naturales a reales?
qué quiere decir que un cto. no esté relacionado con otro, según la definición de R?
Recordemos que A está relacionado con B si y solo si  existe al menos una biyección de A en B.

´´´
Razonemos para deducir cómo negar la doble implicación.
Tengamos en cuenta que la doble implicación es una conjunción de proposiciones condicionales.
O sea, en nuestro caso, tenemos que  
(Si A está relacionado con B, entonces existe al menos una biyección de A en B) y (Si existe al menos una biyección de A en B, entonces A está relacionado con B).

Como queremos negar la bicondicionalidad. para qué? para saber qué debe suceder para que dos elementos no estén relacionados, según la definición de la relación con la que estamos tratando.

Para negar la bicondicionalidad, debemos negar a la expresión equivalente escrita anteriormente.
Al hacerlo, vemos que llegamos a la expresión que, en caso de ser verdadera, se debe cumplir una o dos de las siguientes proposiciones:


Antes de eso, recordemos como negar proposiciones con cuantificadores.

Cuantificador para todo:

Si digo que para todo elemento de un cto. existe su inverso, la negación es equivalente a decir que existe al menos un elemento para el cual no existe su inverso.

Ejemplo: si me dicen que todas las personas de mi familia tienen pelo negro, la negación es equivalente a decir que existe  al menos un integrante de mi familia que no tenga el pelo negro, que tenga el pelo de cualquier otro color.


Cuantificador existe al menos uno:

Si digo que existe al menos un número real con forma de choclo, la negación es equivalente a decir que  todos los número reales no tienen no tienen forma de choclo.

Ejemplo: si me dicen que existe  al menos una persona en mi familia que tiene el pelo rubio, para probar que no es cierto, o sea, para negarlo, basta mostrar que todas personas de mi familia tienen el pelo negro.
todos los número

 Todo esto vino de querer ver que el cto. de los naturales no está relacionado con el cto. de los reales (según la definición de la relación en cuestión). Al tener en cuenta que el conjunto de los naturales está incluído pero no es igual al cto. de los reales, podemos conjeturar que puede ser inyectiva (ya que para todos los elementos distintos del dominio pueden tener distinta imagen), pero no puede ser sobreyectiva ya que la imagen de la función en cuestión puede ser a lo sumo igual al cto. de los número naturales (esto se ve porque la cantidad de elementos de la imagen más grande que podemos armar jamás podría ser igual al cto. de los reales).

 Como queremos ver que el cto. de los naturales no está relacionado con el cto. de los reales, entonces queremos que no se cumple la definición de relación. Lo que es lo mismo que querer que la doble implicación sea falsa (para los ctos. mencionados).
 Si la doble implicación es falsa, la definición de relación no se cumple? no.


 Disgresión:

 En realidad, la definición de relación nos habla de suposiciones, suponer que pasan ciertas cosas que al ser verderas implican otras cosas y al ser falsas, de deduce cualquier cosa verdadera o falsa.

 Si analizo la definición de relación, veo que me si dos elementos están relacionados, entonces existe biyección  y si existe biyección entre dos elementos, dichos elementos están relacionados.

Para probar que dos elementos no están relacionados, qué tengo que hacer?
Debo probar que no se cumple la doble implicación, lo que es lo mismo que probar la veracidad de solo una de las implicaciones o probar que ninguna de las formulas es verdadera.

O sea, debo ver que es verdadero que ARB implique existencia de biyección ó que es verdadera
la existencia de biyección implique ARB   ó ver que ninguna de las formulas es verdadera.
Esto me indicaría que la bicondicionalidad no se cumple. Por lo tanto los ctos. no estarían relacionados.

Y, según reglas lógicas, probar lo anterior es lo mismo que probar la veracidad de solo alguna de las siguiente fórmulas (proposiciones compuestas) y que tratamos con una disyunción exclusiva (ya que el hecho de que ambas sean verdaderas, implica una contradicción):


##### formula1
que ARB y que no exista biyección de A en B

##### formula2
que exista tal biyección y que A no esté relacionado con B











nota: decir que "dos elementos están relacionados" es lo mismo que decir que existe el par ordenado (N, R)

Entonces, probar que los conjuntos mencionados no están relacionados, se reduce a probar que alguna de las fórmulas dadas sea verdadera, o lo que es lo mismo, que la negación de alguna es falsa.

cuál pruebo? cómo lo hago?
EN primer lugar, debemos notar que queremos probar conjunciones; y, para que dichas conjunciones sean verdaderas, debo ver que las proposiciones que componen dichas conjunciones son verdaderas.

Con respecto a la primer fórmula, debo probar que si ambas proposiciones son verdaderas entonces llegamos a expresiones equivalentes verdaderas.

REcordemos que queremos probar que N no está relacionado con R, o sea que todas las funciones de N en R, ninguna es biyectiva.

Entonces si existe el par ordenado (N, R) y no existe función biyectiva de N en R, quiere decir que no existe función de N en R que sea inyectiva y sobreyectiva a la vez. Notemos que tenemos otra conjunción. Pero en este caso ésta está negada. Por ello, decir que no existe biyección de N en R, es equivalente a decir que no existe función de N en R tal que función inyectiva y sobreyectiva lo es lo mismo que decir que todas las funciones de N en R son no inyectivas o son no sobreyectivas lo que es una disyunción inclusiva.

Como dije, debo ver que es verdad que todas las funciones de  N en R son no inyectivas o no sobreyectivas.

Como estamos tratando con una disyunción inclusiva, entonces para que dicha disyunción sea verdadera me basta con que sea verdadera alguna de las siguientes proposiciones compuestas:

##### proposición compuesta 1
Todas las funciones de N en R no son inyectivas ni sobreyectivas.
##### proposición compuesta 2
Todas las funciones de N en R son inyectivas y no son sobreyectivas.
##### proposición compuesta 3
Todas las funciones de N en R son no inyectivas y son sobreyectivas.

Acabo de declarar cuales serìan los posibles casos para que la disyunción nombrada sea verdadera.

la ultima proposiciòn me parece una pelotudez tremenda, algo está mal.
´´´
Voy a poner la resolución del profesor. Pero para mi hay otra forma de resolverlo. Ahora no me queda tiempo para seguir pensando. Tengo que seguir con otra cosa. PEro ya volveré problema, te resolveré.

El profesor usó otros datos para poder resolverlo facilmente, pero ¿Qué pasa si tales datos no los tengo? ¿No sería mejor poder deducir la solución del problema sin tener esos datos a mano? Eso es lo quiero hacer, y por falta de tiempo, no lo haré ahora. PEro  como dije, lo haré el el futuro.

Solución: Como sabemos que el conjunto  de los reales está relacionado con el intervalo abierto desde el cero al uno, y también sabemos que la relación es simétrica por ser una relación de equivalencia, podemos decir que el intervalo abierto desde el cero al uno está relacionado con el conjunto de los números reales.

Entonces, si conseguimos probar que el conjunto de los números naturales está relacionado con el intervalo abierto desde el cero al uno, por tratarse de una relación transitiva por ser una relación de equivalencia, podríamos afirmar que el conjunto de los números naturales está relacionado con el conjunto de los números reales.

Para conseguir probarlo, supongamos que existe al menos una función biyectiva desde los naturales al intervalo abierto mencionado.

Suponer que es biyectiva es suponer que es inyectiva y sobreyectiva, veamos primero que es sobreyectiva

(TERMINAR)

Durante el desarrollo llegamos a una igualdad falsa, a una contradicción. Entonces, al no ser sobreyectiva vemos que no es biyectiva y , por ende, fué un error haber supuesto que existe al menos una función biyectiva de los naturales al intervalo abierto del cero al uno. Por lo tanto, todas las funciones de los naturales al intervalo abierto no son biyectivas.


# INDUCCIòN

### ejercicios

### ejercicio1

Tenemos que 1 al cubo es igual a 1 al cuadrado
Tenemos que 1 al cubo más dos al cubo es igual a 9 igual a 3 al cuadrado
Tenemos que 1 al cubo más dos al cubo más 3 al cubo es igual a 36 igual a 6 al cuadrado.
Tenemos, tenemos tenemos tenemos

Entonces, realizamos la conjetura que dice que si sumo 1 al cubo más 2 al cubo más todos los demás naturales mayores a dos, hasta llegar a n al cubo, podemos decir que es igual a la suma de todos esos n elevados al cuadrado.

Lo que acabamos de hacer es una conjetura, o sea, no se algo que se puede tomar como verdadero para todo n. Para afirmar que la conjetura es válida para todos los números naturales, debo probarlo.

Para probarlo, usaremos el principio de inducción.

Este principio me dice que cualquier conjunto inductivo cumple con dos condiciones.

Nosotros tenemos una conjetura que puede llamarse proposición y ésta conjetura parece ser cierta solo para los número naturales porque la afirmamos sobre ellos.. Queremos ver si dicha proposición es verdadera para cada uno de los elementos pertenecientes al conjunto de los números naturales. Entonces, queremos ver si es cierta para el conjunto inductivo de los números naturales.

Como queremos ver si es cierta para un conjunto inductivo, queremos que las condiciones que cumple un cojunto inductivo las cumpla el conjunto de valores que hacen verdera tal proposición.

En otras palabras, nosotros tenemos una conjetura, queremos ver si el conjunto de valores que hacen verdadera la proposición es igual al conjunto de los números naturales, un conjunto inductivo. y por ser un conjunto inductivo, éste cumple dos condiciones, entonces en vez de probar número por número para ver si con cada uno de ellos la proposición es verdera,  tenemos la estrategia de ver si los valores que hacer verdadera la proposición cumplen con la condición de conjunto inductivo.

Dichas condiciones son:
##### 1)
Que el elemento 1 sea parte del conjunto que hace verdera a la proposición. O sea, que 1  haga a la proposición verdadera.

##### 2)
Que del hecho de que la proposición sea verdaera para algún elemento k natural se deduzca que que la proposición es verdera para el siguiente, o sea, k+1.


Sigamos con el ejercicio. Porque queremos ver si el cto. de elementos que hacen verdadera a la proposición es el cto. de los naturales, un cto. inductivo, debemos ver si las condiciones que caracterizan a un conjunto inductivo son son cumplidas por el cto. de elementos que hacen verdadera la paroposición.

Condición 1, llamado caso base.
Veamos que la proposición evaluada con n igual a 1 es verdadera.

Condición 2, llamado caso inductivo.
Veamos si al suponer que la proposición es verdera con un elemento k natural se deduce que es verdadera para k+1 natural.

Si suponemos que es cierto que p(n) es verdadera para k natural entonces es cierto que 1 al cubo más 2 al cubo más todos los naturales hasta k al cubo es igual a la suma de los k elementos al cuadrado.

Nosotros queremos ver que de la igualdad anterior podemos deducir que es cierto que la suma de los k+1 elementos cada uno elevados al cubo es igual a la suma de los k+1 elementos al cuadrado.

Cómo vemos esto? cómo podemos razonar para solucionar este problema?
Primero notemos que queremos probar que dos cosas son iguales, por lo tanto debemos tomar una de las partes de la igualdad y a ella transformarla en la otra parte; o sea, podemos tomar la parte derecha de la igualdad y transformarla en la parte de la izquierda ó podemos tomar la parte izquierda de la igualdad y transformarla en la parte de la derecha. Aclaro que lo haré de las dos formas.
O bien, podemos tomar la igualdad que queremos probar y de ella llegar a otra igualdad que es verdadera o una igualdad mas  facil de probar. Lo cual también haré.


Forma 1.
Tomaremos la parte derecha y la tranformaremos en la parte de la izquierda.

##### Disgresión
La palabra "transformar" es utilizada para hacer notar que al ser dos cosas iguales, entonces al sufrir operaciones que no modifiquen su valor debe tomar otro aspecto pero sigue teniendo el mismo valor.

En este caso, la parte derecha de la igualdad que queremos probar es la suma de k+1 elementos elevados al cuadrado. De esa expresión, debemos llegar a que es igual a la suma de uno hasta k+1 cada uno elevado al cuadrado.

cómo seguimos? qué podemos hacer para poder resolver esto? qué debo pensar? qué debo preguntar?

Mi recomendación para empezar es mirar fijamente la igualdad y tratemos de reconocer cosas. En este caso, notemos que tenemos una suma de k+1 elementos y esa suma es elevada al cuadrado. Creo que la preguntas serían:

A qué quiero llegar? En principio, probar la igualdad. Luego, para ello, debo transformar esta expresión en la deseada.
Cómo lo hago? Como quiero transformarla, entonces no quiero modificar su valor, por lo que necesito aplicar operaciones que no modifiquen su valor (para cualquier n).

Bien, quedamos en que debo modificar la expresión sin modificar su valor. Ahora, qué operaciones aplico? cómo puedo modificar su forma sin modificar su valor para cada n?

Ahora es cuando tenemos que pensar en las igualdades que conocemos, las que sabemos desarrollar; para que así, transformemos la expresión.

Recordemos que tenemos una suma de k+1 elementos y esa suma está elevada al cuadrado. Qué igualdades relaciondas con elementos elevados al cuadrado conocemos? Yo me acuerdo del binomio al cuadrado, el cual es igual a un desarrollo fácil de recordar. Pero como lo que tenemos elevado al cuadrado es una suma de k+1 elementos, es necesario utilizar la propiedad asociativa de la suma y asociar los primeros k elementos como si fuese uno de los monomios que conforma al binomio que queremos desarrollar.

Si a la suma de los k elementos lo llamamos S, podemos decir que la expresiòn que nos queda es la suma de S más (k+1) elevados al cuadrado. Dicha nueva expresión es igual al desarrollo s al cuadrado más s por 2 por (k+1) más (k+1) al cuadrado.

Hasta ahora hemos transformado un poco la expresión sin modificar el valor que tendría en algún n natural.

Recordemos que queremos llegar a que lo que obtuvimos es igual a la suma de los k+1 elementos, cada uno elevado al cubo.

Qué puedo decir acerca de la expresión que logramos obtener? Observemos....
Tèrmino por término....
En el primer término tenemos a s que representa a la suma de los k elementos, y como s está elevado al cuadrado, entonces la suma está elevada al cuadrado. En el segundo término tenemos el doble de la suma de los k elementos multiplicados por el número (k+1) y, por último, en el tercer término tenemos al número (k+1) elevados al cuadrado. Qué podemos comentar sobre estos términos? Cómo puedo seguir transformando esta expresión en otra? Tenemos algún dato que nos puede servir? Qué datos tenemos?

TEnemos el dato de la hipótesis inductiva. LA que los dice que la suma de k elementos elevada al cuadrado el igual a la suma de los k elementos donde cada elemento está elevado al cubo. Entonces podemos seguir transformando nuestra expresión reemplezando s al cuadrado por una expresión equivalente, la que mencionamos.
