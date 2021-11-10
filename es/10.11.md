---
Text: texto
Hello: Hola
---

<a href="https://gitlocalize.com/repo/4578/ru?utm_source=badge"> <img src="https://gitlocalize.com/repo/4578/ru/badge.svg"> </a>

# ![Logotipo de Markdown Here](https://raw.github.com/adam-p/markdown-here/master/src/common/images/icon48.png) Markdown aquí

[**Visita el sitio web.**](http://markdown-here.com)<br>[**Consíguelo para Chrome.**](https://chrome.google.com/webstore/detail/elifhakcjgalahccnjkneoccemfahfoa)<br>[**Consíguelo para Firefox.**](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/)<br>[**Consíguelo para Safari.**](https://s3.amazonaws.com/markdown-here/markdown-here.safariextz)<br>[**Consíguelo para Thunderbird y Postbox.**](https://addons.mozilla.org/en-US/thunderbird/addon/markdown-here/)<br>[**Consíguelo para Opera.**](https://addons.opera.com/en/extensions/details/markdown-here/)<br>[**Discuta y haga preguntas en el Grupo de Google.**](https://groups.google.com/forum/?fromgroups#!forum/markdown-here/)<br>

*Markdown Aquí* hay una extensión de Google Chrome, Firefox, Safari, Opera y Thunderbird que le permite escribir correos electrónicos <sup>†</sup> en Markdown <sup>‡</sup> y procesarlos antes de enviarlos. También admite el resaltado de sintaxis (solo especifique el idioma en un bloque de código delimitado).

Escribir un correo electrónico con código es bastante tedioso. Escribir Markdown con código es fácil. Me encontré escribiendo un correo electrónico en Markdown en el editor del navegador de Github y luego copiando la vista previa en el correo electrónico. Este es un flujo de trabajo bastante absurdo, así que decidí crear una herramienta para escribir y renderizar Markdown directamente en el correo electrónico.

Para descubrir qué se puede hacer con Markdown en *Markdown Here* , consulte la[hoja de referencia de Markdown Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) y las otras [páginas de la wiki](https://github.com/adam-p/markdown-here/wiki) .

<sup>†: ¡Y publicaciones de Grupos de Google, publicaciones de Blogger, notas de Evernote y publicaciones de Wordpress! <a href="#compatibility">Ver más</a></sup><br><sup>‡: ¡Y fórmulas matemáticas TeX!</sup>

![captura de pantalla de la conversión](https://raw.github.com/adam-p/markdown-here/master/store-assets/markdown-here-image1.gimp.png)

### Tabla de contenido

**[Instrucciones de instalación](#installation-instructions)**<br>**[Instrucciones de uso](#usage-instructions)**<br>**[Solución de problemas](#troubleshooting)**<br>**[Compatibilidad](#compatibility)**<br>**[Notas y varios](#notes-and-miscellaneous)**<br>**[Construyendo los paquetes de extensión](#building-the-extension-bundles)**<br>**[Pasos siguientes, créditos, comentarios, licencia](#next-steps)**<br>

## Instrucciones de instalación

### Cromo

#### Tienda virtual de Chrome

Vaya a la [página de Chrome Web Store para *Markdown Here*](https://chrome.google.com/webstore/detail/elifhakcjgalahccnjkneoccemfahfoa) e instálelo normalmente.

Después de la instalación, asegúrese de volver a cargar su correo web o reiniciar Chrome.

#### Manual / Desarrollo

1. Clona este repositorio.
2. En Chrome, abra la configuración de Extensiones. (Botón de llave inglesa, herramientas, extensiones).
3. En la página de configuración de Extensiones, haga clic en la casilla de verificación "Modo de desarrollador".
4. Haga clic en el botón "Cargar extensión descomprimida ..." ahora visible. Navegue al directorio donde clonó el repositorio, luego al `src` debajo de ese.
5. La *extensión Markdown Here* ahora debería estar visible en su lista de extensiones.
6. Vuelva a cargar su página de correo web (y tal vez la aplicación) antes de intentar convertir un correo electrónico.

### Firefox y Thunderbird

#### Sitio de complementos de Mozilla

Vaya a la [página de complementos de Firefox para *Markdown Here*](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/) e instálelo normalmente.

O vaya al menú "Herramientas&gt; Complementos" y luego busque "Markdown Here".

Después de la instalación, asegúrese de reiniciar Firefox / Thunderbird.

**Nota:** Mozilla tarda hasta un mes en aprobar los cambios en la extensión de Firefox / Thunderbird, por lo que las actualizaciones (funciones, correcciones) se retrasarán con respecto a lo que se muestra aquí. Puede elegir instalar manualmente la versión más reciente antes de que se revise de la lista de versiones: [https://addons.mozilla.org/en-US/firefox/addon/markdown-here/versions/](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/versions/)

#### Manual / Desarrollo

1. Clona este repositorio.
2. Siga las instrucciones del artículo de MDN ["Configuración de un entorno de desarrollo de extensiones"](https://developer.mozilla.org/en/Setting_up_extension_development_environment) .

### Safari

[Descarga la extensión directamente.](https://s3.amazonaws.com/markdown-here/markdown-here.safariextz) Cuando haya terminado de descargarse, haga doble clic en él para instalarlo.

#### Preferencias

Para acceder a las preferencias de Markdown Here, abra las preferencias de Safari y luego vaya a la pestaña "Extensiones". Luego haga clic en el cuadro "Haga clic en mí para mostrar las opciones de Markdown Here".

### Ópera

Tenga en cuenta que *Markdown Here* solo funciona con las versiones 16 de Opera y superiores (es decir, las que están basadas en Chromium).

Vaya a la [página de la tienda de complementos de Opera para *Markdown Here*](https://addons.opera.com/en/extensions/details/markdown-here/) e instálelo normalmente.

Después de la instalación, asegúrese de volver a cargar su correo web o reiniciar Chrome.

## Instrucciones de uso

Instálelo y luego ...

1. En Chrome / Safari / Opera, *asegúrese de* volver a cargar su página de correo web antes de intentar usar Markdown Here.

2. En Chrome / Firefox / Safari / Opera, inicie sesión en su cuenta de Gmail, Hotmail o Yahoo y comience un nuevo correo electrónico. En Thunderbird, inicie un nuevo mensaje.

3. Asegúrate de estar usando el editor enriquecido.

    - En Gmail, haga clic en el vínculo "Formato enriquecido", si está visible.
    - En Thunderbird, asegúrese de que la opción "Redactar mensajes en formato HTML" esté habilitada en el panel "Configuración de la cuenta", "Composición y direcciones".

4. Redacte un correo electrónico en Markdown. Por ejemplo:

    <pre>   **Hello** `world`.

       ```javascript
       alert('Hello syntax highlighting.');
       ```
       </pre>

5. Haga clic con el botón derecho en el cuadro de redacción y elija el elemento "Alternar Markdown" en el menú contextual. O haz clic en el botón que aparece en tu barra de direcciones. O use la tecla de <kbd>acceso</kbd> rápido (CTRL + <kbd>ALT</kbd> + <kbd>M</kbd> por defecto).

6. Debería ver su correo electrónico procesado correctamente desde Markdown en HTML enriquecido.

7. Envíe su increíble correo electrónico a todos los que conoce. A ellos les parecerá de la misma manera que a usted.

### Volver a Markdown

Después de convertir su Markdown en HTML bonito, aún puede volver a su Markdown original. Simplemente haga clic con el botón derecho en cualquier parte del Markdown recién renderizado y haga clic en "Alternar Markdown": el cuerpo de redacción de su correo electrónico volverá al Markdown que había escrito.

Tenga en cuenta que cualquier cambio que realice en el bonito HTML se perderá cuando vuelva a Markdown.

En Gmail, también puede usar el comando Deshacer del navegador ( <kbd>CTRL</kbd> + <kbd>Z</kbd> / <kbd>CMD</kbd> + <kbd>Z</kbd> , o desde el menú Editar). Tenga en cuenta que también puede perder los últimos caracteres que ingresó.

### Respuestas

En Gmail, Thunderbird y Grupos de Google, puede usar "Markdown Toggle" normalmente: simplemente escriba su respuesta (arriba, abajo, en línea, donde sea) y luego convierta. El correo electrónico original al que está respondiendo se dejará solo. (Técnicamente: los `blockquote` bloque existentes se dejarán intactos).

En Hotmail y Yahoo (que no ponen el original en una `blockquote` en bloque) y, opcionalmente, en Gmail, Thunderbird y Grupos de Google, puede asegurarse de que solo la parte de la respuesta que escribió se convierta seleccionando lo que desea convertir. y luego haga clic en "Alternar Markdown" - vea la siguiente sección.

### Selección / Conversión por etapas

A veces, no desea convertir todo el correo electrónico; a veces su correo electrónico no es completamente Markdown. Para convertir solo una parte del correo electrónico, seleccione el texto (con el mouse o el teclado), haga clic derecho sobre él y haga clic en el elemento de menú "Alternar Markdown". Su selección se representa mágicamente en un bonito HTML.

Para volver a Markdown, simplemente coloque el cursor en cualquier lugar del bloque de texto convertido, haga clic con el botón derecho y vuelva a hacer clic en el elemento de menú "Alternar Markdown". Ahora vuelve mágicamente al Markdown original.

![captura de pantalla de la conversión de selección](https://raw.github.com/adam-p/markdown-here/master/store-assets/markdown-here-image2.gimp.png)

#### Cosas que debe saber sobre la conversión / reversión de una selección

- Si selecciona solo una parte de un bloque de texto, solo se convertirá ese texto. El bloque convertido se incluirá en un elemento de párrafo, por lo que la línea original se dividirá. Probablemente no quieras hacer esto nunca.

- Puede seleccionar y revertir varios bloques convertidos al mismo tiempo. Un resultado de esto es que puede seleccionar todo su correo electrónico, hacer clic en "Alternar Markdown", y todas las partes que había convertido se revertirán.

- Si no tiene nada seleccionado cuando hace clic en "Alternar Markdown", *Markdown Here* comprobará si hay bloques convertidos en algún lugar del mensaje y los revertirá. Si no se encuentran bloques convertidos, convertirá todo el correo electrónico.

### Opciones

Se *puede acceder a la página de opciones de Markdown Here* a través de la lista de extensiones de Chrome, Firefox, Safari o Thunderbird. Las opciones disponibles incluyen:

- Modificaciones de estilo para el Markdown renderizado.
- Sintaxis que resalta la selección y modificación del tema.
- Habilitación y personalización del procesamiento de fórmulas matemáticas TeX.
- Cuál debería ser la tecla de acceso rápido.

Para Chrome y Firefox, cualquier cambio realizado en las *opciones de Markdown Here* se sincroniza automáticamente entre sus otras instalaciones de ese navegador (si tiene la función de sincronización habilitada en el navegador).

![captura de pantalla de opciones](https://raw.githubusercontent.com/adam-p/markdown-here/master/store-assets/markdown-here-chrome-options-1.gimp.png)

## Solución de problemas

Consulte la [página wiki de resolución de problemas](https://github.com/adam-p/markdown-here/wiki/Troubleshooting) .

## Compatibilidad

Consulte la [página wiki de compatibilidad](https://github.com/adam-p/markdown-here/wiki/Compatibility) .

## Notas y varios

- *Markdown Here* usa [Github Flavored Markdown](http://github.github.com/github-flavored-markdown/) , con la limitación de que los enlaces especiales de GFM no son compatibles ( [número 11](https://github.com/adam-p/markdown-here/issues/11) ); ni lo serán, ya que MDH no es específico de Github.

- Los idiomas disponibles para el resaltado de sintaxis (y la forma en que deben escribirse en el bloque de código delimitado) se pueden ver en la [página de demostración de highlight.js](http://softwaremaniacs.org/media/soft/highlight/test.html) .

- Las imágenes incrustadas en línea en su Markdown se conservarán cuando "Markdown Toggle". Gmail le permite poner imágenes en línea en su correo electrónico; esto puede ser mucho más fácil que hacer referencia a una imagen externa.

- Las firmas de correo electrónico se excluyen automáticamente de la conversión. Específicamente, cualquier cosa después del semi-estándar `'-- '` (observe el espacio final) se deja solo.

    - Tenga en cuenta que Hotmail y Yahoo *no* agregan automáticamente el `'-- '` a las firmas, por lo que debe agregarlo usted mismo.

- El elemento de menú "Alternancia de Markdown" se muestra para más tipos de elementos de los que puede representar correctamente. Esto tiene como objetivo ayudar a las personas a darse cuenta de que no están usando un editor enriquecido. De lo contrario, simplemente no ven el elemento del menú y no saben por qué.

- Estilo:

    - Debe evitarse el uso de estilos específicos del navegador (-moz-, -webkit-). Si se utilizan, es posible que no se muestren correctamente para las personas que leen el correo electrónico en un navegador diferente al que se envió el correo electrónico.
    - El uso de estilos dependientes del estado (como `a:hover` ) no funciona porque no coinciden en el momento en que los estilos se hacen explícitos. (En el correo electrónico, los estilos deben aplicarse explícitamente a todos los elementos; las hojas de estilo se eliminan).

- Para obtener más funciones innovadoras, visite la sección [Consejos y trucos.](https://github.com/adam-p/markdown-here/wiki/Tips-and-Tricks)

## Construyendo los paquetes de extensión

```
cd utils
node build.js
```

### Extensión de Chrome y Opera

Cree un archivo con una `.zip` contenga estos archivos y directorios:

```
manifest.json
common/
chrome/
```

### Extensión de Firefox / Thunderbird

Cree un archivo con una `.xpi` contenga estos archivos y directorios:

```
chrome.manifest
install.rdf
common/
firefox/
```

### Extensión de Safari

El código específico del navegador se encuentra en el proyecto [`markdown-here-safari`](https://github.com/adam-p/markdown-here-safari) .

Utilice el Generador de extensiones de Safari.

## Próximos pasos

Consulte la [lista de problemas](https://github.com/adam-p/markdown-here/issues) y el [Wiki de Notes](https://github.com/adam-p/markdown-here/wiki/Development-Notes) . Todas las ideas, errores, planes, quejas y sueños terminarán en uno de esos dos lugares.

Siéntase libre de crear un problema de solicitud de función si lo que desea aún no está allí. Si prefieres un enfoque menos formal para hacer flotar una idea, publícala en el [Grupo de Google "markdown-here"](https://groups.google.com/forum/?fromgroups=#!forum/markdown-here) .

También se necesita un poco de trabajo para mantenerse al día con los últimos cambios en todas las aplicaciones y sitios web donde trabaja Markdown Here.

## Créditos

*Markdown Here* fue codificado en hombros de gigantes.

- Markdown-to-HTML: [chjj / marcado](https://github.com/chjj/marked)
- Resaltado de sintaxis: [isagalaev / highlight.js](https://github.com/isagalaev/highlight.js)
- HTML a texto: [mtrimpe / jsHtmlToText](https://github.com/mtrimpe/jsHtmlToText)

## Realimentación

Todos los errores, solicitudes de funciones, solicitudes de extracción, comentarios, etc., son bienvenidos. [Crea un problema](https://github.com/adam-p/markdown-here/issues) . O [publique en el grupo de Google "markdown-here"](https://groups.google.com/forum/?fromgroups=#!forum/markdown-here) .

## Licencia

### Código

Licencia MIT: http://adampritchard.mit-license.org/ o consulte [el archivo `LICENSE`](https://github.com/adam-p/markdown-here/blob/master/LICENSE) .

### Logo

Copyright 2015, [Austin Anderson](http://protractor.ninja/) . Licenciado a Markdown Here bajo el[acuerdo de licencia de colaborador de MDH](https://github.com/adam-p/markdown-here/blob/master/CLA-individual.md) .

### Otras imagenes

[Licencia Creative Commons Attribution 3.0 Unported (CC BY 3.0)](http://creativecommons.org/licenses/by/3.0/)

---

![El hombre de Dos Equis dice](https://raw.github.com/adam-p/markdown-here/master/store-assets/dos-equis-MDH.jpg)

- solicitudes de extracción
- También requiere bastante trabajo
- Licencia
- Error
- Código
