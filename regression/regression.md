# Regression Models.

## Linear Regression.

Una Regresión Lineal es un modelo matemático-estdístico que sirve para aproximar la relación de dependencia o correlación entre una variable dependiente y $n$ variables independientes.
Es importante precisar que las variables independientes en una regresión lineal son llamadas también variables predictoras y sus valores son conocidos con antelación. Por otro lado, la variable dependiente se considera  variable respuesta y su carácterística fundamental es que su valor es continuo, no discreto.
Nótese el término de **variable predictora**, este nos indica a simple vista que con una regresión lineal se puede predecir el valor de una variable o, mejor aún, el comportamiento de un fenómeno con base en los datos históricos del mismo. Así mismo, es importante resaltar que estos modelos son óptimos para predecir valores futuros cuando se espera que la variable de respuesta arroje un valor continuo (genralmente con valores decimales) ejemplo, si se quiere conocer el precio de un cab_service con base en la distancia a recorrer, el estado del clima, el estado del tráfico y cualquier otro factor que influya decisivamente en un servicio de taxi.

Auque en el ejemplo anterior puede se pueden incluir muchas variables predictoras que permiten consolidar un modelo más preciso, por fines didácticos empezaremos analizando unicamente la correlación entre dos variables, para predecir el precio de un cab service solo utilizaremos la distancia recorrida como variable predictora.

### Simple Linear Regression.
Como ya dijimos, este modelo permite predecir un fenómeno con base en el comportamiento de una variable independiente o predictora.
La fórmula de regresión lineal simple es:
$Y = \beta_{0} + \beta_{1}X$

Donde $Y$ es el valor a predecir y $X$ es la variable independite o predictora.
$\beta_{0}$ es el intersepto o el punto donde se corta la $Y$ cuando $X$ tiene un valor de cero. Imaginemos por ejemplo un cargo fijo, el valor fijo que cobra un cab driver justo cuando el pasajero se monta en el vehículo y todavía no ha empezado a andar.
El coeficiente $\beta_{1}$ es, por otro lado, la pendiente o el grado de variación del valor de $Y$ por cada unidad de medida de $X$. En nuestro ejemplo, indica cuánto aumenta el precio del cab_service por cada kilómetro recorrido.
Entonces para entender mejor nuestra fórmula podríamos decir que:
$cabServicePrice = \beta_{0} + \beta_{1}(tripDistance)$
