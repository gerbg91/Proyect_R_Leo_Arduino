# Proyect_R_Leo_Arduino
Proyecto de mascota virtual que tendrá diversas fases de evolución:

- Primera fase de huevo, cuando pase el suficiente tiempo definido en la programación pasara a infancia.
- Segunda fase de infancia, cuando pase el suficiente tiempo definido en la programación pasara a adulta.
- Tercera ultima fase, será adulta.

Se mostrará por la pantalla Oled, la imagen que corresponde con su evolución.

También poseerá diferentes géneros:

- Masculino
- Femenino
- No binario

Este elección será de manera aleatoria en la programación y se mostrará por pantalla.

Tendrá diferentes acciones y estadísticas, en la cual mediante botones podremos ir aumentándolos:

- Alimentación
- Amor
- Limpieza
- Medicina

Para la acción del amor y simulando que se le puede acariciar, tendremos un sensor de ultrasonidos que al pasar nuestra mano por delante aumentará el amor.

Por cada acción tenemos un botón que hace subir las estadísticas hasta un máximo de 10 niveles a excepción de la medicina para que nuestra mascota este sana y feliz. Si dejamos pasar el tiempo y las estadísticas van bajando cuando la alimentación, el amor y la limpieza lleguen a 0 morirá.

Cada semana de manera aleatoria puede enfermar nuestra mascota, si enferma una vez, nos mostrará por pantalla que se encuentra mal, si a la siguiente semana vuelve a enfermar y no la hemos curado morirá.

Todas estas estadísticas se mostrarán por una pantalla LCD que mediante un JOSTICK podremos alternar las diferentes opciones, mostrando por un lado primero la fase de evolución, genero y estado de nuestra mascota. Si movemos el JOSTICK hacia abajo, se mostrarán las estadísticas de alimentación, amor y limpieza. Moviendo el JOSTICK a su posición inicial tendremos de vuelta la primera pantalla.

Cabe decir que nuestra mascota tendrá una vida finita, ya que cada cierto tiempo se guarda la información en la EEPROM y esta solo admite un numero finito de grabación y escritura antes de que falle. Esta guardado, vendrá definido en una constante en la programación así como el tiempo de consumo de las estadísticas.

Materiales utilizados:

- Arduino uno
- Pulsadores
- Pantalla Oled
- Pantalla LCD
- Modulo RTC
- Protoboard
- Modulo HC-SR04
