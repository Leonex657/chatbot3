Aqui seguimos ocupando las librerias anteriores pero agregaremos mas, primero para dinferenciar el sistema operativo usado import plataform, import os para igual interactuar con este y import pyttsx3 este nos ayudara con lo de la voz, convirtiendo el texto a voz. a partir de aqui, para instalarlos es facil, como flet en la terminal. pondremos pip install pyttsx3, ya que es el unico que no viene instalado con python. En esta parte 3 agregamos todo lo investigado en una linea que sera la forma en que el bot hablara:
<img width="746" height="81" alt="image" src="https://github.com/user-attachments/assets/ad7f644a-a674-43ff-a2e7-179b3551b233" /> 
num_ctx
 Define cuánta información anterior (tokens) puede recordar el modelo.
 
  num_predict
Indica cuántos tokens puede generar como respuesta máxima


  temperature
Controla la creatividad o aleatoriedad del modelo.

0.2: más lógico, directo y repetitivo.

0.7: equilibrio entre precisión y creatividad.

1.0+: más libre y creativo, pero menos predecible.

  top_p
Controla el rango de probabilidad acumulada para seleccionar palabras

  repeat_penalty
Penaliza que el modelo repita las mismas palabras o frases.

  KEEP_ALIVE
Controla cuánto tiempo el modelo se mantiene cargado en memoria después de responder.
Si el usuario deja de usarlo, pasado ese tiempo se descarga para liberar recursos.

de aqui en fuera agregamos lo mismo que en la parte 2 solo que conforme a los perosnjaes que nos tocara dependiendo de nuestro sistema operativo
