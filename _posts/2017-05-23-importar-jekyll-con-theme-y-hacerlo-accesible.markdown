---
title:  "Importar Jekyll con Theme desde GitHub y hacerlo accesible"
date:   2017-05-23 14:48:00
categories: [jekyll]
tags: [jekyll]
---

Paso a seguir para crear un blog Jekyll sin ponerlo como principal de modo http://<usuario>.github.io

1.- Hacemos fork en nuestro usuario de github.com
2.- Navegamos a la carpeta donde queremos importar el proyecto
3.- Traemos a local con 

`git clone https://github.com/<usuario>/cards-jekyll-template.git`

4.- En /cards-jekyll-template se ha generado la carpeta de proyecto
5.- Accedemos a la carpeta
6.- Creamos un nuevo branch 'gh-pages' con el contenido de master y switch con:

`git checkout -b gh-pages`

7.- Hacemos push para meterlo en nuestra cuenta.

`git push`

8.- Accediendo a https://<usuario>.github.io/cards-jekyll-template
