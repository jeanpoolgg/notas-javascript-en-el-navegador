# 1. El DOMN

## El DOM
>Las siglas DOM significan Document Object Model, o lo que es lo mismo, la estructura del documento HTML. Una página HTML está formada por múltiples etiquetas HTML, anidadas una dentro de otra, formando un árbol de etiquetas relacionadas entre sí, que se denomina árbol DOM (o simplemente DOM).


En el DOM toda etiqueta es un objeto. Es decir, cada etiqueta HTML es un objeto en el DOM. Donde cada objeto puede tener hijos. El texto tambien se considera un hijo dentro del DOM.


El DOM parte del objeto **document** donde **document** es una variable global que representa un objeto que contiene todo lo que se ve dentro de la página web.

### Código

``````javascript
document
document.doctype
document.title
document.charset
document.head
    document.charset
    document.title
document.body
    document.links
    document.images
    document.images[10]
    document.forms
    document.getSelection()
    document.getSelection().anchorNode.data
    document.getSelection().toString()
document.scripts
document.scripts[0]
document.styleSheets
``````