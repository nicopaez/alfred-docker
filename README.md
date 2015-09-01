# alfred-docker

Este repositorio contiene diversas configuraciones para correr contenedores de Alfred.

* images: contiene los Dockerfiles para crear las imagenes de alfred. En este momento contiene solo la configuración para generar una imagen de la capa web ya que el contenedor de base de datos se genera a partir de imagen postgresql oficial.
* compose: contiene una configuración para la herramienta compose para levantar conjuntamente ambas contenedores (db y web)
