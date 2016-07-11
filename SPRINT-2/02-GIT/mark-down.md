# MarkDown


### ¿Que es MarkDown?

Mark down es un lenguaje de marcado ligero el cual fue creado por John Gruber, este lenguaje trata de conseguir la máxima legibilidad y facilidad de publicación, tanto en su forma de entrada como en la de salida, esta basado originalmente en convenciones existentes en el marcado de los correos electrónicos. Emplea texto plano, procurando que sea legible pero consiguiendo que se convierta en XHTML correctamente formateado.

### Usos de Markdown

Este lenguaje de marcado al ser muy ligero nos permite darle muchos aplicativos cuando de formatear texto se trata, puesto que con un solo caracter le decimos al interprete lo necesario para que convierta a la etiqueta HTML correcta. Sus usos pueden variar, desde creaciones de blog's, correos electronicos, documentos de texto(PDF), entro otros.

### Sintaxis MarkDown

La Sintaxis de Markdown es muy sencilla, solo se basa en una serie de caracteres especiales los cuales despues el interprete cambiara por las etiquetas HTML para su correcta visualización.

A continuación les mostrare algunos ejemplos de la Sintaxis de Markdown:

- **Encabezados**: Estos se producen utilizando el signo de almohadilla '#' continuado del texto y segun la cantidad de signos podremos dar los 6 niveles que HTML nos ofrece.

Código:
~~~
# Esto es una cabecera H1
~~~
Resultado:
# Esto es una cabecera H1
- - -
Código:
~~~
## Esto es una cabecera H2
~~~
Resultado:

## Esto es una cabecera H2
- - -
Código:
~~~
### Esto es una cabecera H3
~~~
Resultado:

### Esto es una cabecera H3
- - -

- **Formato**: Este es el formato basico del texto, como las **Negritas** y *Cursivas*

Código:
~~~
*Texto en Cursivas*
~~~
Resultado:

*Texto en Cursivas*
- - -
Código:
~~~
**Texto en Negritas**
~~~
Resultado:

**Texto en Negritas**
- - -

- **Enlaces**: Veremos tambien las dos maneras de crear un enlace.

Código:
~~~
[Google](https://google.com "Titulo del enlace")

[Google](https://google.com)
~~~
Resultado:

[Google](https://google.com "Titulo del enlace")

[Google](https://google.com)
- - -
Cóodigo:
~~~
[Google][1], [Facebook][2], [YouTube][3]

 [1]: https://google.com
 [2]: https://facebook.com "Facebook"
 [3]: https://www.youtube.com/
~~~
Resultado:

[Google][1], [Facebook][2], [YouTube][3]

 [1]: https://google.com
 [2]: https://facebook.com "Facebook"
 [3]: https://www.youtube.com/
- - -

- **Imágenes**: La manera de enlazar imágenes es básicamente la misma de crear enlaces, con un única diferencia, se añade el carácter exclamación ! al principio de la pareja de corchetes que definen el nombre del enlace.

Código:
~~~
![Texto alternativo](http://lorempixel.com/300/200/people/ "titulo")
~~~
Resultado:

![Texto alternativo](http://lorempixel.com/300/200/people/ "titulo")
- - -
Código:
~~~
![Texto alternativo][1]  ![Texto alternativo][2]

 [1]: http://lorempixel.com/300/200/people/1
 [2]: http://lorempixel.com/300/200/people/2 "Personas"
~~~
Resultado:

![Texto alternativo][1]  ![Texto alternativo][2]

 [1]: http://lorempixel.com/300/200/people/1
 [2]: http://lorempixel.com/300/200/people/2 "Personas"
 - - -

 - **LIstas**: Markdown permite crear dos tipos de listas, ordenadas y desordenadas, es decir numeradas o listas de puntos. Para distinguir los tipos y como se crean, nada mejor que verlo con ejemplos:

 Código:

~~~
Esto es una lista ordenada

1. Primer elemento
2. Segundo elemento
3. Tercer elemento
~~~
Resultado:

Esto es una lista ordenada

1. Primer elemento
2. Segundo elemento
3. Tercer elemento
- - -

Código:
~~~
Esto es una lista desordenada

- Primer elemento
- Segundo elemento
- Tercer elemento
~~~
Resultado:

Esto es una lista desordenada

- Primer elemento
- Segundo elemento
- Tercer elemento
- - -
