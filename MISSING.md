# Missing

- Como poder ponerlos en un assambly para las cosas que son internal y todo eso

- Hacer los test ya formalmente, o ver como se podrian hacer, o por lo menos crear esenas y documentarlo para que se puedan tener.

- Documentar como se usa el banner, que se debe crear la clase que herede y eso , y como lo puse en el monobehaviour

- Hacer que sii no es una platafoorma soportada, se va a comportar como si fuera el modo NoAdsMode

- Hacer que si se usa el await para el Show y no hay ningun listener agregado, entonces se va a completar la task con .onFailed

- hacer en la clase intertitial que la variable isstarted refleje si esta o no subscrito a los eventos, esto se puede hacer revisando si es null el listener
  y hacer que el initialize se llame antes de ejecutar el noAdsmode para que ya este subscrito y se comporte bien

 sacar el assably definition de dentro de Runtime y ponerlo directo sobre U.Universal.Ads