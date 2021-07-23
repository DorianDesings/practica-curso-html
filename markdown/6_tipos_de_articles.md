# :beginner: Práctica de sección de contenido

[Inicio |](/README.md) [Anterior |](5_tipos_sections.md) [Siguiente](7_ejemplos.md)

## Tipos de articles

Article es un contenedor que respresenta contenido independiente, es decir, podemos leer ese fragmento en cualquier otro sitio y tendría sentido por sí mismo.

El elemento article es similar al elemento section pero la diferencia principal es mientras un section puede contener cualquier contenido que se pueda agrupar temáticamente, un article debe ser una solo pieza de contenido que pueda valerse por sí mismo, por ejemplo si un contenido se puede volver a publicar en otro sitio sin ser modificado o enviado como una actualización ( RSS, twitter, facebook), tiene cualidades de un article.

*Nota: article también puede contener header o header y footer, los cuales son opcionales. Pero SÏ debe contener al menos un heading, título de sección.* 

### Article con heading y contenido

```html
<article>
    <h2>Título de la sección</h2>
    <p>contenido del texto</p>
</article>
```

### Article con header (que contiene un heading) y contenido

```html
<article>
    <header>
        <h2>Título de la sección</h2>
    </header>
    <p>contenido del texto</p>
</article>
```

### Article con header (que contiene un heading), contenido y footer de sección.

El article es definido como un componente de la página de contenido independiente, esto implica que esta etiqueta pueda tener un header y un footer propios.

```html
<article>
    <header>
        <h2>Título de la sección</h2>
    </header>
    <p>contenido del texto</p>
    <footer>Pie de sección</footer>
</article>
```


#### Anidamiento


También existe el caso en el que un article contenga varias secciones, el artículo independiente podría ser navegadores y este contener dentro secciones como navegadores más utilizados en 2020


---

![youtube logo](/assets/youtube_logo_30.png) [#16 Práctica de sección de contenido _ Curso de HTML 2020/2021](https://youtu.be/67gV0jmgbUc)


![github logo](/assets/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---
[Inicio |](/README.md) [Anterior |](5_tipos_sections.md) [Siguiente](7_ejemplos.md)
