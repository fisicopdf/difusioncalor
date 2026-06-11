PREINFORME – PROYECTO FINAL
MÉTODOS COMPUTACIONALES

Nombre del proyecto:
Simulación numérica de la difusión de calor mediante la ley de Fourier en una barra unidimensional y en medios tridimensionales

Integrantes:
Juan David Hincapié Ruiz
David Santiago Barrera Mendoza

Objetivo general

Desarrollar modelos computacionales basados en la ley de difusión de calor de Fourier para simular la evolución espacial y temporal de la temperatura tanto en una barra unidimensional como en un sistema tridimensional, utilizando los métodos numéricos de Euler, Runge-Kutta de segundo orden (RK2) y Runge-Kutta de cuarto orden (RK4) para resolver las ecuaciones diferenciales asociadas y analizar la precisión y eficiencia de cada método.
Para referencia de las ecuaciones: https://es.wikipedia.org/wiki/Ecuaci%C3%B3n_del_calor 

Descripción del proyecto (alcances y metodología)

El proyecto consiste en modelar la transferencia de calor por conducción aplicando la ley de Fourier, la cual establece que el flujo de calor es proporcional al gradiente de temperatura presente en un material. A partir de esta ley y del principio de conservación de la energía se obtiene la ecuación de difusión de calor, que describe la evolución temporal y espacial de la temperatura dentro de un medio.

Inicialmente se estudiará el caso de una barra unidimensional, donde la temperatura depende de la posición a lo largo de la barra y del tiempo. Posteriormente, el análisis se extenderá a sistemas tridimensionales con el fin de representar la propagación del calor en volúmenes más complejos y visualizar la distribución térmica en las tres dimensiones espaciales.

Para resolver la ecuación de difusión de calor se utilizará el método de diferencias finitas para discretizar las derivadas espaciales. Esta discretización transforma la ecuación diferencial parcial en un sistema de ecuaciones diferenciales ordinarias dependientes del tiempo. Dicho sistema será resuelto mediante los métodos de Euler, Runge-Kutta de segundo orden (RK2) y Runge-Kutta de cuarto orden (RK4), permitiendo comparar la precisión, estabilidad y costo computacional de cada técnica numérica.

Los resultados se presentarán mediante gráficas de temperatura en función de la posición y del tiempo para el caso unidimensional, así como mapas de calor, superficies tridimensionales y animaciones para el caso tridimensional. Finalmente, se realizará una comparación entre los métodos numéricos empleados, evaluando sus errores y su capacidad para reproducir el comportamiento físico esperado de la difusión de calor según la ley de Fourier.
