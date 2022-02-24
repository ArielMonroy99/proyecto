# Proyecto: Bot para servicio delivery de comida
## Integrantes 
- Jose Ignacio Carvajal Laura
- Kevin Rolando Lecoña Marca
- Ariel Ygnacio Monroy Luna
## Introducción 

 El bot servirá para apoyar la organización en un restaurante, podrá responder consultas básicas como menú del día o qué platos a la carta existen y la disponibilidad de estos.También proporciona una opción para elegir platos vegetarianos o veganos en caso de requerir y además podrá registrar la reserva de  platos y dar información básica del restaurante como dirección y horarios de atención.

 ## Problematica
 
 Vimos las dificultades de comunicación de un restaurante con el cliente, para mejorar la situación del restaurante se hará un bot para poder ayudar a mejorar la comunicación. 
 El bot está enfocado a problemas comunes en restaurantes. No puede usar los servicios de delivery estándares por el costo de comisión que tiene las aplicaciones por ese motivo se utilizara el bot de telegram para poder realizar un servicio de delivery y dar información sobre el menú con el que cuenta.  
    
 Los problemas con los que se encuentran los clientes son los siguientes: 
- No poder contactar con el restaurante mediante un servicio de delivery convencional
- No saber el menú con el que el restaurante cuenta 

Los inconvenientes que tiene el restaurante: 
- No tener un contacto con los clientes. 
- No poder realizar el servicio de delivery



## Valor el valor que el proyecto va a dar a la empresa.
Un metodo de comunicacion entre el cliente y el restaurante permitirá:
- Tangible
    - Promocionar el restaurante.
    - Realizar el servicio de delivery
    - No poder saber informacion sobre el restaurante
- Intangible 
    - Le será más sencillo a los clientes recibir la información deseada por lo que quedaron más satisfechos
    - Mejorará la comunicación del cliente con el restaurante 
    - No poder promocionar el restaurante


 ## Ejemplo de funcionamiento del BOT

 ## Menu de Empleado

```
Cli: Hola
Bot: Hola,selecciona una opción:
1. Ver menú
2. Ver información del restaurante 
3. Tu pedido
5. Salir
```
Si selecciona la opción 1:
```
Bot: (mostrar menu)
1. Entradas   
2. Platos fuertes
3. Postres
4. Bebidas
5. Menú del día
7. Promociones 
6. Terminar
#. Atrás 

Si se selecciona entradas: 

Bot: (mostrar menu)
1. Tortilla de Acelga
2. Choclos a la parrilla con ají 
3. Falafel
@. Agregar al pedido
#. Atrás 

Si selecciona @ en el menú: 
Bot: Se agregó falafel a la orden 
```

Si selecciona la opción 2:
    
```
Bot: seleccione una opción
Horarios de atención
Sucursales
Atrás
```

Si selecciona la opción 3

```
Bot: (mostrar menu)
1. Falafel x 2     
2. Fricase x 2 
3. Coca Cola 500ml x2 
@. Enviar Pedido
#. Atrás
```