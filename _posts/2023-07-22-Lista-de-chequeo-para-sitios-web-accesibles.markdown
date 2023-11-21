---
layout: post
title: "Lista de chequeo para sitios web accesibles"
date: 2023-07-22 11:27:00 -0500
categories:
---
# **Introducción**

Tener una noción de la importancia de la accesibilidad en la web es vital para cualquier esfuerzo direccionado en que las tecnologías digitales protejan y avancen los derechos humanos fundamentales y promuevan la justicia social.

Este documento recopila una serie de conocimientos y experiencias que el equipo de Fundación Karisma está adquiriendo y mejorando con el paso de los años, el objetivo de esta entrega es recopilar todos estos saberes y brindar una lista básica y actualizada de los principales aspectos para lograr tener sitios web accesibles. Está dirigido a las organizaciones o personas que trabajan activamente para que sus comunicaciones digitales, sean realmente accesibles para la mayor cantidad de personas.

Fundación Karisma en el año 2021 publicó la [Guía básica de accesibilidad web y de contenidos en redes sociales](https://web.karisma.org.co/mas-autonomia-digital-menos-barreras-guia-bpasica-de-accesibilidad-web-y-redes-sociales/), cuyo enfoque fue el de facilitar pautas e información técnica y experiencial sobre el diseño e implementación de estrategias y buenas prácticas para el desarrollo de contenidos comunicativos más accesibles e incluyentes para todas las personas, abordando los estándares internacionales de la W3C [(World Wide Web Consortium)](https://www.w3.org) quienes crearon las directrices de accesibilidad para el contenido web [WCAG](https://www.w3.org/TR/2018/REC-WCAG21-20180605/) en su versión 2.1 al cierre de este documento. 

> Para la publicación de este documento se encuentran disponibles las [WCAG 2](https://www.w3.org/TR/2018/REC-WCAG21-20180605/.) y se está trabajando en su versión [WCAG 3](https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/) la cual se encuentra como borrador. 

Para esta entrega, consideramos los [criterios de WCAG de nivel A](https://docs.google.com/document/d/1CxD5d8JZhL2Pef4lJObLucI1SYwZ9MKFCEfkHSGMk88/edit#heading=h.byz582jvu6ut)
como referencia en la creación de sitios web que eliminen barreras de accesibilidad. Específicamente, nos enfocamos en las acciones comunicativas y cómo el diseño y la interacción de las personas usuarias con las páginas web afectan su experiencia. Abordamos acciones para superar limitaciones, como:

- La ceguera y la baja visión.
- La sordera y la pérdida auditiva.
- El movimineto limitado, las discapacidades del habla, la fotosensibilidada combinacion de estas.
- Algunas adaptaciones para discapacidades de aprendizaje y limitaciones cognitivas.

## **1. Lista de chequeo**

### **1.1 Validación de contenidos**

Al momento de diseñar cualquier contenido gráfico una buena práctica para la accesibilidad es evaluar el diseño antes de subirlo a la web. 

Para esta evaluación debemos pensar en las personas usuarias con visión parcial, por ejemplo, la visión de color limitada, como es el caso del daltonismo, tener esta condicion en mente permite que las personas puedan acceder a los contenidos con el amparo de la Accesibilidad universal por esto es fundamental que la información transmitida por el color esté disponible de otras maneras visuales o no sea indispensable para comprender la información o navegabilidad del sitio web.

Aquí una serie de herramientas para evaluar este criterio:

- [Vischeck](https://www.vischeck.com/)
- [Laboratorio de color AWARE](http://colorlab.wickline.org/colorblind/colorlab/)
- [Microsoft: Comprobar que una página es utilizable por personas con daltonismo](https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/accessibility/test-color-blindness)
- [Cómo hacer figuras y presentaciones que sean amigables para las personas daltónicas](https://jfly.uni-koeln.de/color/)
- [La aplicación Color Tutor](https://colortutorial.design/tutor.html)

### **1.2 Validación la estructura HTML5**

La accesibilidad web comienza con una buena estructura HTML5, para ello debemos revisar que nuestro HTML5 este correctamente escrito, esto implica usar las etiquetas únicamente para el fin con el que fueron diseñadas haciendo una semántica correcta que pueda ser interpretada tanto por lectores de pantalla como por diversos actores en la web con los que las personas usuarias interactúan con los sitios.

La W3C tiene una magnífica herramienta para hacer un test de este criterio: [validator](https://validator.w3.org/)

![Captura de pantalla de un ítem del diagnóstico con el uso de la herramienta](/DocKom/assets/gitbook/images/Captura-de-pantalla-de-una-de-las-recomendaciones-a-nivel-HTML-de-la-herramienta.webp)
> Captura de pantalla de un ítem del diagnóstico con el uso de la herramienta.

Esta estructura nos ayuda a que el sitio web cuente con una buena navegabilidad, algo muy importante para dos criterios de accesibilidad universal. Uno es que el sitio web pueda ser comprendido y el otro es que sea operable, tanto con el mouse como con el teclado en este caso se benefician las personas que interactúan con los sitios web usando el teclado para navegar por el sitio.

### **1.3 Menú de navegación**

![Captura de pantalla de la interacción con teclado en una barra de navegación.](/DocKom/assets/gitbook/images/Captura_pantalla_menú_navegación_página_web_karisma.webp)
> Captura de pantalla de la interacción con teclado en una barra de navegación.

Tomando como referencia la W3C el uso de las barras de navegación o menús, se da principalmente para facilitar la navegación de los sitios web, este es un componente crítico para la operatividad del sitio.

### **1.4 Efecto Hover**

Este efecto permite aplicar un cambio de estilo a un elemento cuando el cursor se sitúa sobre él. Esto es crucial para la interacción y usabilidad de un sitio, resaltar los elementos interactivos es algo especialmente útil para las personas usuarias con discapacidad visual.

El siguiente ejemplo de nuestro sitio web, podemos ver el cambio de color del fondo del menú: ‘INICIO’’ 

Así luce el botón únete a nuestro Boletín sin el efecto hover:

![Así luce el botón únete a nuestro Boletín sin el efecto hover](/DocKom/assets/gitbook/images/Así-luce-el-botón-únete-a-nuestro-Boletín-sin-el-efecto-hover.webp)
> Así luce el botón únete a nuestro Boletín sin el efecto hover.

Así luce el botón únete a nuestro Boletín con el efecto hover:
![Así luce el botón únete a nuestro Boletín con el efecto hover](/DocKom/assets/gitbook/images/Así-luce-el-botón-únete-a-nuestro-Boletín-con-el-efecto-hover.webp)
> Así luce el botón únete a nuestro Boletín con el efecto hover.

### **1.5 Carruseles en el home y entradas**

Los carruseles permiten a los sitios web mostrar una colección de elementos en una secuencia de uno después de otro. Para garantizar que estos elementos en la web sean accesibles debemos pensar en que estos cuenten con una estructura robusta y que le brinde control al usuario. La W3C recomienda tener en cuenta los siguientes 4 criterios.

**Estructura:** Que se desarrolle con la semántica que la documentación oficial prevé según sea el caso del desarrollo web para que los asistentes tecnológicos como lectores de pantalla puedan funcionar correctamente.

**Funcionalidad:** Que cumpla con su objetivo sin fallos por contenido o programación garantizando la navegabilidad lo que implica que el cambio de elementos se pueda detener, reanudar, adelantar y retroceder.

**Animaciones:** Agregar animación entre el movimiento del contenido considerando que estas animaciones no representen un cambio menor a 3 elementos por segundo, pensando en las personas que tengan una condición de fotosensibilidad.

**Estilo:** Asegurarse de que el diseño sea legible y utilizable para todos y todas. para más información puedes consultar: [Más autonomía digital y menos barreras: Guía básica de accesibilidad web y de contenidos en redes sociales.](https://web.karisma.org.co/mas-autonomia-digital-menos-barreras-guia-bpasica-de-accesibilidad-web-y-redes-sociales/)

![Captura de pantalla de un carrusel que cumple con estos criterios.](/DocKom/assets/gitbook/images/Captura-de-pantalla-de-un-carrusel-que-cumple-con-estos-criterios,-Aquí-se-puede-ver.webp)
> [Aquí se puede ver el ejemplo con su funcionalidad.](https://www.w3.org/WAI/tutorials/carousels/working-example/)

Algunos de los criterios de accesibilidad que podemos revisar son:

- Pausar los carruseles es crucial, ya que las personas usuarias tienen distintos ritmos de lectura y un flujo muy rápido puede convertirse en un factor de distracción además de dificultar la lectura.

- Las funciones del carrousel pueden variar según el uso del carrusel y su contenido, debemos garantizar que tanto los links internos en el caso que los tenga como la navegación es decir que se pueda controlar el cambio y pausa de los contenidos con el teclado y desde la pantalla con los criterios para los botones y links de navegación.

- Los cambios de elementos en el carrusel tiene que comunicarse para todas las personas usuarias, es decir que cuando cambia un elemento de un carrousel esto debe poder ser percibido por personas usuarias con  limitaciones visuales que acceden a los contenido únicamente con lector de pantallas.

### **1.6 Los enlaces en los títulos y en el cuerpo de los textos**

Los enlaces siempre deben ir subrayados puesto que permite a personas que perciben el color de una manera diferente puedan identificar el enlace sin necesidad de referenciarse únicamente del color del texto. El texto descriptivo de los enlaces debe siempre indicar lo que se espera que suceda después de interactuar con él.

![Ejemplo de los enlaces dentro del carrusel de la página principal de Fundación Karisma](/DocKom/assets/gitbook/images/Ejemplo-de-los-enlaces-dentro-del-carrusel-de-la-página-principal-de-Fundación-Karisma.webp)
> Ejemplo de los enlaces dentro del carrusel de la página principal de Fundación Karisma

![Ejemplo de los enlaces dentro de la sección ‘Aprende algo nuevo’ de la página principal de Fundación Karisma](/DocKom/assets/gitbook/images/Ejemplo-de-los-enlaces-dentro-de-la-sección-‘Aprende-algo-nuevo’-de-la-página-principal-de.webp)
> Ejemplo de los enlaces dentro de la sección ‘Aprende algo nuevo’ de la página principal de Fundación Karisma.

Al igual que para los enlaces de redes sociales, para los enlaces que van dentro  de las entradas web o documentos. se deben responder las siguientes preguntas:

- ¿A dónde se dirige el enlace?
- ¿Qué acción se espera que se haga?

Se aconseja no utilizar palabras como por ejemplo ‘Clic aquí’ o ‘Ver más’, tampoco direcciones como URL abreviadas sin un nombre que las identifique. 

**Ejemplo de una entrada web de K con enlaces:**

![Captura de pantalla de los enlaces en una entrada web.](/DocKom/assets/gitbook/images/Captura-de-pantalla-los-enlaces-en-una-entrada-web.webp)
> Captura de pantalla de los enlaces en una entrada web.

**Ejemplo de un PDF con enlaces:**

![Captura de pantalla los enlaces en el cuerpo de un documento PDF](/DocKom/assets/gitbook/images/Captura-de-pantalla-los-enlaces-en-el-cuerpo-de-un-documento-PDF.webp)
> Captura de pantalla los enlaces en el cuerpo de un documento PDF

### **1.6 Texto alternativo en WordPress**

Al subir una imagen desde WordPress en el tablero de configuración el que está ubicado al lado derecho de la página para los casos de visualización de escritorio, en el apartado de bloque al seleccionar la imagen nos va a desplegar varias opciones, en este caso nos fijamos en la que dice texto alternativo. 
El texto alternativo describe el propósito que tiene la imagen, en el caso en que sea plenamente decorativa este campo se deja vacío.

![Captura de pantalla con un ejemplo de texto alternativo en una imagen de WordPress](/DocKom/assets/gitbook/images/Captura-de-pantalla-con-un-ejemplo-de-texto-alternativo-en-una-imagen-de-WordPress.webp)
> Captura de pantalla con un ejemplo de texto alternativo en una imagen de WordPress.

## **2 Criterios WCAG.**

En el marco de las acciones que podemos desarrollar para garantizar que los sitios web sean accesibles y cumplan con los criterios de las normas en su versión WCAG 2. Debemos tener en cuenta que estas normas se dividen en tres niveles de conformidad (A, AA, AAA) estos son criterios de éxito y se organizan en función del impacto que tiene en el diseño o la presentación visual de las páginas, estos criterios son verificables y se agrupan en cuatro principios: Perceptible, Operable, Comprensible y Robusto:

Para los fines de este documento solo se relacionarán descripciones y comentarios de buenas prácticas en las normas en el nivel de conformidad A. Para una consulta detallada se sugiere remitirse a la documentación oficial en: [How to Meet WCAG (Quickref Reference) (w3.org)](https://www.w3.org/WAI/WCAG21/quickref/#top)

### **2.1 Perceptible**

Este principio nos sugiere que tanto nuestros contenidos web como la interfaz con la que interactúan todos las personas usuarias, independientemente de las barreras o limitaciones que puedan tener, deben ser perceptibles por los sentidos o comprensibles mediante el raciocinio. A continuación, se presentan algunos criterios a considerar en este nivel.

#### **2.1.1 Alternativas Textuales**

Primero debes identificar todo el contenido que no sea textual y que transmite información a las personas usuarias y asegúrate de que ese mismo contenido cuente con una alternativa de texto, esto con la finalidad de que pueda cambiarse a otras formas como letra grande, braille, voz, símbolos o un lenguaje más simple. 

#### **2.1.2 Medios Basados en el tiempo (audio y vídeo)**

Este criterio nos habla del contenido de audio o video el cual debe ser adaptable y distinguible. Una medida de accesibilidad universal es brindarle a las personas usuarias siempre una alternativa de texto equivalente para que la información de los medios pueda comprenderse.

A continuación una lista de los lineamientos a considerar los cuales pueden ser consultados en detalle:

- [Solo audio y solo video (pre grabado)](https://www.w3.org/WAI/WCAG21/quickref/#audio-only-and-video-only-prerecorded)
- [Subtítulos (pre grabados)](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)
- [Descripción de audio o alternativa de medios (pre grabada)](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-or-media-alternative-prerecorded)

#### **2.1.3 Adaptable**

Para que un sitio web y su contenido sea adaptable debemos pensar en la manera en la que todas las personas usuarias interactúan con el sitio incluyendo las que cuenten con limitaciones visuales, auditivas, o motoras. Considerar y aplicar las pautas de la WCAG permite que los sitios web cuenten con estas características de adaptabilidad.

A continuación una lista de los lineamientos a considerar los cuales pueden ser consultados en detalle:

- [Información y relaciones](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#info-and-relationships)
- [Secuencia significativa](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#meaningful-sequence)
- [Características sensoriales](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#sensory-characteristics)

#### **2.1.4 Distinguible**
Facilita a los usuarios ver y escuchar contenido, incluida la separación del primer plano del fondo.

A continuación una lista de los lineamientos a considerar los cuales pueden ser consultados en detalle:

- [Uso del color](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#use-of-color)
- [Audio Control](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#audio-control)

### **2.2 Operable**

Este principio hace referencia a la capacidad que tienen los sitios web modernos para que los usuarios interactúen con ellos mediante diversos componentes de la interfaz de usuario y la navegación. 

- Teclado accesible
- Tiempo suficiente
- Convulsiones y reacciones físicas
- Navegable

### **2.3 Comprensible**

Este componente se enfoca en hacer que la información y las operaciones en un sitio web sean claras y comprensibles para todos los usuarios. Esto implica presentar la información de forma clara y sencilla, organizarla de manera lógica, proporcionar instrucciones concisas y ofrecer ayuda adicional para aquellos que lo necesiten. El objetivo es garantizar que todos los usuarios puedan entender fácilmente la información y usar la interfaz del sitio web, sin importar su nivel de habilidad o conocimiento.

### **2.4 Robusto**

El contenido debe ser lo suficientemente robusto en términos de compatibilidad para que pueda ser consultado por usuarios que acceden desde diversos dispositivos, y ser interpretado por una amplia gama de agentes de usuario, incluyendo tecnologías de asistencia.

## **3 Glosario**

### **3.1 Accesibilidad universal**

La condición que deben cumplir los entornos, procesos, bienes, productos y servicios, así como los objetos o instrumentos, herramientas y dispositivos, para ser comprensibles, utilizables y practicables por todas las personas en condiciones de seguridad y comodidad, de la forma más autónoma y natural posible.

#### **3.2 Ajuste razonables**

Son las acciones que los equipos de comunicación deciden tomar para que sus contenidos sean más accesibles de modo que no afecte el trabajo de manera sustancial.

#### **3.3 modelo social de discapacidad**

Este modelo reconoce a la discapacidad como una construcción social, que no se da por las condiciones específicas de cada persona sino por la interacción de las personas con la sociedad misma. 

- #####	**3.3.1 Barreras de accesibilidad**

Este tipo de barreras nos plantea que si un contenido web no es accesible no es porque las personas usuarias tienen algún tipo de limitación para acceder a él, este nuevo paradigma implica que el contenido no es accesible, puesto que no se realizaron los ajustes razonables para que bajo un contexto de accesibilidad universal las personas puedan acceder al contenido sin ninguna barrera o limitación.

- #####	**3.3.2 Barreras situacionales**

Este tipo de barreras hace referencia a situaciones específicas en donde por razones ajenas al contenido mismo existen limitaciones en el ambiente o el lugar en donde se está, por ejemplo si debemos consultar un video, pero el ruido en el ambiente es tan fuerte que no se puede escuchar lo correcto sería que el video cuente con subtítulos.

- #####	**3.3.3 Barreras de aprendizaje**

Este tipo de barreras se refiere a que las acciones que se deben tomar en materia de accesibilidad deben pensar también en las personas usuarias que puedan llegar a tener limitaciones cognitivas o que cuenten que sean  neuro divergentes 

## **4 Comentarios finales**

La implementación de buenas prácticas para que todas las personas puedan acceder a los contenidos e información de manera igualitaria, nos permite reconocernos en un mundo increíblemente diverso, en donde un gran porcentaje de las personas en el planeta tienen algún tipo de discapacidad, por esta razón los esfuerzos en accesibilidad tienen un impacto en el goce de derechos humanos y libertades fundamentales.

El conocer y aplicar criterios como por ejemplo, el análisis y posterior implementación de las acciones mínimas razonables o la correcta implementación de legislaciones internacionales y nacionales: 

[El Tratado de Marrakech.](https://www.wipo.int/marrakesh_treaty/es/)

Según cada país la legislación que define las disposiciones para garantizar el pleno ejercicio de los derechos de las personas con discapacidad, que para el caso de Colombia es la [Ley estatutaria 1618 de 2013.](https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=52081)
 
[Cómo las personas con discapacidad usan la Web, Iniciativa de Accesibilidad Web (WAI), W3C](https://www.w3.org/WAI/people-use-web/)

La W3C (World Wide Web Consortium) ha creado las Directrices de Accesibilidad para el Contenido Web (WCAG) que establecen los criterios para que una página web sea accesible. Estas directrices se dividen en tres niveles de conformidad: A, AA y AAA.

[lista de verificación para sitios web basada en las Directrices de Accesibilidad del Contenido Web (WCAG) 2.1 nivel AA1](https://www.w3.org/WAI/gettingstarted/Overview.html.es)






---
layout: post
title: "Lista de chequeo para sitios web accesibles"
date: 2023-07-22 11:27:00 -0500
categories:
---
# **Introducción**

Tener una noción de la importancia de la accesibilidad en la web es vital para cualquier esfuerzo direccionado en que las tecnologías digitales protejan y avancen los derechos humanos fundamentales y promuevan la justicia social.

Este documento recopila una serie de conocimientos y experiencias que el equipo de Fundación Karisma está adquiriendo y mejorando con el paso de los años, el objetivo de esta entrega es recopilar todos estos saberes y brindar una lista básica y actualizada de los principales aspectos para lograr tener sitios web accesibles. Está dirigido a las organizaciones o personas que trabajan activamente para que sus comunicaciones digitales, sean realmente accesibles para la mayor cantidad de personas.

Fundación Karisma en el año 2021 publicó la [Guía básica de accesibilidad web y de contenidos en redes sociales](https://web.karisma.org.co/mas-autonomia-digital-menos-barreras-guia-bpasica-de-accesibilidad-web-y-redes-sociales/), cuyo enfoque fue el de facilitar pautas e información técnica y experiencial sobre el diseño e implementación de estrategias y buenas prácticas para el desarrollo de contenidos comunicativos más accesibles e incluyentes para todas las personas, abordando los estándares internacionales de la W3C [(World Wide Web Consortium)](https://www.w3.org) quienes crearon las directrices de accesibilidad para el contenido web [WCAG](https://www.w3.org/TR/2018/REC-WCAG21-20180605/) en su versión 2.1 al cierre de este documento. 

> Para la publicación de este documento se encuentran disponibles las [WCAG 2](https://www.w3.org/TR/2018/REC-WCAG21-20180605/.) y se está trabajando en su versión [WCAG 3](https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/) la cual se encuentra como borrador. 

Para esta entrega, consideramos los [criterios de WCAG de nivel A](https://docs.google.com/document/d/1CxD5d8JZhL2Pef4lJObLucI1SYwZ9MKFCEfkHSGMk88/edit#heading=h.byz582jvu6ut)
como referencia en la creación de sitios web que eliminen barreras de accesibilidad. Específicamente, nos enfocamos en las acciones comunicativas y cómo el diseño y la interacción de las personas usuarias con las páginas web afectan su experiencia. Abordamos acciones para superar limitaciones, como:

- La ceguera y la baja visión.
- La sordera y la pérdida auditiva.
- El movimineto limitado, las discapacidades del habla, la fotosensibilidada combinacion de estas.
- Algunas adaptaciones para discapacidades de aprendizaje y limitaciones cognitivas.

## **1. Lista de chequeo**

### **1.1 Validación de contenidos**

Al momento de diseñar cualquier contenido gráfico una buena práctica para la accesibilidad es evaluar el diseño antes de subirlo a la web. 

Para esta evaluación debemos pensar en las personas usuarias con visión parcial, por ejemplo, la visión de color limitada, como es el caso del daltonismo, tener esta condicion en mente permite que las personas puedan acceder a los contenidos con el amparo de la Accesibilidad universal por esto es fundamental que la información transmitida por el color esté disponible de otras maneras visuales o no sea indispensable para comprender la información o navegabilidad del sitio web.

Aquí una serie de herramientas para evaluar este criterio:

- [Vischeck](https://www.vischeck.com/)
- [Laboratorio de color AWARE](http://colorlab.wickline.org/colorblind/colorlab/)
- [Microsoft: Comprobar que una página es utilizable por personas con daltonismo](https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/accessibility/test-color-blindness)
- [Cómo hacer figuras y presentaciones que sean amigables para las personas daltónicas](https://jfly.uni-koeln.de/color/)
- [La aplicación Color Tutor](https://colortutorial.design/tutor.html)

### **1.2 Validación la estructura HTML5**

La accesibilidad web comienza con una buena estructura HTML5, para ello debemos revisar que nuestro HTML5 este correctamente escrito, esto implica usar las etiquetas únicamente para el fin con el que fueron diseñadas haciendo una semántica correcta que pueda ser interpretada tanto por lectores de pantalla como por diversos actores en la web con los que las personas usuarias interactúan con los sitios.

La W3C tiene una magnífica herramienta para hacer un test de este criterio: [validator](https://validator.w3.org/)

![Captura de pantalla de un ítem del diagnóstico con el uso de la herramienta](/DocKom/assets/gitbook/images/Captura-de-pantalla-de-una-de-las-recomendaciones-a-nivel-HTML-de-la-herramienta.webp)
> Captura de pantalla de un ítem del diagnóstico con el uso de la herramienta.

Esta estructura nos ayuda a que el sitio web cuente con una buena navegabilidad, algo muy importante para dos criterios de accesibilidad universal. Uno es que el sitio web pueda ser comprendido y el otro es que sea operable, tanto con el mouse como con el teclado en este caso se benefician las personas que interactúan con los sitios web usando el teclado para navegar por el sitio.

### **1.3 Menú de navegación**

![Captura de pantalla de la interacción con teclado en una barra de navegación.](/DocKom/assets/gitbook/images/Captura_pantalla_menú_navegación_página_web_karisma.webp)
> Captura de pantalla de la interacción con teclado en una barra de navegación.

Tomando como referencia la W3C el uso de las barras de navegación o menús, se da principalmente para facilitar la navegación de los sitios web, este es un componente crítico para la operatividad del sitio.

### **1.4 Efecto Hover**

Este efecto permite aplicar un cambio de estilo a un elemento cuando el cursor se sitúa sobre él. Esto es crucial para la interacción y usabilidad de un sitio, resaltar los elementos interactivos es algo especialmente útil para las personas usuarias con discapacidad visual.

El siguiente ejemplo de nuestro sitio web, podemos ver el cambio de color del fondo del menú: ‘INICIO’’ 

Así luce el botón únete a nuestro Boletín sin el efecto hover:

![Así luce el botón únete a nuestro Boletín sin el efecto hover](/DocKom/assets/gitbook/images/Así-luce-el-botón-únete-a-nuestro-Boletín-sin-el-efecto-hover.webp)
> Así luce el botón únete a nuestro Boletín sin el efecto hover.

Así luce el botón únete a nuestro Boletín con el efecto hover:
![Así luce el botón únete a nuestro Boletín con el efecto hover](/DocKom/assets/gitbook/images/Así-luce-el-botón-únete-a-nuestro-Boletín-con-el-efecto-hover.webp)
> Así luce el botón únete a nuestro Boletín con el efecto hover.

### **1.5 Carruseles en el home y entradas**

Los carruseles permiten a los sitios web mostrar una colección de elementos en una secuencia de uno después de otro. Para garantizar que estos elementos en la web sean accesibles debemos pensar en que estos cuenten con una estructura robusta y que le brinde control al usuario. La W3C recomienda tener en cuenta los siguientes 4 criterios.

**Estructura:** Que se desarrolle con la semántica que la documentación oficial prevé según sea el caso del desarrollo web para que los asistentes tecnológicos como lectores de pantalla puedan funcionar correctamente.

**Funcionalidad:** Que cumpla con su objetivo sin fallos por contenido o programación garantizando la navegabilidad lo que implica que el cambio de elementos se pueda detener, reanudar, adelantar y retroceder.

**Animaciones:** Agregar animación entre el movimiento del contenido considerando que estas animaciones no representen un cambio menor a 3 elementos por segundo, pensando en las personas que tengan una condición de fotosensibilidad.

**Estilo:** Asegurarse de que el diseño sea legible y utilizable para todos y todas. para más información puedes consultar: [Más autonomía digital y menos barreras: Guía básica de accesibilidad web y de contenidos en redes sociales.](https://web.karisma.org.co/mas-autonomia-digital-menos-barreras-guia-bpasica-de-accesibilidad-web-y-redes-sociales/)

![Captura de pantalla de un carrusel que cumple con estos criterios.](/DocKom/assets/gitbook/images/Captura-de-pantalla-de-un-carrusel-que-cumple-con-estos-criterios,-Aquí-se-puede-ver.webp)
> [Aquí se puede ver el ejemplo con su funcionalidad.](https://www.w3.org/WAI/tutorials/carousels/working-example/)

Algunos de los criterios de accesibilidad que podemos revisar son:

- Pausar los carruseles es crucial, ya que las personas usuarias tienen distintos ritmos de lectura y un flujo muy rápido puede convertirse en un factor de distracción además de dificultar la lectura.

- Las funciones del carrousel pueden variar según el uso del carrusel y su contenido, debemos garantizar que tanto los links internos en el caso que los tenga como la navegación es decir que se pueda controlar el cambio y pausa de los contenidos con el teclado y desde la pantalla con los criterios para los botones y links de navegación.

- Los cambios de elementos en el carrusel tiene que comunicarse para todas las personas usuarias, es decir que cuando cambia un elemento de un carrousel esto debe poder ser percibido por personas usuarias con  limitaciones visuales que acceden a los contenido únicamente con lector de pantallas.

### **1.6 Los enlaces en los títulos y en el cuerpo de los textos**

Los enlaces siempre deben ir subrayados puesto que permite a personas que perciben el color de una manera diferente puedan identificar el enlace sin necesidad de referenciarse únicamente del color del texto. El texto descriptivo de los enlaces debe siempre indicar lo que se espera que suceda después de interactuar con él.

![Ejemplo de los enlaces dentro del carrusel de la página principal de Fundación Karisma](/DocKom/assets/gitbook/images/Ejemplo-de-los-enlaces-dentro-del-carrusel-de-la-página-principal-de-Fundación-Karisma.webp)
> Ejemplo de los enlaces dentro del carrusel de la página principal de Fundación Karisma

![Ejemplo de los enlaces dentro de la sección ‘Aprende algo nuevo’ de la página principal de Fundación Karisma](/DocKom/assets/gitbook/images/Ejemplo-de-los-enlaces-dentro-de-la-sección-‘Aprende-algo-nuevo’-de-la-página-principal-de.webp)
> Ejemplo de los enlaces dentro de la sección ‘Aprende algo nuevo’ de la página principal de Fundación Karisma.

Al igual que para los enlaces de redes sociales, para los enlaces que van dentro  de las entradas web o documentos. se deben responder las siguientes preguntas:

- ¿A dónde se dirige el enlace?
- ¿Qué acción se espera que se haga?

Se aconseja no utilizar palabras como por ejemplo ‘Clic aquí’ o ‘Ver más’, tampoco direcciones como URL abreviadas sin un nombre que las identifique. 

**Ejemplo de una entrada web de K con enlaces:**

![Captura de pantalla de los enlaces en una entrada web.](/DocKom/assets/gitbook/images/Captura-de-pantalla-los-enlaces-en-una-entrada-web.webp)
> Captura de pantalla de los enlaces en una entrada web.

**Ejemplo de un PDF con enlaces:**

![Captura de pantalla los enlaces en el cuerpo de un documento PDF](/DocKom/assets/gitbook/images/Captura-de-pantalla-los-enlaces-en-el-cuerpo-de-un-documento-PDF.webp)
> Captura de pantalla los enlaces en el cuerpo de un documento PDF

### **1.6 Texto alternativo en WordPress**

Al subir una imagen desde WordPress en el tablero de configuración el que está ubicado al lado derecho de la página para los casos de visualización de escritorio, en el apartado de bloque al seleccionar la imagen nos va a desplegar varias opciones, en este caso nos fijamos en la que dice texto alternativo. 
El texto alternativo describe el propósito que tiene la imagen, en el caso en que sea plenamente decorativa este campo se deja vacío.

![Captura de pantalla con un ejemplo de texto alternativo en una imagen de WordPress](/DocKom/assets/gitbook/images/Captura-de-pantalla-con-un-ejemplo-de-texto-alternativo-en-una-imagen-de-WordPress.webp)
> Captura de pantalla con un ejemplo de texto alternativo en una imagen de WordPress.

## **2 Criterios WCAG.**

En el marco de las acciones que podemos desarrollar para garantizar que los sitios web sean accesibles y cumplan con los criterios de las normas en su versión WCAG 2. Debemos tener en cuenta que estas normas se dividen en tres niveles de conformidad (A, AA, AAA) estos son criterios de éxito y se organizan en función del impacto que tiene en el diseño o la presentación visual de las páginas, estos criterios son verificables y se agrupan en cuatro principios: Perceptible, Operable, Comprensible y Robusto:

Para los fines de este documento solo se relacionarán descripciones y comentarios de buenas prácticas en las normas en el nivel de conformidad A. Para una consulta detallada se sugiere remitirse a la documentación oficial en: [How to Meet WCAG (Quickref Reference) (w3.org)](https://www.w3.org/WAI/WCAG21/quickref/#top)

### **2.1 Perceptible**

Este principio nos sugiere que tanto nuestros contenidos web como la interfaz con la que interactúan todos las personas usuarias, independientemente de las barreras o limitaciones que puedan tener, deben ser perceptibles por los sentidos o comprensibles mediante el raciocinio. A continuación, se presentan algunos criterios a considerar en este nivel.

#### **2.1.1 Alternativas Textuales**

Primero debes identificar todo el contenido que no sea textual y que transmite información a las personas usuarias y asegúrate de que ese mismo contenido cuente con una alternativa de texto, esto con la finalidad de que pueda cambiarse a otras formas como letra grande, braille, voz, símbolos o un lenguaje más simple. 

#### **2.1.2 Medios Basados en el tiempo (audio y vídeo)**

Este criterio nos habla del contenido de audio o video el cual debe ser adaptable y distinguible. Una medida de accesibilidad universal es brindarle a las personas usuarias siempre una alternativa de texto equivalente para que la información de los medios pueda comprenderse.

A continuación una lista de los lineamientos a considerar los cuales pueden ser consultados en detalle:

- [Solo audio y solo video (pre grabado)](https://www.w3.org/WAI/WCAG21/quickref/#audio-only-and-video-only-prerecorded)
- [Subtítulos (pre grabados)](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)
- [Descripción de audio o alternativa de medios (pre grabada)](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-or-media-alternative-prerecorded)

#### **2.1.3 Adaptable**

Para que un sitio web y su contenido sea adaptable debemos pensar en la manera en la que todas las personas usuarias interactúan con el sitio incluyendo las que cuenten con limitaciones visuales, auditivas, o motoras. Considerar y aplicar las pautas de la WCAG permite que los sitios web cuenten con estas características de adaptabilidad.

A continuación una lista de los lineamientos a considerar los cuales pueden ser consultados en detalle:

- [Información y relaciones](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#info-and-relationships)
- [Secuencia significativa](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#meaningful-sequence)
- [Características sensoriales](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#sensory-characteristics)

#### **2.1.4 Distinguible**
Facilita a los usuarios ver y escuchar contenido, incluida la separación del primer plano del fondo.

A continuación una lista de los lineamientos a considerar los cuales pueden ser consultados en detalle:

- [Uso del color](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#use-of-color)
- [Audio Control](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aa%2Caaa&technologies=css%2Cjs%2Cserver%2Csmil%2Cflash%2Csl#audio-control)

### **2.2 Operable**

Este principio hace referencia a la capacidad que tienen los sitios web modernos para que los usuarios interactúen con ellos mediante diversos componentes de la interfaz de usuario y la navegación. 

- Teclado accesible
- Tiempo suficiente
- Convulsiones y reacciones físicas
- Navegable

### **2.3 Comprensible**

Este componente se enfoca en hacer que la información y las operaciones en un sitio web sean claras y comprensibles para todos los usuarios. Esto implica presentar la información de forma clara y sencilla, organizarla de manera lógica, proporcionar instrucciones concisas y ofrecer ayuda adicional para aquellos que lo necesiten. El objetivo es garantizar que todos los usuarios puedan entender fácilmente la información y usar la interfaz del sitio web, sin importar su nivel de habilidad o conocimiento.

### **2.4 Robusto**

El contenido debe ser lo suficientemente robusto en términos de compatibilidad para que pueda ser consultado por usuarios que acceden desde diversos dispositivos, y ser interpretado por una amplia gama de agentes de usuario, incluyendo tecnologías de asistencia.

## **3 Glosario**

### **3.1 Accesibilidad universal**

La condición que deben cumplir los entornos, procesos, bienes, productos y servicios, así como los objetos o instrumentos, herramientas y dispositivos, para ser comprensibles, utilizables y practicables por todas las personas en condiciones de seguridad y comodidad, de la forma más autónoma y natural posible.

#### **3.2 Ajuste razonables**

Son las acciones que los equipos de comunicación deciden tomar para que sus contenidos sean más accesibles de modo que no afecte el trabajo de manera sustancial.

#### **3.3 modelo social de discapacidad**

Este modelo reconoce a la discapacidad como una construcción social, que no se da por las condiciones específicas de cada persona sino por la interacción de las personas con la sociedad misma. 

- #####	**3.3.1 Barreras de accesibilidad**

Este tipo de barreras nos plantea que si un contenido web no es accesible no es porque las personas usuarias tienen algún tipo de limitación para acceder a él, este nuevo paradigma implica que el contenido no es accesible, puesto que no se realizaron los ajustes razonables para que bajo un contexto de accesibilidad universal las personas puedan acceder al contenido sin ninguna barrera o limitación.

- #####	**3.3.2 Barreras situacionales**

Este tipo de barreras hace referencia a situaciones específicas en donde por razones ajenas al contenido mismo existen limitaciones en el ambiente o el lugar en donde se está, por ejemplo si debemos consultar un video, pero el ruido en el ambiente es tan fuerte que no se puede escuchar lo correcto sería que el video cuente con subtítulos.

- #####	**3.3.3 Barreras de aprendizaje**

Este tipo de barreras se refiere a que las acciones que se deben tomar en materia de accesibilidad deben pensar también en las personas usuarias que puedan llegar a tener limitaciones cognitivas o que cuenten que sean  neuro divergentes 

## **4 Comentarios finales**

La implementación de buenas prácticas para que todas las personas puedan acceder a los contenidos e información de manera igualitaria, nos permite reconocernos en un mundo increíblemente diverso, en donde un gran porcentaje de las personas en el planeta tienen algún tipo de discapacidad, por esta razón los esfuerzos en accesibilidad tienen un impacto en el goce de derechos humanos y libertades fundamentales.

El conocer y aplicar criterios como por ejemplo, el análisis y posterior implementación de las acciones mínimas razonables o la correcta implementación de legislaciones internacionales y nacionales: 

[El Tratado de Marrakech.](https://www.wipo.int/marrakesh_treaty/es/)

Según cada país la legislación que define las disposiciones para garantizar el pleno ejercicio de los derechos de las personas con discapacidad, que para el caso de Colombia es la [Ley estatutaria 1618 de 2013.](https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=52081)
 
[Cómo las personas con discapacidad usan la Web, Iniciativa de Accesibilidad Web (WAI), W3C](https://www.w3.org/WAI/people-use-web/)

La W3C (World Wide Web Consortium) ha creado las Directrices de Accesibilidad para el Contenido Web (WCAG) que establecen los criterios para que una página web sea accesible. Estas directrices se dividen en tres niveles de conformidad: A, AA y AAA.

[lista de verificación para sitios web basada en las Directrices de Accesibilidad del Contenido Web (WCAG) 2.1 nivel AA1](https://www.w3.org/WAI/gettingstarted/Overview.html.es)






