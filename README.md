# 25-web-sur-f
## Table of Contents

* [Repositorio en GitHub](#repositorio)
* [Comandos básicos](#comandos)


## Repositorio
[Repositorio para ejercicios ](https://github.com/gmglln/25-web-sur-f)


## Comandos

Te dejo una breve lista de comandos básicos de Git/Github

``` bash
# inicializa un repositorio existente.
$git init 


# agrega archivos al staging-area
$git add 


# nuevo commit con los archivos del staging-area
$git commit 


# muestra el estado actual del repositorio
$git status


# muestra el historial de commits del repositorio
$git log


# muestra, crea o elimina ramas (
$git branch


# cambia de rama o restaura archivos
$git checkout


# fusiona una rama con otra rama activa.
$git merge


# clone w https - usr/password
#git clone <repositorio> <nombre-carpeta>
$git clone https://github.com/gmglln/25-web-sur-f


# clone w ssh - ssh key
$git clone git@github.com:gmglln/25-web-sur-f.git


# entry to project
$ cd 25-web-sur-f


# obtiene cabios desde el repo remoto
$git pull


# envía los cambios locales al repositorio remoto
$git push


# envía los cambios locales al repositorio remoto
$git push

```


## CSS documentación
La documentación oficial de CSS (Cascading Style Sheets) se puede encontrar en el sitio web de la W3C (World Wide Web Consortium), la organización encargada de establecer los estándares web.

* [Documentación oficial](https://www.w3.org/TR/CSS21/)
* [CSS Mozila](https://developer.mozilla.org/es/docs/Web/CSS)

## Cómo vincular CSS con HTML
``` bash
<link rel="stylesheet" type="text/css" href="style.css">
```

## Selectores

1. Selector de etiqueta
2. Selector de clase
3. Selector de ID
4. Selector de descendiente
5. Selector de atributo
6. Selector universal
7. Selector de pseudo-clase

``` css
/* Etiqueta */
p {
  color: red;
}
```

``` css
/* Clase */
.clase {
  font-weight: bold;
}
```

``` css
/* Id */
#id {
  background-color: yellow;
}
```

``` css
/* Descendientes */
div p {
  font-size: 16px;
}
```

``` css
/* Atributo */
[type="text"] {
  border: 1px solid black;
}
```

``` css
/* Universal */
* {
  margin: 0;
  padding: 0;
}
```


``` css
/* pseudo-clase: */
a:hover {
  color: blue;
}

```

## Box model

Básicamente, el box model considera que cada elemento HTML es un cuadro (o box) rectangular que contiene el contenido, el relleno (padding), el borde (border) y el margen (margin) del elemento.

propiedades del box model: 

``` css
- width (ancho),
- height (alto),
- padding (relleno),
- border (borde)
- margin (margen)
- color: blue
```

## Float 
El float es una propiedad CSS que se utiliza para posicionar elementos en una página web.


## Position 
La propiedad position en CSS se utiliza para controlar la posición de un elemento en una página web.


## Flexbox (pendiente)
## Grid (pendiente)