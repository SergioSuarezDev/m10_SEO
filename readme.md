# Módulo 10 SEO - Sergio Suárez

## https - Se activa un certificado
El protocolo seguro ayuda a que se indexe mejor la pagina en google.

## Cambios en el codigo HTML

Cambios realizados en el codigo HRML

- Se optimiza el Title, por debajo de de 65 palabras.
- Se mejoran todos los H1, H2, H3, H4, H5 (Solo un H1 por página, y el resto debajo)
- Se añade figure y figcaption en las imágenes y se les pone un alt.
- Se mejoran todas las negritas
- Se cambian los section por article.
- Añadidos atributos title en los anchor con información sobre link.
- Se quitan divs, segun lo comentado por el  profesor, que no haya demasiados.
- Se unifica la barra de menú en uno solo, no usar 2 distintos. Y se añaden titulos. 
- Sobre los metakeywords: Google no las tiene en cuenta desde 2009, no se ponen.
- Se carga el javascript al final, para no ralentizar o permitir que no se cargue contenido si falla.


## Robots.txt
Se añade un robots.txt  que proporciona información a los rastreadores de busqueda.

## Sitemap

Permite optimizar el SEO de un sitio web ya que informa a Google y otros motores de búsqueda sobre la organización y la jerarquía del contenido y permite que los buscadores rastreen el sitio de forma más inteligente.

## Se añaden Metas Fundamentales de OpenGraph

<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# article:
http://ogp.me/ns/article#">
<meta property="og:title" content="Sergio Suarez CV" />
<meta property="og:type" content="article" />
<meta property="og:url" content="https://sergiosuarezdev.com" />
<meta property="og:image" content="https://sergiosuarezdev.com/assets/img/sergio.jpg" /> 
<meta property="og:description" content="CV De Sergio Suarez" /> 
<meta property="og:site_name" content="Sitio Web de Sergio Suarez" /> 
<meta property="fb:app_id" content="XXXXXXXX" />


## Microdatos

Se añaden microdatos en las secciones "quien", "estudios", "experiencia", "sobre" y "footer.
Todos ellos sacados de http://schema.org


## Google Search Console

Verificamos la propiedad del sitio web y comprobamos que indexamos todo lo que enviamos 

## Mas Mejoras - CDN

Seria muy buena idea tambien añadir todos los ficheros de video e imágenes a un CDN para mejorar la carga dependiendo de la situaxción geográfica del usuario.