    Juan Felipe Rubio Sanabria J1  

Informacion sobre Date kavasckiropt:  

    -getDay() 

Este codigo nos dice el dia en el que nos encontramos, este empieza desde 0( Domingo) el primer dia. 

    -setHours() 

Asigna la hora de una fecha, esta tambien puede configurar minutos segundos y milisegundos. 

    -getUtCDay() 

Instancias devuelve el día de la semana para esta fecha según el tiempo universal, donde 0 representa el domingo.

    -new Date() 

Cuando es usado como un constructor, crea un nuevo objeto Date.


    Date.now()
Devuelve el valor numérico correspondiente al actual número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC, ignorando los segundos intercalares.

    Date.parse()
Transforma la cadena que representa una fecha y devuelve el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC, ignorando los segundos intercalares.


    -Date.UTC()
Acepta los mismos parámetros que el constructor en su forma extendida (por ejemplo: del 2 al 7) y devuelve el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC, ignorando los segundos intercalares.


    -Date.prototype.getDate()

Devuelve el día del mes (1–31) para la fecha especificada según la hora local.

    -Date.prototype.getDay()

Devuelve el día de la semana (0–6) para la fecha especificada según la hora local.

    -Date.prototype.getFullYear()

Devuelve el año (4 dígitos para años de 4 dígitos) para la fecha especificada según la hora local.

    -Date.prototype.getHours()

Devuelve la hora (0–23) para la fecha especificada según la hora local.

    -Date.prototype.getMilliseconds()

Devuelve los milisegundos (0–999) para la fecha especificada según la hora local.

    -Date.prototype.getMinutes()

Devuelve los minutos (0–59) para la fecha especificada según la hora local.

    -Date.prototype.getMonth()

Devuelve el mes (0–11) para la fecha especificada según la hora local.

    -Date.prototype.getSeconds()

Devuelve los segundos (0–59) para la fecha especificada según la hora local.

    -Date.prototype.getTime()

Devuelve el valor numérico de la fecha especificada como el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC. (Devuelve valores negativos para fechas anteriores).

    -Date.prototype.getTimezoneOffset() 

Devuelve la diferencia horaria en minutos para la hora local.

    -Date.prototype.getUTCDate() 

Devuelve el día del mes (1–31) para la fecha especificada según la hora local.

    -Date.prototype.getUTCDay()

Devuelve el día de la semana (0–6) para la fecha especificada en hora universal.

    -Date.prototype.getUTCFullYear()

Devuelve el año (4 dígitos para años de 4 dígitos) para la fecha especificada según la hora universal.

    -Date.prototype.getUTCHours() 

Devuelve la hora (0–23) para la fecha especificada según la hora universal.

    -Date.prototype.getUTCMilliseconds() 

Devuelve los milisegundos (0–999) para la fecha especificada según la hora universal.

    -Date.prototype.getUTCMinutes() 

Devuelve los minutos (0–59) para la fecha especificada según la hora universal.

    -Date.prototype.getUTCMonth() 

Devuelve el mes (0–11) para la fecha especificada según la hora universal.

    -Date.prototype.getUTCSeconds() 

Devuelve los segundos (0–59) para la fecha especificada según la hora universal.

    -Date.prototype.getYear() 

Devuelve el año (usualmente de 2 a 3 dígitos) para la fecha especificada según la hora local. Usa getFullYear() en su lugar.

    -Date.prototype.setDate() 

Establece el día del mes para la fecha especificada según la hora local.

    -Date.prototype.setFullYear()

Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha específica según la hora local.

    -Date.prototype.setHours() 

Establece la hora para una fecha específica según la hora local.

    -Date.prototype.setMilliseconds() 

Establece los milisegundos para una fecha específica según la hora local.

    -Date.prototype.setMinutes() 

Establece los minutos para una fecha específica según la hora local.

    -Date.prototype.setMonth()

Establece el mes para una fecha específica según la hora local.

    -Date.prototype.setSeconds() 

Establece los segundos para una fecha específica según la hora local.

    -Date.prototype.setTime() 

Establece el objeto Date al tiempo representado por un número de milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC. Usa números negativos para fechas anteriores.

    -Date.prototype.setUTCDate() 

Establece el día del mes para la fecha especificada según la hora universal.

    -Date.prototype.setUTCFullYear() 

Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha específica según la hora universal.

    -Date.prototype.setUTCHours() 

Establece la hora para una fecha específica según la hora universal.

    -Date.prototype.setUTCMilliseconds() 

Establece los milisegundos para una fecha específica según la hora universal.

    -Date.prototype.setUTCMinutes() 

Establece los minutos para una fecha específica según la hora universal.

    -Date.prototype.setUTCMonth() 

Establece el mes para una fecha específica según la hora universal.

    -Date.prototype.setUTCSeconds() 

Establece los segundos para una fecha específica según la hora universal.

    -Date.prototype.setYear() 

Establece el año (usualmente de 2 a 3 dígitos) para una fecha específica según la hora local. Usa setFullYear() en su lugar.

    -Date.prototype.toDateString()

Devuelve la "fecha" del objeto Date como una cadena fácil de leer por humanos 'Thu Apr 12 2018'.

    -Date.prototype.toISOString()

Convierte una fecha a una cadena siguiendo el Formato Extendido de ISO 8601.

    -Date.prototype.toJSON()

Devuelve una cadena representando el objeto Date usando toISOString(). Destinado a ser usado por JSON.stringify().

    -Date.prototype.toGMTString()

Devuelve una cadena representando el objeto Date basado en la zona horaria GMT (UTC). Usa toUTCString() en su lugar.

    -Date.prototype.toLocaleDateString()

Devuelve una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

    -Date.prototype.toLocaleString()

Devuelve una cadena con una representación sensible a la localización de esta fecha. Sobrescribe el método Object