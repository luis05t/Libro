<div style="text-align: justify;">

En bibliotecas genéricas. Esto solo será posible cuando las API proporcionen representaciones autodescriptivas.

* Cuando las API cambian, los clientes de API personalizados se rompen y deben repararse. Pero cuando un sitio web se somete a un rediseño, los usuarios del sitio se quejan del rediseño y luego se adaptan. Sus navegadores no dejan de funcionar.

  En términos de REST, el rediseño del sitio web está completamente encapsulado en los documentos HTML autodescriptivos que proporciona el sitio web. Un cliente que pudiera entender los documentos HTML antiguos puede entender los nuevos.

Estos son los problemas que intento resolver con este libro. La buena noticia es que solía ser mucho peor. Hace unos años, era común ver API RESTful que usaban métodos HTTP seguros de formas inseguras o mezclaban el estado de la aplicación y el de los recursos. Esto ya no sucede mucho. Los diseños han mejorado y pueden mejorar aún más.

## El Desafío Semántico

Ahora, las malas noticias. La historia que les he contado, la historia del viaje de Alice a través de un sitio web, fue tan fluida como lo fue gracias a un dispositivo de hardware muy lento y costoso: Alice misma. Cada vez que su navegador mostraba una página web, Alice, un ser humano, tenía que mirar la página mostrada y decidir qué hacer a continuación. La Web funciona porque los seres humanos toman todas las decisiones sobre qué enlaces hacer clic y qué formularios completar.

El objetivo de las API web es hacer las cosas sin que un humano esté sentado frente a un navegador web todo el día. ¿Cómo podemos programar una computadora para que tome las decisiones sobre qué enlaces hacer clic? Una computadora puede analizar el código HTML `<a href="/messages">Get started</a>`, pero no puede entender la frase "Get started". ¿Por qué molestarse en diseñar API que brinden mensajes autodescriptivos si esos mensajes no serán comprendidos por sus consumidores de software?

Este es el mayor desafío en el diseño de API web: cerrar la brecha semántica entre comprender la estructura de un documento y comprender lo que significa. En resumen, lo llamaré el desafío semántico. Se ha avanzado muy poco en el desafío semántico y nunca lo resolveremos por completo. La buena noticia es que, como se ha avanzado tan poco hasta ahora, el primer avance es realmente fácil. Solo tenemos que empezar a trabajar juntos, en lugar de duplicar el trabajo de los demás.

En los próximos capítulos abordaré el desafío semántico, a medida que hable sobre las tecnologías de la Web y cómo se pueden usar en los diseños de API. En el capítulo 8, tendremos las herramientas necesarias para abordar el desafío semántico de frente.

</div>