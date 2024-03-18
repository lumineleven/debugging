# debugging
Trabajo realizado para ciclo superior de desarrollo de aplicaciones multiplataforma.
En este código corregimos un error detectado a través del debugger de eclipse. 

El error que he detectado es justamente en la función Math.random(), al añadir paréntesis en la función se ejecuta correctamente el código. Actualmente se encuentra así:

num_aleat[i]=(int)Math.random()*100;

Para resolverlo añadimos el paréntesis correspondiente:

num_aleat[i] = (int) (Math.random() * 100);

Y se generan correctamente los números aleatorios.
