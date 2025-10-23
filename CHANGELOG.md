# Change Log

All notable changes to the "mclibre-org-snippets" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## 0.5.0 (2025-10-23)
- Añado Snippet mc5: Este snippet debería utilizarse en bloques pre de ficheros HTML. Pega el contenido del portapapeles (el contenido del portpapeles debería ser código fuente HTML copiado de alguna página web), sustituyendo los caracteres '&' por &amp;, '>' por &gt; y '<' por &lt;. Yo lo utilizo cuando creo un ejemplo de código fuente HTML en los apuntes, para que se vean las etiquetas como texto.
- Modifico atajo de teclado del Snippet mc4 a ctrl+alt+v ctrl+alt+d.
- Añado atajo de teclado ctrl+alt+v ctrl+alt+e para el Snippet mc5.

## 0.4.0 (2025-10-07)
- Corrijo expresión regular "Pega HTML en PHP (líneas)" para que funcione en Firefox cuando copio usando el botón de Prism (https://github.com/PrismJS/prism/issues/3303).
- Añado Snippet mc4: Este snippet debería utilizarse en bloques pre de ficheros HTML. Pega el contenido del portapapeles (el contenido del portpapeles debería ser código fuente HTML copiado de alguna página web), sustituyendo los caracteres '>' por &gt; y '<' por &lt;. Yo lo utilizo cuando creo un ejemplo de código fuente HTML en los apuntes, para que se vean las etiquetas como texto.
- Añado atajo de teclado ctrl+alt+v ctrl+alt+e para el Snippet mc4.

## 0.3.0 (2019-10-10)
- Corrijo Expresión regular para que sea compatible con Visual Studio Code 1.39.

## 0.2.1 (2019-10-03)
- Corrijo enlace a repositorio.

## 0.2.0 (2019-10-03)
- Añado atajos de teclado.

## 0.1.0 (2019-10-03)
- Versión inicial.
- Snippet mc1: Este snippet debería utilizarse en ficheros PHP. Pega el contenido del portapapeles (el contenido del portpapeles debería ser código fuente HTML copiado de alguna página web), insertando un print por cada línea del código fuente y "escapando" en su caso las comillas del código fuente HTML.
- Snippet mc2: Este snippet debería utilizarse en ficheros PHP. Pega el contenido del portapapeles (el contenido del portpapeles debería ser código fuente HTML copiado de alguna página web), insertando un único print y "escapando" en su caso las comillas del código fuente HTML.
- Snippet mc3: Este snippet debería utilizarse en ficheros PHP. Pega el contenido del portapapeles (el contenido del portpapeles debería ser código fuente HTML copiado de alguna página web), "escapando" en su caso las comillas del código fuente HTML. Este snippet está pensado para pegar el código en una instrucción print ya existente.
