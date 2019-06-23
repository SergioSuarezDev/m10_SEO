# Módulo 10 SEO - Sergio Suárez


## https - Se activan un certificado
El protocolo seguro ayuda a que se indexe mejor la pagina en google.

## Robots.txt
Se añade un robots.txt  que proporciona información a los rastreadores de busqueda.

## SITEMAP

Permite optimizar el SEO de un sitio web ya que informa a Google y otros motores de búsqueda sobre la organización y la jerarquía del contenido y permite que los buscadores rastreen el sitio de forma más inteligente.

## Se añaden Metas Fundamentales de OpenGraph
<!-- Open Graph data -->
<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# article:
http://ogp.me/ns/article#">
<meta property="og:title" content="Your Title Here" />
<meta property="og:type" content="article" />
<meta property="og:url" content="https://example.com/" />
<meta property="og:image" content="https://example.com/image.jpg" /> 
<meta property="og:description" content="Your Description Here" /> 
<meta property="og:site_name" content="Your Site Name, i.e. Moz" /> 
<meta property="fb:app_id" content="Your FB_APP_ID" />


## Cambios en la estructura

En cuanto a la estructura del HTML, los cambios realizados fueron los siguientes:

- Se cambian los secgtion por article.
- Se quitan divs, segun lo comentado por el  profesor, que no haya demasiados.
- Se unifica la barra de busqueda en una sola, no usar 2 distintas.


## Microdatos

- En el `<section id="quien-soy">` se usó el esquema `Person` y los atributos `image, description, name`

- En el `<section id="estudios">` se usó el esquema `School` y los atributos `logo, description, name, url` para englobar a la escuela de programación Keepcoding. Y se usó el esquema `CollegeOrUniversity` y los atributos y los atributos `logo, description, name, url` para englobar la Universidad Politécnica de Madrid

- En el `<section id="experiencia">` se usó el esquema `Organization` y los atributos `name, url, logo` para englobar a la compañía y dentro se usó el esquema `OrganizationRole` y los atributos `roleName, description` para englobar el rol dentro de la compañía

- En el `<section id="sobre-mi">` se usó el esquema `MediaObject` y el atributo `contentUrl` para englobar al video

- En el `footer` se usó el esquema `CreativeWork` y el atributo `copyrightHolder` para englobar el copyright de la página web

#### GOOGLE WEBMASTER TOOLS

Verficamos la propiedad del sitio web

Y comprobamos que indexamos todo lo que enviamos tenemos la herramienta GOOGLE WEBMASTER TOOL
