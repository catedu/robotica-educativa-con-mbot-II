
# Potenciómetro

El potenciómetro indica en grados el giro que le damos en su mando:

![](img/EL_POTEN_makeblock_EL_POTEN.jpg)
Al ser negro, sólo se puede usar el puerto 3 o 4. La instrucción en mBlock es la siguiente:

![](img/instruccpoten.png)
## Un caso práctico

El potenciómetro permite interactuar con el movimiento de un personaje de mBlock, enriqueciendo un video-juego:

- El dinosaurio se mueve continuamente en el eje x y aleatoriamente en el eje y
- El murciélago tiene fijo el x pero el y está sujeto al valor del potenciómetro
- Si el murciélago toca el borde exterior o toca el dinosario se suma un punto en COMIDO

{% youtube %}https//www.youtube.com/watch?v=ZvD6cPm6L-0{% endyoutube %}
<script type="text/javascript">var feedback5_93text = "Mostrar retroalimentación";</script><input type="button" name="toggle-feedback-5_93" value="Mostrar retroalimentación" class="feedbackbutton" onclick="$exe.toggleFeedback(this,true);return false" />

### Retroalimentación

La solución es:

Programa del murciélago:

![](img/comedinopoten-bat.png)
Programa del dinosaurio

![](img/comedinopoten-dino.png)
[Descarga del programa](http://aularagon.catedu.es/materialesaularagon2013/mbot/fuentes/comer-bat-dino-potenciometro.sb2)

