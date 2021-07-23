# :beginner: Práctica de sección de contenido

[Inicio |](/README.md) [Anterior |](3_estructura.md) [Siguiente](5_tipos_sections.md)

## Tipos de header

Recordemos que el header se usa como introducción al contenido principal de la página. Suele contener un menú de navegación con enlaces para navegar por la página, un título principal del documento, un logo, etc.
De acuerdo a la práctica de sección de contenido encontramos las siguientes posibilidades de header y el contenido que contiene.

### Header con solo el menú de navegación
```html
<header>
    <nav>Inicio | Personajes | Comics | Solicitar información</nav>
</header>
```

### Header con el menú de navegación y el título principal del documento

```html    
<header>
    <nav>Inicio | Personajes | Comics | Solicitar información</nav>
    <h1>Los Vengadores (The Avengers)</h1>
</header>
```

### Header con el título principal del documento y menú de navegación

```html
<header>
    <h1>Los Vengadores (The Avengers)</h1>
    <nav>Inicio | Personajes | Comics | Solicitar información</nav>
</header>
```

### Header con título principal y menú de navegación con lista de enlaces

La forma correcta de crear el menú de navegación es la que contiene una lista de enlaces. Cada enlace hará referencia a la página a la que redirige el enlace. Recuerda que si no conduce a ningún lado se usa el símbolo # como referencia en el href.

*Nota: el header puede contener o no el título principal. Que el título principal se encuentre antes o después del menú de navegación varía según el diseño a seguir. Puede ser que el header tampoco contenga un título principal como vimos anteriormente.* 

```html
<header>
    <h1>Los Vengadores (The Avengers)</h1>
    <nav>
        <ul>
            <li><a href= "#">Inicio</a></li>
            <li><a href= "personajes.html">Personajes</a></li>
            <li><a href= "comics.html">Comics</a></li>
            <li><a href= "informacion.html">Solicitar información</a></li>
        </ul>    
    </nav>
</header>
```



---

![youtube logo](/assets/youtube_logo_30.png) [#16 Práctica de sección de contenido _ Curso de HTML 2020/2021](https://youtu.be/67gV0jmgbUc)


![github logo](/assets/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---
[Inicio |](/README.md) [Anterior |](3_estructura.md) [Siguiente](5_tipos_sections.md)
