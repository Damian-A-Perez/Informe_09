# Informe_09
TEMA: PRÁCTICA No. 9 AMPLIFICADOR OPERACIONAL.

ESTUDIANTES: MENESES JARRIN SANTIAGO JAVIER OSEJO CUESTA BRANDON DILLAN PEREZ CEDILLO DAMIAN ALEXANDER

DOCENTE: DARWIN OMAR ALULEMA FLORES

NRC: 8703

En esta practica usaremos tres distintos circuitos de red para comprender el funcionamiento y las distintas aplicaciones que se pueden generar gracias a un amplificador operacional reconoceremos la diferencia en la señal sinusoidal que entra al amplificador y la que sale del amplificador.

# 1 PLANTEAMIENTO DEL PROBLEMA:

Reconocer como afecta la disposición de los distintos elementos del circuito respecto al voltaje de salida proporcionado por el amplificador operacional? ¿Qué factores limitan el funcionamiento de un amplificador operacional dentro de un circuito?

# 2 OBJETIVOS:

-Verificar el principio de funcionamiento de un amplificador operacional.

-Analizar algunas aplicaciones básicas con el amplificador operacional.

2.1OBJETIVOS ESPECIFICOS:

-Implementar los circuitos utilizando amplificadores operacionales y comprobar su funcionamiento mediante el osciloscopio.

-Determinar y analisar la relación entre las señales de entrada y salida del amplicador operacional en cada uno de los circuitos.

-Conocer los distintos parámetros técnicos que deben ser considerados para el uso de un amplificador operacional.

-Investigar acerca de las distintas aplicaciones de los AO y analizar las características de los distintos amplificador operacionales dentro el mercado.

# 3 MARCO TEORICO:

Un amplificador operacional, tambien conocido como op-amp (operational amplifier), es un dispositivo electronico que consta de dos entradas y una salida, se lo reconoce como amplificador gracias a que por lo general su salida es en gran cantidad superior a la diferencia de potencial generada en sus entradas.
SU DIAGRAMA LOGICO ES:

![](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/180px-Op-amp_symbol.svg.png)


Como se puede observar consta de diferentes partes o tambien pines de conexion, los cuales tienen distinto proposito en la conexion de una red de amplificacion.

SUS TERMINALES O PINS DE CONEXION SE RECONOCEN DE LA SIGUIENTE MANERA.
V+ = Entrada no inversora.

V− = Entrada inversora.

Vout = Salida.

VS+ = Fuente DC positiva.

VS− = Fuente DC negativa.

Los diseños varían entre cada fabricante y cada producto, pero todos los amplificadores operacionales tienen básicamente la misma estructura interna, que consiste en tres etapas:
1. Amplificador diferencial: 
		Es la etapa de entrada que proporciona una baja amplificación del ruido y gran impedancia de entrada. Suelen tener una salida diferencial.

2.Amplificador de tensión: 
		Proporciona ganancia de tensión.

3.Amplificador de salida: 
		Proporciona la capacidad de suministrar la corriente necesaria, tiene una baja impedancia de salida y, usualmente, protección frente a cortocircuitos. Éste también proporciona una ganancia adicional.
		
°Los amplificadores operacionales tienen caracteristicas escenciales:

Infinita ganancia en lazo abierto.

Infinita resistencia de entrada.

Corriente de entrada cero.

Tensión de desequilibrio de entrada cero.

Infinito rango de tensión disponible en la salida.

Infinito ancho de banda con desplazamiento de fase cero.

Rapidez de variación de tensión infinita.

Resistencia de salida cero.

Ruido cero.


# 4 Materiales 

-Generador de señales

-Fuente DC.

-Osciloscopio.

-Protoboard

-Multímetro

-Cables conductores

-Resistencias, capacitores

-Amplificadores operacionales. 

# 5 Procedimiento

1.- Construya en el protoboard cada uno de los circuitos de la figura 1. Muestre
simultáneamente las señales de entrada y salida en un osciloscopio. Dibuje o capture las formas
de onda.

2.- Determine y analice la relación entre las señales de entrada y salida en cada uno de los
circuitos indicados en la figura 1.

3.- Simule los circuitos y muestre resultados gráficos.

![C1](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/C1.png)

![LF1](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/LF%202.png)

![LF1 osc](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/LF%201.png)

(explicacion)

![C2](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/C2.png)

![LF2](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/LF%2044.png)

![LF2 OSC](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/LF%203.png)

(explicacion)

![LF3](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/C3.png)

![LF3](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/LF%206.png)

![LF3 OSC](https://github.com/Damian-A-Perez/Informe_09/blob/master/Img/LF%205.png)


(explicacion)

6..- RESPUESTA DE PREGUNTAS

-1.Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.

Tención de alimentacion: Tención máxima permitida que puede aplicarse con seguridad al amplificador, 15V estándar.

Rango de temperatura de operación (Tor).

Tensión de entrada diferencial (Vid): Tensión máxima que puede aplicarse con seguridad entre los terminales de entrada diferencial sin flujo excesivo de corriente +-30V.

Voltaje de entrada en modo común (Vcm): Voltaje que puede aplicarse en ambas entradas respecto a tierra.

Consumo de potencia (PC): Potencia requerida para operar el amplificador operacional o la potencia consumida por este.


Disipación de potencia (PD): Potencia que es capaz de disiparse en un dispositivo con seguridad en forma continua mientras opera dentro de un rango de temperatura especifico.

-2.Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.
AO LM741, amplificador de propósito general bastante conocido y de uso muy extendido. Cuenta con parámetros bastante regulares, en conjunto genera alta impedancia de entrada, pequeños offset de corriente y voltaje en la entrada.

AO LM725. Similar al anterior con mejora en sus parámetros, como menores valores para el voltaje y corriente de offset, su corriente de polarización también es menor y su CMRR más elevado. Con la desventaja que su impedancia es menor al del LM741.

AO LF411. Posee excelentes parámetros, tiene un offset de entrada y una corriente de polarización de valores muy bajos, su impedancia de entrada es la más elevada de todas. Es uno de los amplificadores operacionales de National Semiconductors para la aplicación de máxima precisión.

3.-Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.
Los amplificadores operacionales son comúnmente usados en:

Comparadores.

Seguidores de voltaje o tensión.

Amplificador no inversor.

Sumador y restador inversor.

Derivador ideal

Conversor de corriente a tensión.

Función exponencial y logarítmica.


7.- CONCLUSIONES

8.-RECOMENDACIONES





