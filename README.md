# LABORATORIO 2

Laboratorio 2 Analisis de Mallas

Nombres: Nicolas Cando , Blass Collaguazo

1. OBJETIVOS
2. 1.1 Objetivos Generales.

-Determinar mediante la ley de voltajes de Kirchhoff la corriente en un circuito eléctrico.

1.1.2 Objetivos Especificos

-Calcular el valor de la corriente del circuito mediante el análisis de mallas.

-Aplicar un sentido de corriente arbitrario (horario o antihorario) para todas las mallas.

-Comprender la importancia que tiene el análisis de mallas al analizar circuitos electrónicos para realizar cálculos de una manera más fácil y organizada.


2. MARCO TEÓRICO

2.1.1 MUltimetro.-Es un instrumento portatil que se usa para medir magnitudes electricas como corrientes y potencias, se puede medir corriente continua o alterna los multimetros o tambien conocidos como tester en la actualidad son digitales, esta compuesto por su pantalla, una perrilla y sus dos cables positivo y tierra.

2.1.2 SOLDADOR.- Es un instrumento el cual consta de 3 partes un cable de conección a 110 v, una parte fija de madera o plastico y su punta de metal, su punta se calentara a una temperatura capaz de derretir el estaño. esto nos sirve para hacer sueldas de componentes electronicos, ademas de placas en baquelitas.

2.1.3 PROTOBOAD.- Es una especie de tablero con orificios, en la cual se pueden insertar componentes electrónicos y cables para armar circuitos. Como su nombre lo indica, esta tableta sirve para experimentar con circuitos electrónicos, con lo que se asegura el buen funcionamiento del mismo.

2.1.4 RESISTENCIA.- La resistencia electrica de un objeto es una oposion al paso de la corriente electrica.

2.1.5 CIRCUITO EN SERIE.- Este es un circuito que su caracteristica principal es que sus bornes o resistencias van una tras de la otra en este circuito la tension varia.

2.1.6 CIRCUITO PARALELO.- Este es un circuito el cual sus resistencias estan conectadas de forma que todos sus terminales coinciden entre sí en este circuito no varia la tensión.

2.1.7 CIRCUITO MIXTO.- Este circuito es un circuito que se compone de un circuito en serie con un circuito en paralelo.

2.1.8 LEY DE KIRCCHOFF.-Las leyes de Kirchhoff son dos igualdades que se basan en la conservación de la energía y la carga en los circuitos eléctricos. En estas leyes vamos a ver lo que es un NODO y lo que es una MALLA, el Nodo  es un punto donde dos o más elementos o ramas de un circuito cerrado tienen una conexión común. la Malla es un lazo cerrado o un circuito cerrado de toda la conexión.

2.1.9 LEY DE OHM.-La ley de Ohm se usa para determinar la relación entre tensión, corriente y resistencia en un circuito eléctricO, aqui tenemos una formula de la cual despejamos los demas componentes, la formula es V= I.R (Voltaje= Intensidad . Resistencia)

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Sin-t-tulo.png)

3. EXPLICACIÓN DEL PROCEDIMIENTO

EXPERIMENTO SIMULADO

Circuito para el análisis de mallas.

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen1%20(2).png)

Diagrama Esquematico

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen2%20(2).png)

Se procede a ultilizar el simulador tinkercad para realizar mediciones de intensidad de corriente en el circuito 

Medicion de intensidad de corriente:

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen4%20(2).png)

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen5%20(2).png)

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen6%20(2).png)

Se anotaron los datos en la siguiente tabla:

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen9%20(2).png)

EXPERIMENTO ANALITICO

Se procede a realizar el calculo analiticamente con el metodo de mallas y las Leyes de Kirchhoff:

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen%20de%20WhatsApp%202022-11-17%20a%20las%2021.27.43.jpg)

Resolucion del circuito con las Leyes de Kirchhoff:

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen%20de%20WhatsApp%202022-11-17%20a%20las%2021.38.32.jpg)

Lo que nos resulta en un sistema de ecuaciones 5x5 esto sistema lo resolvemos con la regla de cramer

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen%20de%20WhatsApp%202022-11-17%20a%20las%2021.41.16%20(2).jpg)

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen%20de%20WhatsApp%202022-11-17%20a%20las%2021.41.45%20(2).jpg)

Los resultados lo anotamos en una tabla

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen10%20(2).png)

EXPERIMENTO EN LA VIDA REAL

Se procedio hacer el circuito en la protoboard de fuente de alimentacion se uso el arduino que nos da 5 voltios y 3.3 voltios.

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/experimento.jpg)

Con la ayuda del multimetro podemos medir la corriente en cada una de las resistencias:

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/medicionexpe.jpg)

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/valorexpe.jpg)

Se anotaron los valores en una tabla:

![](https://github.com/Nikopunky/Laboratorio-2/blob/main/Imagen11%20(2).png)

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Los valores analíticos y simulados, cumplen con la ley de voltaje y corriente de Kirchhoff, de la misma forma ambos obtienen los mismos valores para las corrientes de las mallas.

En cuanto a los valores experimentales existe una ligera diferencia entre los analíticos y simulados, incluso entre ambos circuitos del grupo, es puesto que para el circuito físico se utilizaron fuentes de voltaje de 6 V en lugar de 5 V, y de 9 V en lugar de 10 V, y también las baterías de cada circuito del grupo, también varían ligeramente en su valor, por ende existirá una diferencia de hasta una unidad con los valores previstos, esto se observa en las mediciones, sin embargo por regla de tres se puede observar como los resultados del circuito físico son casi iguales a los resultados analíticos y simulados.

Respecto al margen de error, es debido a los diferentes valores usados en el circuito físico, y también que siempre existirá una diferencia de milésimas por distintos aspectos, principalmente el redondeo de resultados.

5. VIDEO

6. CONCLUSIONES

• Se utilizó un análisis y compresión adecuado del esquema del circuito eléctrico para su elaboración, por medio de los materiales adecuados respetando su trayectoria y polaridad con el fin de que cumpliera con lo solicitado

• Se determinó que gracias al análisis de mallas se puede obtener los valores de las corrientes de mallas por medio de un sistema de ecuaciones, siendo útil este método para un circuito eléctrico complejo.

7. BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. Octava edición. México: PEARSON EDUCACIÓN.
McAllister, W. (2022). Khan Academy. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method
Zapata, F. (1 de Noviembre de 2019). Lifeder. Obtenido de https://www.lifeder.com/analisis-de-mallas/ 

RUBRICA

![](https://github.com/Bscollaguazo/LAB1_COLLAGUAZO_BLASS/blob/main/Laboratorio.png)
