Principios de diseño
========================================================================


Bajo acoplamiento
------------------------------------------------------------------------

.. index:: acoplamiento

Otro principio básico de diseño es favorecer siempre un bajo
acoplamiento_ entre objetos que interactuan.

Se dice que dos objetos/módulos tiene un acoplamiento **bajo** o
**débil** cuando pueden interactuar, pero el conocimiento que tienen
cada uno del otro es pequeño.

.. index:: cohesión

El acoplamiento se relaciona de forma inversa con la cohesión_. Un
bajo acoplamiento normalmente se correlaciona con una alta cohesión, y
viceversa. Un bajo acoplamiento permite:

- Mejorar la facilidad de mantenimiento.

- Aumentar las posibilidades de reuso.

- Evitar el efecto onda, en el cual un cambio un una parte de software
  afecta a otras.


.. _acoplamiento: https://es.wikipedia.org/wiki/Acoplamiento_(inform%C3%A1tica)
.. _cohesión: https://es.wikipedia.org/wiki/Cohesi%C3%B3n_(inform%C3%A1tica)

