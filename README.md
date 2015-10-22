# ListenerSiteCondition
Proyecto con Intel Edison para monitorear las condiciones de un site mediante diversos sensores.

El site es la ubicación en donde se concentran los recursos necesarios para el procesamiento de la información de una organización. Debido a la importancia de los sistemas y el procesamiento llevan un acondicionamiento muy importante como lo es la temperatura, el acceso, la iluminación, la calidad del aire.

Lo que se pretende con este proyecto es controlar de manera automatizada y mandar alertas a un correo electronico o un mensaje de texto de acuerdo a la prioridad.

Para este proyecto se implementarán los siguientes sensores:
* sensor de luz Grove SEN11302P
* sensor de temperatura Gove SEN23292P
* sensor de sonido Grove SEN12945P
* sensor de calidad de aire Grove 101020078
* sensor infrarrojo reflectivo Grove  WL07061P
* sensor de fuego 101020049

Debido a la importancia del site, el acondicionamiento que este lleva y debe llevar, se implementarán los sensores para la luminosidad, esto es para cuando entra alguna persona y de la luz del lugar, el de temperatura para medir el lugar si es muy frio, apagar el aire acondicionado o si la temperatura es alta encender el aire acondicionado. El sensor de sonido medirá la cantidad de sonido cuando no haya nadie en el site y mandará una alerta al correo por una posible falla o algúna otra posibilidad de que haya sonido. El de la calidad del aire evaluará si el aire es malo puede que algun componente este sacando humo. El de infrarrojo servirá de detección si la puerta esta abierta o esta cerrada. El sensor de fuego nos dirá si hay fuego en el site y asi mandar una alerta por mensaje de texto.
