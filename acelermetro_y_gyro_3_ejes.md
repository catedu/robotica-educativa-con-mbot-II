
# Acelerómetro y Gyro 3 ejes

El [acelerómetro gyro 3 ejes ](https://www.makeblock.es/productos/sensor_acelerometro_gyro/)detecta en grados su inclinación en tres ejes:

![](img/EL_GYRO_makeblock_EL_GYRO.jpg)
Su función en mBlock es la siguiente: 

![](img/instrucciongyro.png)
En teoría como se puede ver en esta página de Makeblock.com puede comunicar los grados al mBloc pero no nos ha funcionado. Si alguien le funciona por favor que nos escriba.

**Sólo nos ha funcionado con el robot funcionando independientemente del ordenadorm modo autónomo**. ([Upload to Arduino](http://aularagon.catedu.es/materialesaularagon2013/mbot/M3/upload_to_arduino.html))

Solución al problema de deriva en el eje Z [aquí](https://www.youtube.com/watch?v=EpmbZtbfs9Y)

## Ejemplo de uso

Suponte que quieres hacer un mando con el giroscopio.

Es decir, si lo inclinamos sobre el eje y va hacia delante o hacia atrás

Y si lo inclinamos sobre el eje x que gire a un lado o a otro

Un vídeo lo explica mejor:

{% youtube %}https//www.youtube.com/watch?v=lczO3UDKwaQ{% endyoutube %}
<script type="text/javascript">var feedback1_93text = "Mostrar retroalimentación";</script><input type="button" name="toggle-feedback-1_93" value="Mostrar retroalimentación" class="feedbackbutton" onclick="$exe.toggleFeedback(this,true);return false" />

### Retroalimentación

La solución es :

![](img/programamandogyro.png)
el 10* es porque los grados son demasiado pequeños para hacer una velocidad rápida.

