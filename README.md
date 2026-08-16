¿Por qué es mala práctica usar SELECT * en producción? Mencioná al menos dos razones concretas (rendimiento, mantenibilidad, seguridad).

Es mala practica usar SELECT ya que traeriamos todos los datos de la tabla que hay creados, lo que haría un archivo muy pesado y con datos innecesarios. Esto haría que en rendimiento sea demasiado lento debido a la cantidad de datos y a su vez estariamos viendo datos que realmente no necesitamos. Su mantenibilidad sería compleja ya que al haber tantos datos, podemos equivocarnos en lo que realmente necesitamos

¿Por qué son importantes los alias para un stakeholder no técnico? Explicá con un ejemplo concreto cómo un alias transforma total_amount en algo que cualquier persona del área de finanzas puede interpretar directamente.

Es importante para que cualquier persona pueda entender a que se refiere el dato. En lugar de poner total_amount ponemos total_facturado entonces cualquier persona entendería de lo que estamos hablando