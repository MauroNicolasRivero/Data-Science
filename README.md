# Data-Science en CoderHouse
Este es un proyecto de DS donde voy a crear un modelo de ML que pueda predecir que reservas van a ser susceptibles de cancelación en una actividad hotelera ficticia usando un dataset descargado de Kaggle con datos reales.

* Contexto Comercial

**HospeDate SA** es una cadena Portuguesa que administra hoteles, a través de su área de contabilidad pidió recabar información sobre las reservas hechas en sus establecimientos, para llevar a cabo un análisis completo con el fin de detectar oportunidades para aumentar sus ingresos y conocer las preferencias de sus usuarios.

* Problema Comercial

El rubro hotelero está sujeto a varios eventos externos que hacen complejas las tomas de decisiones como la competencia, clima metereológico y la estacionalidad pero hay otros eventos que podemos llegar a preveer como las **Cancelaciones de reservas** que afectan la explotación de las habitaciones, es por eso que vamos a concentrarnos en este fenómeno.

* Definición del Objetivo

Como objetivo principal nos proponemos desarrollar un modelo que pueda predecir que porcentaje aproximado de reservas serán canceladas.

Como objetivo secundario y en base al porcentaje arrojado por el modelo decidir de que forma se va a trabajar ese resultado para maximizar las ganancias al sobrevender habitaciones susceptibles a ser canceladas en una primer instancia o minimizar las pérdidas tratando de conservar el cliente ofreciendo mejoras en los servicios

* Contexto Analítico

Disponemos de un dataset con las reservas hechas entre los meses de Julio del 2015 y Agosto del 2017, son unos 120.000 datos aproximadamente divididos en 32 columnas con datos cuantitativos y cualitativos, las cuales vamos a analizar para ir reduciendo su número y asi el contexto sobre el cual nos vamos a enfocar para los objetivos planteados.

* Breve Descripción de las Variables que vamos a utilizar:
 
 1. **Hotel**: *Tipos de hoteles*
 2. **Is_canceled**: *Muestra si fue o no cancelada la reserva*
 3. **Arrival_date_week_number**: *Muestra la semana en número en la cual llegarán los huespedes*
 4. **Meal**: *Comidas ofrecidas por el hotel*
 5. **Country**: *País procedente de los huéspedes*
 6. **Market_Segment**: *Segmento del mercado que operó en la reserva*
 7. **Is_repeated_guest**: *Si el cliente ya ha reservado en alguna otra ocasión*
 8. **Previuos_cancellations**: *Si el cliente ha incurrido en una cancelación anteriormente*
 9. **Reserved_room_type**: *Tipo de habitación reservada*
 10. **Assigned_room_type**: *Tipo de habitación asignada*
 11. **Deposit_type**: *Muestra si han hecho un depósito previo o no*
 12. **Customer_type**: *Muestra que tipos de clientes son* 
 13. **Adr**: *Es una métrica que muestra la tarifa promedio por habitación*
 14. **Required_car_parking_spaces**: *Indica si el huésped solicitó lugar en el estacionamiento*
 15. **Total_of_special_requests**: *Indica la cantidad total de solicitudes que hizo el huésped*
 16. **Reservation_status_date**: *Fecha de la última actualización de la reserva*
 17. **People_sum**: *Es la suma de las distintas variables que representan los huéspedes*
 18. **Days_Sum**: *Sumatoria de los dias reservados ya sean entre semana o fin de semana*
 19. **Date_arrive**: *Fecha de llegada declarada en la reserva*
 20. **Day_dif**: *Representa cuantos dias antes de la fecha de arribo se produjo la cancelación*
