# objetos_js

## cuál es el principal uso del objeto de la propiedad Date
- El objeto de propiedad Date en JavaScript se utiliza principalmente para representar y trabajar con fechas y horas. Permite realizar diversas operaciones, como:

- Obtener la fecha y hora actual: Se puede crear un objeto Date sin argumentos para obtener la fecha y hora actuales del sistema.
- Crear una fecha específica: Se puede especificar la fecha y hora exactas al crear el objeto Date utilizando argumentos.
- Extraer información de fecha y hora: Se pueden obtener diferentes componentes de la fecha y hora, como el año, mes, día, hora, minutos y segundos, utilizando métodos del objeto Date.
- Manipular fechas y horas: Se pueden sumar, restar y comparar fechas y horas utilizando métodos del objeto Date.
- Formatear fechas y horas: Se puede convertir la fecha y hora a diferentes formatos de cadena utilizando métodos del objeto Date.

En resumen, el objeto Date es una herramienta esencial para trabajar con fechas y horas en JavaScript. Se utiliza en una amplia variedad de aplicaciones web, como formularios, calendarios, registros de datos y mucho más.

- Obtener la fecha y hora actual:
JavaScript
const fechaActual = new Date();
console.log(fechaActual); // Muestra la fecha y hora actual

## sus principales propiedades de la funcion Date

La función Date en JavaScript se utiliza para trabajar con fechas y horas. Aquí están algunas de sus principales propiedades y métodos:

## Propiedades:

-Date.prototype: Permite agregar nuevas propiedades y métodos a todos los objetos de tipo Date.
-Date.length: Propiedad que indica el número de argumentos esperados por el constructor Date.
-Date.now(): Método estático que devuelve el número de milisegundos transcurridos desde el 1 de enero de 1970 00:00:00 UTC.

## Métodos:

-getDate(): Obtiene el día del mes (1-31) de la fecha especificada según la hora local.
-getDay(): Obtiene el día de la semana (0-6) de la fecha especificada según la hora local.
-getFullYear(): Obtiene el año (como un número de cuatro dígitos) de la fecha especificada según la hora local.
-getHours(): Obtiene la hora (0-23) de la fecha especificada según la hora local.
-getMilliseconds(): Obtiene los milisegundos (0-999) de la fecha especificada según la hora local.
-getMinutes(): Obtiene los minutos (0-59) de la fecha especificada según la hora local.
-getMonth(): Obtiene el mes (0-11) de la fecha especificada según la hora local.
-getSeconds(): Obtiene los segundos (0-59) de la fecha especificada según la hora local.
-getTime(): Devuelve el valor numérico correspondiente al tiempo para la fecha especificada según la hora universal (UTC).
-getTimezoneOffset(): Devuelve la diferencia de minutos entre la hora local y la hora UTC.
-getUTCDate(): Obtiene el día del mes (1-31) de la fecha especificada según la hora UTC.
-getUTCDay(): Obtiene el día de la semana (0-6) de la fecha especificada según la hora UTC.
-getUTCFullYear(): Obtiene el año (como un número de cuatro dígitos) de la fecha especificada según la hora UTC.
-getUTCHours(): Obtiene la hora (0-23) de la fecha especificada según la hora UTC.
getUTCMilliseconds(): Obtiene los milisegundos (0-999) de la fecha especificada según la hora UTC.
-getUTCMinutes(): Obtiene los minutos (0-59) de la fecha especificada según la hora UTC.
-getUTCMonth(): Obtiene el mes (0-11) de la fecha especificada según la hora UTC.
-getUTCSeconds(): Obtiene los segundos (0-59) de la fecha especificada según la hora UTC.
-setDate(): Establece el día del mes para una fecha según la hora local.
-setFullYear(): Establece el año de una fecha según la hora local.
-setHours(): Establece la hora para una fecha según la hora local.
-setMilliseconds(): Establece los milisegundos para una fecha según la hora local.
-setMinutes(): Establece los minutos para una fecha según la hora local.
-setMonth(): Establece el mes para una fecha según la hora local.
-setSeconds(): Establece los segundos para una fecha según la hora local.
-setTime(): Establece una fecha en milisegundos desde el 1 de enero de 1970 00:00:00 UTC.
-setUTCDate(): Establece el día del mes para una fecha según la hora UTC.
-setUTCFullYear(): Establece el año de una fecha según la hora UTC.
-setUTCHours(): Establece la hora para una fecha según la hora UTC.
-setUTCMilliseconds(): Establece los milisegundos para una fecha según la hora UTC.
-setUTCMinutes(): Establece los minutos para una fecha según la hora UTC.
-setUTCMonth(): Establece el mes para una fecha según la hora UTC.
-setUTCSeconds(): Establece los segundos para una fecha según la hora UTC.