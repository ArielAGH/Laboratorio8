# Laboratorio 8: Teorema de la Máxima Transferencia de Potencia
Integrantes: Caillamara Leonardo, González Ariel
## 1. OBJETIVOS

### Objetivo general:
* Experimentar con el teorema de Máxima transferencia de potencia mediante el uso de varios resistores como resistores de carga.
### Objetivos específicos:
*	Simular el circuito propuesto en Tinkercad intercambiando el valor del resistor de carga según sea necesario. 
*	Observar en que valores de RL ocurre una máxima transferencia de potencia.

## 2. MARCO TEÓRICO

![](https://github.com/ArielAGH/Laboratorio8/blob/main/Img/TeoremaMaximaTransferencia.png)

El teorema de máxima trasferencia de potencia indica que una resistencia de carga RL recibe la máxima potencia suministrada por la fuente sólo si  RL = Rth es decir, su la resistencia de carga es del mismo valor que la resistencia Thevenin. Y se calcula de la siguiente manera: 

![](https://github.com/ArielAGH/Laboratorio8/blob/main/Img/Formula.jpg)

Como se puede observar en la figura inicial si la resistencia de carga es menor o mayor que la resistencia de Thevenin, la potencia transferida es menor.

Una aplicación más común para este teorema es su utilización en amplificadores de radiofrecuencia los cuales buscan que la carga llegue a disipar la mayor potencia posible al transmitir una señal.

![](https://github.com/ArielAGH/Laboratorio8/blob/main/Img/Amplificador.png)

## 3. EQUIPOS Y MATERIALES

* **TinkerCad:** Programa online de simulación de circuitos.
* **Proteus:** Programa de simulación de circuitos.
* **Protoboard:** Es una placa de pruebas en la que se pueden insertar elementos electrónicos y cables con los que se arman circuitos sin la necesidad de soldar ninguno de los elementos.
* **Resistencias eléctricas:** Elemento eléctrico que se opone al paso de corriente.
* **Cables puente:** Cables de ayuda para realizar conexiones provisionales.
* **Multímetro:** Es un instrumento analógico o digital portátil que se usa para medir directamente magnitudes eléctricas.
* **Batería o fuente energética:** Dispositivo que provee energía a un circuito al cual es conectado.

## 4. PROCEDIMIENTO

* Armar el circuito de la figura en un simulador.

![](https://github.com/ArielAGH/Laboratorio8/blob/main/Img/Figura.png)

* Mida el voltaje y la corriente para cada valor de RL que se indica en la tabla. Anote los resultados medidos.

![](https://github.com/ArielAGH/Laboratorio8/blob/main/Img/VAT220.jpeg)

* Calcule las potencias consumidas por RL, para cada valor dado y anote los resultados en la tabla 5.1.

## 5. TABLAS DE MEDICIÓN Y CÁLCULOS

### Tabla 5.1 Resultados obtenidos para el circuito

![](https://github.com/ArielAGH/Laboratorio8/blob/main/Img/TablaPotencias.png)

Los cálculos respectivos están en la carpeta denominada Cálculos y para el cálculo del error se usa la siguiente fórmula para cada caso.

![](https://github.com/KevinCaillamara/Laboratorio_2/blob/main/Im%C3%A1genes/formula_error.png)

### ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.

Con los resistores usados en esta práctica no fue posible llegar a comprobar que RL recibe la máxima potencia, pero usando los valores obtenidos en los demás resistores se puedo predecir que efectivamente para que exista una trasferencia máxima de potencia el valor de RL debe acercar a Rth.

### ¿Cuál fue la potencia máxima en RL?
0.04649 Watts

### ¿Para qué valor de RL se obtiene la MTP?
1200 Ω


## 6. ANÁLISIS DE RESULTADOS

De los datos obtenidos se puede observar que en el experimento no es posible llegar a la máxima  transferencia de potencia ya que se  necesita un resistor de  1200 Ω el cual no figura en la lista de materiales para esta práctica. 

Comparando los resultados con lo dicho en el marco teórico se puede observar que efectivamente el valor de la potencia va aumentando a medida que la resistencia de carga se acerca al varlor de la resistencia de Thevenin y es menor mientras más lejos esté de esta.  

Adicionalmente se puede notar que mientras el valor del resistor de carga aumenta el voltaje que cae en dicho resistor va aumentando pero para el resistor Rth va disminuyendo.

Los errores registrados en la tabla son bastante pequeños por lo tanto  los datos tomados recogidos generarán un análisis bastante exacto.


## 7. CONCLUSIONES

En conclusión, queda demostrado que el teorema de máxima transferencia de potencia si es válido cuando el valor de la carga es igual al del resistor de Thevenin. Esto implica que la potencia siempre será menor para cualquier valor de RL distinto a Rth.

Este teorema no es un método para realizar un análisis de circuitos pero es útil al momento de crear un diseño el cual sea necesario que RL disipe o entregue la mayor potencia posible.

## 8. BIBLIOGRAFÍA

* Durán, J. (2012). *Electrotecnia*. Barcelona: Editorial Lexus.
* Fraile, J. (2012). *Circuitos eléctricos*. Madrid: Editorial Pearson.
* Thomas, L. (2007). *Principios de circuitos eléctricos*. México: Editorial Pearson.
* Sadiku, M. (2006). *Fundamentos de circuitos eléctricos*. México: McGraw Hill Interamericana.
