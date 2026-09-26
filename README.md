# sql-select-fundamentals

1. Asunto del uso del SELECT *

  Esta sentencia de SQL debe usarse con cautela, ya que es inmensamente útil, por ejemplo, para comprobar o revisar rápidamente que la información que se deseaba poner al crear una tabla y la que se ingresa en ella mediante INSERT, pero en caso de que no se quisiera comprobar absolutamente todo, es mucho mejor si solo se selecciona lo que se necesita ver, ya que pueden haber muchas columnas o mucha información, la que costará recursos del computador o máquina en donde se corre el script. Por otro lado, puede haber un grave riesgo de seguridad, ya que si se está corriendo el script y se tiene la sentencia SELECT * para extraer de una tabla toda su información, y allí se encuentran columnas que contengan entradas confidenciales, se habrá mostrado información no deseada de manera pública.


2. El uso de los alias
   Los alias en el script de SQL son bastante útiles para reconocer con un nombre más amigable, por ejemplo, si una columna se llama originalmente total_amount, se puede entender de manera más sencilla esta información si a esa columna se le llama total_unidades.


