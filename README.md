# Instagram feed con Bootstrap

Creando una landing page similar a Instagram usando solamente Boostrap.

### Pre-requisitos 📋

1. Ordenador o dispositivo movil.
2. Programa donde copiar el repositorio. (Gitpod, VisualStudioCode, Pycharm ....)
3. Navegador web donde visualizar el resultado del codigo.


## Construido con 🛠️

* [HTML5] - Base del Front-end
* [CSS3]
* [Fontawesome](https://fontawesome.com/) - Iconos utilizados

## Deployment

Para lanzar este proyecto introducir en la consola:

```bash
  pip3 install flask && python server.py
```


## Estructura y explicación del codigo ⚙️

* Creación de un post similar a Instagram basado en html y css puro sin bootstrap.
* Se inserta un div unico clase post en el body ya que solo vamos a tener un post. SI fueran mas se crearia un div contenedor padre. 
* El div post se divide en 3 div de clases: post-header , post-image , post-body.
* El post-header incluye un icono de HTML5 el titulo del post y un icono final de config. Se utiliza un flex para agruparlos horizontalmente y al titulo del post #name se le otorga un grow 3 para desplazar el icono config al final.
* En post-image se inserta una foto y se le otorga un cover sobre el contenedor padre.
* Para el post-body se utiliza un display block. Los iconos se insertan en un div padre post-icons y al ultimo se le hace float a la derecha. Para el texto insertado en los <p> se utiliza 'word-break: break-all' en el div padre para justificar el texto al tamaño del contenedor.


## Autor ✒️

* **Jose Luis Gil** - *Ejercicio completo* - [JoseLike](https://github.com/JoseLike)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/JoseLike/excuse-generator/contributors) quíenes han participado en este proyecto. 