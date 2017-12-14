
# Tira latas con teclado

## Propuesta

Realizar un programa que utilizando el teclado del ordenador, pueda manipular un objeto

La propuesta puede ser:

- Tecla C Cierra la garra
- Tecla A Abre la garra
- Tecla H coloca la garra en una posición Horizontal
- Tecla D balancea la garra hacia la derecha
- Tecla I balancea la garra hacia la izquierda
- Tecla flecha derecha gira el robot hacia la derecha
- Tecla flecha izquierda gira el robot hacia la izquierda
- Tecla fecha arriba mueve la garra arriba
- Tecla flecha abajo mueve la garra abajo
- Tecla 1 mueve el robot hacia delante
- Tecla 2 mueve el robot hacia detrás
- Tecla 0 para el robot

en fin.... es una propuesta, se puede hacer como se quiera

{% youtube %}https//www.youtube.com/watch?v=k01opsw0RXM{% endyoutube %}
<script type="text/javascript">var feedback4_93text = "Solución";</script><input type="button" name="toggle-feedback-4_93" value="Solución" class="feedbackbutton" onclick="$exe.toggleFeedback(this,false);return false" />

### Retroalimentación

Por ejemplo para  la siguiente configuración (puedes conectarlo como quieras, pero en esta solución conectamos los puertos y los slots a los servos siguientes:
|**Efecto**|**Tecla**|**Puerto**|**Slot**|**Ángulo**|**Servo**
|Cerrar la garra|C|3|2|90º|garra
|Abrir la garra|A|3|2|0º|garra
|Garra en horizontal|H|1|1|90º|El de dentro del U del brazo articulado
|Garra balanceo derecha|D|1|1|0º|El de dentro del U del brazo articulado
|Garra balanceo izquierda|I|1|1|180º|El de dentro del U del brazo articulado
|Garra arriba|Flecha arriba|1|2|45º|El de fuera del brazo articulado
|Garra abajo|Flecha abajo|1|2|90º|El de fuera del brazo articulado

![](img/tiralatasteclado.png)
Puedes descargarte el programa [aqui](PINZAS-CIERRA-ABRE-CONTECLADO.sb2) (sb2 - 75.12 <abbr lang="en" title="KiloBytes">KB</abbr>).

