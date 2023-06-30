# Repaso de HTML

Este es un breve repaso de HTML (HyperText Markup Language) que cubre los conceptos básicos y las etiquetas fundamentales utilizadas para crear páginas web. HTML es el lenguaje estándar para estructurar y presentar contenido en la web.

## Tabla de contenidos

1. [Introducción a HTML](#introducción-a-html)
2. [Estructura básica de un documento HTML](#estructura-básica-de-un-documento-html)
3. [Etiquetas básicas de HTML](#etiquetas-básicas-de-html)
4. [Etiquetas de formato de texto](#etiquetas-de-formato-de-texto)
5. [Enlaces](#enlaces)
6. [Imágenes](#imágenes)
7. [Listas](#listas)
8. [Tablas](#tablas)
9. [Formularios](#formularios)

## Introducción a HTML

HTML es un lenguaje de marcado que utiliza etiquetas para estructurar y dar formato al contenido de una página web. Cada etiqueta tiene un propósito específico y se utiliza para representar diferentes tipos de elementos en una página.

## Estructura básica de un documento HTML

Un documento HTML sigue una estructura básica compuesta por las siguientes etiquetas:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Título de la página</title>
</head>
<body>
    <!-- Contenido de la página -->
</body>
</html>
```

- `<!DOCTYPE html>`: Define el tipo de documento como HTML5.
- `<html>`: Envuelve todo el contenido de la página HTML.
- `<head>`: Contiene información sobre el documento, como el título de la página y enlaces a archivos externos.
- `<title>`: Define el título de la página que se muestra en la pestaña del navegador.
- `<body>`: Contiene el contenido visible de la página.

## Etiquetas básicas de HTML

Aquí hay algunas etiquetas básicas de HTML que se utilizan comúnmente:

- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`: Encabezados de diferentes niveles.
- `<p>`: Párrafos de texto.
- `<a>`: Enlaces.
- `<img>`: Imágenes.
- `<ul>`: Lista desordenada.
- `<ol>`: Lista ordenada.
- `<li>`: Elemento de lista.
- `<div>`: Contenedor genérico.
- `<span>`: Contenedor de texto genérico.
- `<table>`: Tabla.
- `<tr>`: Fila de tabla.
- `<td>`: Celda de tabla.

## Etiquetas de formato de texto

HTML ofrece etiquetas para dar formato al texto, como:

- `<strong>`: Texto en negrita.
- `<em>`: Texto en cursiva.
- `<u>`: Texto subrayado.
- `<br>`: Salto de línea.
- `<hr>`: Línea horizontal.

## Enlaces

Los enlaces permiten navegar entre páginas web. Se crean utilizando la etiqueta `<a>` y el atributo `href` para especificar la URL de destino.

```html
<a href="https://www.ejemplo.com">Enlace a Ejemplo</a>
```

## Imágenes

Las imágenes se insertan en una página utilizando la etiqueta `<img>` y el atributo `src`

 para especificar la ruta de la imagen.

```html
<img src="ruta/imagen.jpg" alt="Descripción de la imagen">
```

## Listas

Hay dos tipos principales de listas en HTML: listas desordenadas (`<ul>`) y listas ordenadas (`<ol>`). Los elementos de la lista se definen con la etiqueta `<li>`.

```html
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ul>

<ol>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ol>
```

## Tablas

Las tablas se crean utilizando la etiqueta `<table>`. Las filas se definen con la etiqueta `<tr>`, y las celdas se definen con la etiqueta `<td>`.

```html
<table>
    <tr>
        <td>Celda 1</td>
        <td>Celda 2</td>
    </tr>
    <tr>
        <td>Celda 3</td>
        <td>Celda 4</td>
    </tr>
</table>
```

## Formularios

Los formularios permiten recopilar datos de los usuarios. Se crean utilizando la etiqueta `<form>`, y los campos del formulario se definen con etiquetas como `<input>`, `<select>`, `<textarea>`, entre otras.

```html
<form action="/submit" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    
    <input type="submit" value="Enviar">
</form>
```

Este repaso cubre solo los conceptos básicos de HTML. Hay muchas más etiquetas y atributos disponibles para construir páginas web más complejas.
