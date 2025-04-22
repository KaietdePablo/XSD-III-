# XSD-III-
Ejercicio 1 - Longitud fija de una clave
Objetivo: Definir un tipo de dato clave que permita una longitud fija de 10 caracteres, que pueden ser letras (mayúsculas y minúsculas) o dígitos.

Solución: Se crearon dos versiones utilizando:

xs:length y xs:pattern para asegurar que la longitud sea de 10 caracteres y los valores sean letras o dígitos.

Solo xs:pattern para lograr la misma validación con una expresión regular.

Ejercicio 2 - Longitud mínima y máxima de una clave
Objetivo: Validar que el elemento clave tenga entre 4 y 10 caracteres, con letras (mayúsculas y minúsculas) y dígitos.

Solución: Usamos las restricciones xs:minLength, xs:maxLength y xs:pattern para asegurar que la clave esté entre 4 y 10 caracteres, y solo contenga letras y dígitos.

Ejercicio 3 - Precios de artículos
Objetivo: Validar un documento XML que contenga precios de artículos, donde cada precio tiene un atributo moneda (por ejemplo, "Euro", "Dólar").

Solución: Se definió un esquema que incluye un tipo claveType para los elementos precio, permitiendo validar tanto el valor numérico como el atributo moneda.

Ejercicio 4 - Información de ubicaciones
Objetivo: Ampliar la definición del tipo direccion para incluir un atributo adicional metros, y validarlo en un documento XML.

Solución: Se creó un nuevo tipo complejo infoUbicacion que combina el tipo direccion con un atributo metros, permitiendo la validación de un documento con información sobre ubicaciones y distancias.

Ejercicio 5 - Colores de muebles
Objetivo: Validar un documento XML que contenga muebles, donde cada mueble tiene un tipo (por ejemplo, "mesa", "silla") y un color (por ejemplo, "blanco", "gris").

Solución: Se definió un tipo tipoColorMueble que extiende tipoMueble para incluir un atributo color, permitiendo la validación de muebles con colores específicos.
