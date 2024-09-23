# Documentación de Uso de Markdown

Markdown es un lenguaje de marcado ligero que permite formatear texto de manera simple y eficiente. Se utiliza comúnmente para crear archivos README, escribir documentación y formatear texto en plataformas como GitHub, StackOverflow, entre otras.

A continuación, veremos las características más comunes de Markdown, como texto formateado, listas, tablas, imágenes, enlaces y bloques de código.

---

## Texto Formateado

Markdown permite aplicar varios tipos de formato al texto:

- **Negrita**: se utiliza `**texto**` para poner en **negrita**.
- *Cursiva*: se utiliza `*texto*` para poner en *cursiva*.
- ~~Tachado~~: se utiliza `~~texto~~` para tachar el texto.
- `Código en línea`: se utiliza una sola tilde invertida (`` ` ``) para formatear el texto como `código en línea`.

Ejemplos:

- **Este texto está en negrita**
- *Este texto está en cursiva*
- ~~Este texto está tachado~~
- Este es `código en línea`


## Listas

### Lista no ordenada:
Para crear una lista no ordenada hay que utilizar `-` seguido de un espacio.
Ejemplo:

- Elemento 1
- Elemento 2
  - Sub-Elemento 2.1
  - Sub-Elemento 2.2

### Lista ordenada:
Para crear una lista ordenada hay que utillizar numeros seguidos de un punto `1.`.
Ejemplo:

1. Primer Elemento
2. Segundo Elemento
3. Tercer Elemento

## Tablas.
Puedes crear tablas utilizando pipes `|` para separar las columnas y guiones `-` para dividir los encabezados de las filas.
Ejemplo:

| Característica    | Descripción          |
| ----------------- | -------------------- |
| **Negrita**       | Formato en negrita   |
| *Cursiva*         | Formato en cursiva   |
| ~~Tachado~~       | Texto tachado        |
| `Línea de código` | `Código`             |

## Imágenes.
Para insertar imágenes en Markdown, utiliza la siguiente sintaxis:

![Texto alternativo](URL de la imagen)

Ejemplo:
![Ejemplo de Imagen](imagen3.png)

## Enlaces.
Para insertar enlaces, se utiliza la siguiente sintaxis:
[Texto del enlace](URL del enlace)

Ejemplo:
[Visita GitHub](https://github.com)

## Bloque de código.
Para mostrar bloques de código, puedes utilizar tres tildes invertidas antes y después del bloque de código.
Para mostrar solo una línea de código se utiliza solo una tilde invertida antes y después de la línea de código.

Ejemplo:
` Línea de código `

``` int num = 2;
	int num_pos = 0;
	if (num >= 0) {
		int num_pos++;
	} ```

