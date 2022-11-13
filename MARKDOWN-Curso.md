# Markdown

`archivo.md`

**Ctrl + shift + V** --> abrir el preview en VSC

<!-- ENCABEZADOS -->
# Encabezado 1
## Es un H2
### Y un H3
#### Encabezado 4
---

<!-- PARRAFOS -->
Esto es un parrafo markdown. Seguimos con escrituras.
Otra linea seguida.

Con salto de linea seguimos escribiendo

Las **NEGRITA** (strong) y las *CURSIVA* (italic), mas código `let saludo = "Hola Mundo"`

Texto ~~TACHADO~~ con el signo ~

> Cuadro remarcado con el signo >

___
<!-- lineas subdivision con --- o _ _ _ seguidos-->
## Lineas subdivision
`---`
`___`

---
<!-- LISTAS -->
## Lista ordenada OL

* Listas
* Listas
* Listas
<!-- sub item usando tab -->
* Listas
    * Lista
    * Lista
    - Lista

## Lista desordenada UL
1. Elemento1
2. Elemento2
3. Elemento3
4. Elemento4

___
<!-- CODIGOS -->
## Codigo

```js
const saludo = () => "Hola Cris";
```

```py
print("Hola Mundo")
```

```html
<h1>Titulo</h1>
<p>Parrafos</p>
```

```css
.class{
    width: 100px;
}
```

---
<!-- TABLAS -->
## Tablas

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

> ---- espacios , :--- alinear izq, ---: alinear der, :---: alinear centro

Link web [generador de tablas](https://www.tablesgenerator.com/markdown_tables)

---
<!-- LINKS enlaces-->
## Links `[nombre](direccion)`
Hemos encontrado una [imagen](https://justyy.com/wp-content/uploads/2016/01/markdown-syntax-language.png)

<!-- IMAGEN -->
## Imagen
![imagen](/markdown.png "ALT nombre alternativo de imagen")

> con solo agregarle el signo ! se mostrara, puedes utilizar la imagen o un link de la imagen web
---
## Emojis
Emojipedia [link](https://emojipedia.org/) 😎

<!-- Emojis en Github -->
Emojis [web emoji](https://emojis.github.io/)
😎  👍
___
<!-- GITHUB MARDOWN -->
TODO en GitHub, con x es tarea realizada

* [x] Tarea 1
* [ ] Tarea 2
* [ ] Tarea 3
* [x] Tarea 4

> Funciona en GitHub