
Código en Bloque:
_________________

_para indicar código en bloque, es decir, que un párrafo ó bloque de contenido debe de interpretarse como si fuese código html, js, otros 

_debemos de anteponer ha éste contenido tres backtips, ó ```, y tres backtips ``` al final del contenido para que así, éste contenido sea interpretado como código en bloque por markdown, ej;


```el siguiente contenido debe ser interpretado como código en bloque dentro de markdown el cuál, a su vez, será enmarcado dentro de tags, ó etiquetas <code></code>, para su exportación html, posteriormente, de ésta manera, ahora podré definir una función javscript, por ejemplo; function demo(){alert('Hola mundo');}```

_pero incluso tendremos la posibilidad de indicar el lenguaje ha interpretar para que así, markdown, coloree y tome en cuenta las características propias del lenguaje

_para lo cuál, debemos de indicar el nombre del lenguaje seguido de las comillas invertidas iniciales, ej;

```javascript

function demo(){console.log('Saludar');}
```

_éste paso lo que hará es que markdown, enmarque el contenido dentro de una etiqueta ó tag, <pre></pre>, y dentro de éstas a su vez, una etiquetas ó tags, <code></code>

_quedando el contenido de la siguiente manera, de cara al html;

    <pre><code>contenido</code></pre>








