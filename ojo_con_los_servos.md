
![](/assets/MT_SERVO_9G_makeblock_MT_SERVO_9G.jpg)

## <br />Funcionamiento

Los servos se tienen que conectar a través del[ ADAPTADOR RJ45](https://www.makeblock.es/productos/adaptador_rj25/) por lo tanto se pueden conectar DOS SERVOS en Slot1 y en Slot2 en el adaptador 

![](/assets/servo.png)

La instrucción de gobierno es "fijar servo" donde hay que especificar el puerto donde está conectado el Adaptador, y dentro del adaptador, a que slot está conectado, y finalmente cual es el ángulo que queremos que se fije el rotor

![](img/fijarservo.png)

## Ojo con ellos

Hay que tener en cuenta:

- NO HAY QUE FORZARLOS los servos fijan el rotor en el ángulo determinado por la instrucción fijar servo, al forzarlo **se rompen los engranajes de plástico que son delicados** y es típico que los chavales, al no estar el servo en la posición deseada, con la mano lo fuerzen.
- PICOS DE TENSIÓN los cables están protegidos con un cilindro magnético para absorber los los picos causados por los contínuos arranques, paradas e inversiones de giro propios del servo, aún así se producen y LAS BATERÍAS ESPECIALMENTE LAS RECARGABLES SE QUEDAN SIN ENERGÍA muy rápidamente
- La fijación con la estructura de plástico es a través de unos tornillos muy pequeños, que requiere destreza. La estructura de plástico se rompe si se fuerza el priete de los tornillos.
- No tienen mucha fuerza, si nos excedemos se rompen los engranajes de plástico. Si deseamos servos con más fuerza es mejor usar l[os Motores Servo](https://www.makeblock.es/productos/servo/)

Una manera de no forzar el relé si no está en la situación deseada inicial, es desmontar y montar el soporte en la posición deseada, antes que forzar, un vídeo lo explica mejor:

{% youtube %}https//www.youtube.com/watch?v=XfSq_KTlBSU{% endyoutube %}
