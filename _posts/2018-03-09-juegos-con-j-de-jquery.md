---
layout: post
title: Juegos con j de jQuery
description: Echa un vistazo a uno de mis últimos proyectos relacionados con jQuery
categories: code
author: juandels3
---


Días atrás, se nos puso en pie realizar un proyecto para la semana cultural de [IES Polígono Sur](https://iespoligonosur.org/). Se trataba, de nada más y nada menos, que **un juego** relacionado con la temática de los derechos a la información y a internet. Hoy quería compartir con todos vosotros cómo ha sido mi experiencia, lo que he aprendido y algunos consejos para llevar a cabo si tu también quieres crear tu propio juego.

## Pasito a pasito

Crear un juego no es algo que se haga de un día para otro. Como todo buen trabajo, requiere paciencia, estrategia y, en este caso, ayuda que tengas experiencia en haber jugado juegos de navegador u otros. Si puedes trabajar con dos buenos compañeros como ha sido mi caso (_¡o más!_) el proyecto avanzará más rápido, pero será necesaria la **c**ooperación, **c**omunicación y **c**oordinación de los miembros del grupo.

### Tema y mecánicas

En mi caso, la temática del juego era clara: el derecho a la información y a internet. La mecánica del juego trata los siguientes conceptos (entre otros)

-   Objetivo del juego
-   Comodines/pistas
-   Sistema de puntuación
-   Dificultad
-   Tiempo
-   Otros...

Puede haber un abismo de mecánicas para un juego, pero **no** siempre hay que reinventar la rueda para llegar a conseguir una **buena** y **atractiva** mecánica para el juego.

![small image]({{site.baseurl}}/images/j1.png)

Nuestro juego es uno de los clásicos "Escape Room", donde el jugador tratará de salir de una habitación, haciendo clic e interactuando con diversos objetos ocultos en la pantalla en un **tiempo limitado**, tratando de contestar correctamente a las preguntas relacionadas con la temática, para seguir avanzando.  
Esto sería la idea del juego con algunas mecánicas, como pueden ser la existencia del **tiempo**, **vidas**, una lupa que actúa como **comodín**, y un sistema sencillo de **preguntas** relacionadas con la informática.

![small image]({{site.baseurl}}/images/j2.png)

### Público objetivo

Uno de los factores más importantes a la hora de desarrollar un juego, es decidir para el público que va a ser lanzado o el **público objetivo**. En el caso de _Classroom Escape_, el público objetivo eran estudiantes cuya edad ronda los 17-22 años (aprox.). Esto es importante a la hora de ajustar el nivel de las **preguntas** y del **juego en** **general**.

### Aspectos técnicos

Una vez tengas la parte teórica, es importante tratar los aspectos técnicos del juego, como por ejemplo:

-   Plataforma del juego (app web, móvil, app de escritorio, consola...)
-   Lenguajes de programación (depende de la plataforma)
-   Diseño
-   Tecnologías (bases de datos, etc...)

En nuestro juego, tuvimos claro que iba a ser un juego para navegador, usando la librería jquery para Javascript y CSS3 como diseño general. Para el sistema de preguntas aleatorias y el ranking, hemos usado PHP y MySQL como base de datos relacional.

El juego ha sido desplegado desde AWS (Amazon Web Services), haciendo uso de una cuenta **gratuita**.

### Manos a la obra

Una vez esté tratado todo lo anterior, es hora de comenzar el reparto de tareas entre los miembros del grupo, y empezar a hincar los codos delante de la pantalla. Es importante la comunicación entre los compañeros, en nuestro caso, usamos **Github** como plataforma de desarrollo, ya que permite muchas facilidades y herramientas a la hora de desarrollar en grupo.

### Testeo

Cuando creas que todo está acabado, no será así. Todo juego tiene que pasar por una fase en la cual se realicen todo tipo de pruebas en el juego, forzándo la aparición de errores para que éstos sean reparados.

![small image]({{site.baseurl}}/images/j3.png)

Espero que os haya gustado esta entrada del blog. Personalmente, he aprendido mucho con este proyecto y con jquery en particular. Puedes probar nuestro juego [aqui](http://54.218.125.245/game/), aunque estará disponible de **forma** **temporal.** Puedes participar en [el proyecto de github](https://github.com/JuandeLS3/ClassRoom-Escape-Game).
