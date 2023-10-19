# AdaptivesImages_
**¿Qué son las imagenes adaptables?** 

[![image.png](https://i.postimg.cc/Z5bdPmtN/image.png)](https://postimg.cc/YhP0kJS2)

Es la encargada de detectar el tamaño de pantalla de su visitante crea aparte de almacenar en caché y entregar automáticamente versiones reescaladas apropiadas para el dispositivo de las imágenes HTML incrustadas de su página web
|Adaptiva|Sensible|
  | :----------- | :----------- |
 |crea plantillas que son óptimas y únicas para cada clase de dispositivo|Diseño único que fluye a través de la pantalla|
 |Del lado del cliente|Del lado del server|
 |Rejillas de Fluidos|Diseños Predefinidos|
 |Los servidores utilizan HTML que está preseleccionado para diferentes dispositivos|La cuadrícula es flexible y las imágenes tienen el tamaño correcto para la pantalla del dispositivo|

Si queremos solucionar el cambio de resolución? Queremos mostrar la misma imagen, más grande o más pequeña dependiendo del dispositivo
Deberiamos usar un codigo

<img src="elva-fairy-800w.jpg" alt="Elva dressed as a fairy" />

Así, podemos utilizar dos nuevos atributos — srcset y sizes — para proporcionar varias imágenes de origen adicionales junto con sugerencias para ayudar al navegador a elegir el correcto.
<img
  srcset="
    elva-fairy-320w.jpg 320w,
    elva-fairy-480w.jpg 480w,
    elva-fairy-800w.jpg 800w
  "
  sizes="(max-width: 320px) 280px,
            (max-width: 480px) 440px,
            800px"
  src="elva-fairy-800w.jpg"
  alt="Elva dressed as a fairy" />


[![image.png](https://i.postimg.cc/jS1SWYst/image.png)](https://postimg.cc/18pQTTnj)

Tutorial adicional de como hacerlo:

https://youtube.com/shorts/8Rc18lfl68c?si=5jIfVwrCuR0cJCs9
