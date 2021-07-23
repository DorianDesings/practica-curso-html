# :beginner: Práctica de sección de contenido

[Inicio |](/README.md) [Anterior |](4_tipos_de_header.md) [Siguiente](6_tipos_de_articles.md)

## Tipos de section

Recordemos que section es un contenedor genérico que agrupa contenido que está relacionado. 
El contenido del elemento section debería ser temático, por lo que sería incorrecto emplearlo de forma genérica para agrupar piezas no relacionadas con el contenido.
Cuando creamos bloques cuyo contenido es parte de un bloque total usaremos section.

*Nota: section también puede contener header o header y footer, los cuales son opcionales. Pero SÏ debe contener al menos un heading, título de sección.* 

### Section con heading y contenido
```html
<section>
    <h2>Título de la sección</h2>
    <p>contenido del texto</p>
</section>
```

### Section con header (que contiene un heading) y contenido

```html
<section>
    <header>
        <h2>Título de la sección</h2>
    </header>
    <p>contenido del texto</p>
</section>
```

### Section con header (que contiene un heading), contenido y footer de sección.

```html
<section>
    <header>
        <h2>Título de la sección</h2>
    </header>
    <p>contenido del texto</p>
    <footer>Pie de sección</footer>
</section>
```

#### Anidamiento

Un section puede contener articles, por ejemplo, si tenemos varios artículos que hablan sobre noticias, es contenido relacionado entre sí donde los articles serían cada una de las noticias que contiene el section. Y usamos artcile porque podríamos leer cada noticia sin haber leido el resto, y seguiría teniendo sentido.

Un section también puede anidar otros sections como por ejemplo, para definir características referentes a un tema particular. 
Un section global seria sobre animales donde podriamos incluir cada animal en otro section para brindar más información sobre ese animal (Animales > Elefante > Características)
 

---

![youtube logo](/assets/youtube_logo_30.png) [#16 Práctica de sección de contenido _ Curso de HTML 2020/2021](https://youtu.be/67gV0jmgbUc)


![github logo](/assets/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---

[Inicio |](/README.md) [Anterior |](4_tipos_de_header.md) [Siguiente](6_tipos_de_articles.md)
