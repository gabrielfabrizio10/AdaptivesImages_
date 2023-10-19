# Imagenes Adaptables_
**¿Qué son las imagenes adaptables?** 

[![image.png](https://i.postimg.cc/Z5bdPmtN/image.png)](https://postimg.cc/YhP0kJS2)

Es la encargada de detectar el tamaño de pantalla de su visitante crea aparte de almacenar en caché y entregar automáticamente versiones reescaladas apropiadas para el dispositivo de las imágenes HTML incrustadas en su página web
|Adaptiva|Sensible|
  | :----------- | :----------- |
 |Crea plantillas que son óptimas y únicas para cada clase de dispositivo|Diseño único que fluye a través de la pantalla|
 |Del lado del cliente|Del lado del server|
 |Rejillas de Fluidos|Diseños Predefinidos|
 |Los servidores utilizan HTML que está preseleccionado para diferentes dispositivos|La cuadrícula es flexible y las imágenes tienen el tamaño correcto para la pantalla del dispositivo|

Si queremos solucionar el cambio de resolución? Queremos mostrar la misma imagen, más grande o más pequeña dependiendo del dispositivo
Deberiamos usar un codigo


[![image.png](https://i.postimg.cc/pTSywc2D/image.png)](https://postimg.cc/k6xn8cR4)


Así, podemos utilizar dos nuevos atributos — srcset y sizes 
srcset define el conjunto de imágenes que el navegador podrá elegir, y el tamaño de cada imagen, Cada conjunto de información de imagen está separado del anterior por una coma.

sizes define un conjunto de condiciones de medios (por ejemplo, anchos de pantalla) e indica qué tamaño de imagen sería mejor elegir cuando se cumplen ciertas condiciones de medios — estas son las sugerencias de las que hablamos anterriormente. En este caso, antes de cada coma escribimos:


[![image.png](https://i.postimg.cc/DfDbH0Zt/image.png)](https://postimg.cc/xqvCb0LR)
  
Así nos quedaria dependiendo la imagen que pongamos


[![image.png](https://i.postimg.cc/XqVGcB7P/image.png)](https://postimg.cc/tZM49T6d)


[![image.png](https://i.postimg.cc/jS1SWYst/image.png)](https://postimg.cc/18pQTTnj)

Tutorial adicional de como hacerlo:

https://youtube.com/shorts/8Rc18lfl68c?si=5jIfVwrCuR0cJCs9
