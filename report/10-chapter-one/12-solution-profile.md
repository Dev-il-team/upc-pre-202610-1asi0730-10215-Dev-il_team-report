## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

En los últimos años, el crecimiento del Internet de las Cosas (IoT) ha transformado progresivamente los hogares tradicionales en entornos inteligentes capaces de automatizar tareas, mejorar la seguridad y optimizar el consumo energético. Actualmente, dispositivos como luces inteligentes, cámaras de vigilancia, sensores de movimiento, asistentes virtuales y sistemas de climatización conectados forman parte de la vida cotidiana de muchos usuarios.

Sin embargo, este crecimiento tecnológico también ha generado una problemática importante relacionada con la fragmentación en la administración de dispositivos inteligentes. La mayoría de fabricantes desarrolla sus propios ecosistemas y aplicaciones, obligando a los usuarios a utilizar múltiples plataformas para controlar distintos dispositivos dentro de un mismo hogar. Como consecuencia, la experiencia de usuario se vuelve compleja, poco intuitiva y limitada en términos de integración y automatización.

Además, muchas soluciones existentes presentan barreras técnicas para usuarios con conocimientos tecnológicos básicos, dificultando la configuración de automatizaciones, el monitoreo centralizado y la supervisión eficiente del consumo energético. Esta situación reduce el aprovechamiento real de las tecnologías IoT y afecta directamente la comodidad, seguridad y eficiencia operativa del hogar inteligente.

Con el propósito de comprender mejor la problemática identificada, se aplica la metodología 5W2H, la cual permite analizar el contexto del problema de manera estructurada.

* **What (¿Qué está ocurriendo?):** 

Los usuarios de hogares inteligentes enfrentan dificultades para administrar y monitorear sus dispositivos debido a la existencia de múltiples aplicaciones y plataformas independientes. Esto limita la capacidad de control centralizado, automatización y supervisión eficiente del hogar.

* **Why (¿Por qué ocurre?):** 

La problemática ocurre porque cada fabricante implementa soluciones propietarias con poca interoperabilidad entre dispositivos de distintas marcas. Asimismo, muchas plataformas actuales poseen interfaces complejas o procesos de configuración poco accesibles para usuarios sin conocimientos técnicos avanzados.

* **Where (¿Dónde ocurre?):** 

El problema se presenta principalmente en hogares inteligentes que utilizan dispositivos IoT de diferentes fabricantes, especialmente en viviendas urbanas donde existe una creciente adopción de tecnologías domóticas y automatización residencial.

* **When (¿Cuándo ocurre?):** 

La problemática se manifiesta durante el uso cotidiano de los dispositivos inteligentes, especialmente cuando los usuarios necesitan controlar múltiples sistemas simultáneamente, monitorear el estado general del hogar o configurar automatizaciones para tareas recurrentes.

* **Who (¿Quiénes se ven afectados?):** Los principales afectados son:

    * Propietarios de viviendas inteligentes
    * Usuarios interesados en implementar soluciones smart home
    * Familias que buscan optimizar seguridad y consumo energético
    * Técnicos o empresas de instalación domótica
    * Usuarios con conocimientos tecnológicos básicos que requieren plataformas intuitivas y centralizadas

* **How (¿Cómo ocurre?):** La problemática se evidencia mediante:

    * Pérdida de tiempo en la administración manual de dispositivos
    * Reducción en la eficiencia energética del hogar
    * Incremento del consumo eléctrico debido a la falta de monitoreo centralizado
    * Menor aprovechamiento de las capacidades de automatización IoT
    * Incremento en la frustración y dependencia tecnológica del usuario
    * Disminución de la accesibilidad para usuarios sin experiencia técnica


* **How much (¿Qué impacto tiene?):** El impacto de esta problemática incluye:

    * Pérdida de tiempo en la administración manual de dispositivos
    * Reducción en la eficiencia energética del hogar
    * Incremento del consumo eléctrico debido a la falta de monitoreo centralizado
    * Menor aprovechamiento de las capacidades de automatización IoT
    * Incremento en la frustración y dependencia tecnológica del usuario
    * Disminución de la accesibilidad para usuarios sin experiencia técnica

**Conclusión del análisis**

A partir del análisis realizado, se identifica la necesidad de desarrollar una solución que permita centralizar, simplificar y optimizar la gestión de dispositivos inteligentes dentro del hogar. En este contexto, la plataforma web Smart Home HERA surge como una propuesta orientada a integrar dispositivos IoT en un único entorno de administración, facilitando el monitoreo, automatización y control eficiente del hogar inteligente.

La solución busca mejorar significativamente la experiencia de usuario mediante una interfaz intuitiva, accesible y enfocada en la interoperabilidad entre dispositivos, promoviendo además una mayor eficiencia energética, comodidad y seguridad residencial.

* **Objetivos de la solución:**

* **Objetivo general:**

Desarrollar una plataforma web capaz de centralizar la administración y monitoreo de dispositivos IoT domésticos, optimizando la experiencia de usuario y mejorando la eficiencia operativa del hogar inteligente.

* **Objetivos especificos:**

    * Integrar múltiples dispositivos inteligentes dentro de una única plataforma centralizada
    * Facilitar el monitoreo en tiempo real del estado del hogar inteligente
    * Permitir la automatización de tareas domésticas mediante rutinas configurables
    * Proporcionar visualización del consumo energético de los dispositivos conectados
    * Mejorar la accesibilidad y facilidad de uso mediante una interfaz intuitiva y responsive
    * Incrementar la interoperabilidad entre dispositivos IoT de distintos fabricantes

* **Restricciones del proyecto:**

    * Dependencia de la compatibilidad y disponibilidad de APIs proporcionadas por fabricantes de dispositivos IoT
    * Limitaciones de interoperabilidad entre ciertos protocolos y ecosistemas propietarios
    * Necesidad de conexión estable a internet para la sincronización y monitoreo en tiempo real
    * Alcance limitado al desarrollo de una aplicación web responsive, sin implementación móvil nativa
    * Restricciones de tiempo y recursos del equipo de desarrollo durante el ciclo académico
    * Limitaciones asociadas al uso de servicios externos y simulación de dispositivos IoT durante el desarrollo del proyecto

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Dentro del enfoque Lean UX, los Problem Statements permiten definir de manera clara y centrada en el usuario los principales problemas que la solución busca resolver. Estos enunciados ayudan a enfocar el diseño del producto en necesidades reales, evitando suposiciones y guiando el desarrollo hacia una experiencia de usuario efectiva.

Para contextualizar los problemas identificados, se definen los siguientes elementos:

* **Domain:** Gestión de hogares inteligentes (IoT).

* **Customer Segments:** Propietarios, nuevos usuarios, técnicos.

* **Pain Points:** Fragmentación, falta de integración, complejidad.

* **Gap:** No existe una plataforma unificada simple.

* **Visión/Strategy:** Centralizar y simplificar la gestión del hogar.

A partir de este contexto, se han identificado los siguientes Lean UX Problem Statements:

* **Problem Statement 1:** 

Los propietarios de hogares inteligentes necesitan una forma sencilla y centralizada de gestionar todos sus dispositivos, ya que actualmente deben utilizar múltiples aplicaciones, lo que genera confusión, pérdida de tiempo y una experiencia poco eficiente.

* **Problem Statement 2:** 

Los usuarios requieren visualizar el estado general de su hogar en tiempo real, debido a que no cuentan con una plataforma que les permita monitorear de forma integrada aspectos como iluminación, seguridad, temperatura y consumo energético.

* **Problem Statement 3:** 

Las personas que desean automatizar su hogar necesitan herramientas intuitivas para programar rutinas, ya que las soluciones actuales suelen ser complejas o requieren conocimientos técnicos avanzados.

* **Problem Statement 4:** 

Los usuarios necesitan optimizar el consumo energético de sus hogares, pero no disponen de información clara ni de herramientas que les permitan analizar y controlar el uso de energía de sus dispositivos.

* **Problem Statement 5:** 

Los técnicos y empresas de instalación domótica requieren una plataforma que facilite la gestión y monitoreo de múltiples hogares, ya que actualmente no cuentan con una solución unificada para brindar soporte eficiente a sus clientes.

#### 1.2.2.2. Lean UX Assumptions

En el enfoque Lean UX, las assumptions (suposiciones) representan hipótesis iniciales sobre los usuarios, sus necesidades, comportamientos y el valor que ofrece la solución. Estas suposiciones deben ser posteriormente validadas mediante pruebas con usuarios o prototipos.

A continuación, se presentan las principales suposiciones identificadas para el desarrollo de la solución propuesta:

1. **Suposiciones sobre los usuarios:**
    * Los usuarios desean simplificar la gestión de sus dispositivos inteligentes mediante una única plataforma centralizada.
    * Los usuarios valoran una interfaz intuitiva y fácil de usar, sin necesidad de conocimientos técnicos avanzados.
    * Los usuarios utilizan con frecuencia dispositivos móviles, por lo que esperan que la solución sea completamente responsive.
    * Los usuarios están interesados en mejorar la comodidad, seguridad y control de su hogar.

2. **Suposiciones sobre el problema:**
    * El uso de múltiples aplicaciones para gestionar dispositivos genera confusión y baja eficiencia.
    * La falta de integración entre dispositivos de distintas marcas es una de las principales barreras en la adopción de smart homes.
    * Los usuarios no cuentan con herramientas claras para monitorear el consumo energético.
    * La automatización del hogar es percibida como compleja o difícil de configurar.

3. **Suposiciones sobre la solución:**
    * Una aplicación web centralizada mejorará significativamente la experiencia del usuario.
    * Un dashboard visual permitirá una mejor comprensión del estado del hogar.
    * La incorporación de automatizaciones facilitará la vida diaria de los usuarios.
    * La visualización de datos de consumo energético incentivará hábitos más eficientes.

4. **Suposiciones sobre el valor del producto:**
    * Los usuarios estarán dispuestos a utilizar la plataforma si esta les ahorra tiempo y esfuerzo.
    * Existe interés en funcionalidades avanzadas mediante un modelo de suscripción premium.
    * La centralización de dispositivos será percibida como un valor diferencial frente a otras soluciones.

5. **Suposiciones sobre el negocio:**
    * El mercado de hogares inteligentes continuará en crecimiento, aumentando la demanda de soluciones de gestión.
    * Se pueden establecer alianzas con técnicos o empresas domóticas para ampliar el alcance del producto.
    * El modelo de suscripción es viable y sostenible a largo plazo.

#### 1.2.2.3. Lean UX Hypothesis Statements

* **Hipótesis 1: Dashboard centralizado**

    * **Creemos que:** Construir un dashboard centralizado que integre dispositivos de diferentes marcas en una sola plataforma

    * **Para:** Propietarios de hogares inteligentes que utilizan múltiples aplicaciones para gestionar sus dispositivos

    * **Lograremos:** Simplificar la gestión del hogar y reducir la fricción operativa

    * **Sabremos que hemos tenido éxito cuando veamos:** Que el 80% de las acciones se realizan sin salir de la aplicación; Una reducción del 30% en el tiempo de ejecución de tareas comunes (encender luces, ajustar temperatura, etc.)

* **Hipótesis 2: Visualización del estado del hogar**

    * **Creemos que:** Diseñar un panel visual que muestre el estado general del hogar en tiempo real

    * **Para:** Usuarios que necesitan supervisar múltiples dispositivos sin una vista unificada

    * **Lograremos:** Mejorar la comprensión del estado del hogar y la toma de decisiones rápida

    * **Sabremos que hemos tenido éxito cuando veamos:** Que el 85% de los usuarios consulta el dashboard en cada sesión; Que el tiempo promedio para entender el estado del hogar es menor a 10 segundos

* **Hipótesis 3: Automatización de rutinas**

    * **Creemos que:** Implementar un sistema sencillo de creación de rutinas automatizadas

    * **Para:** Usuarios que desean automatizar tareas pero encuentran complejas las soluciones actuales

    * **Lograremos:** Facilitar la automatización del hogar y mejorar la comodidad del usuario

    * **Sabremos que hemos tenido éxito cuando veamos:** Que al menos el 60% de los usuarios crea una rutina durante la primera semana; Que el tiempo promedio de configuración es menor a 2 minutos

* **Hipótesis 4: Monitoreo de consumo energético**

    * **Creemos que:** Incorporar un módulo de visualización y análisis del consumo energético

    * **Para:** Usuarios interesados en optimizar el uso de energía en su hogar

    * **Lograremos:** Fomentar un uso más eficiente de los recursos energéticos

    * **Sabremos que hemos tenido éxito cuando veamos:** Que el 70% de los usuarios consulte el módulo semanalmente; Que el 60% identifique oportunidades de ahorro

* **Hipótesis 5: Experiencia de usuario intuitiva**

    * **Creemos que:** Diseñar una interfaz simple, intuitiva y responsive

    * **Para:** Usuarios con conocimientos técnicos básicos

    * **Lograremos:** Reducir la curva de aprendizaje y mejorar la usabilidad del sistema

    * **Sabremos que hemos tenido éxito cuando veamos:** Una puntuación mínima de 4/5 en pruebas de usabilidad; Que el 90% de los usuarios completa tareas básicas sin asistencia

* **Hipótesis 6: Funcionalidades premium**

    * **Creemos que:** Ofrecer funcionalidades avanzadas mediante un plan premium(automatizaciones avanzadas, reportes, alertas)

    * **Para:** Usuarios avanzados y empresas de domótica

    * **Lograremos:** Incrementar el valor percibido del producto y generar ingresos sostenibles

    * **Sabremos que hemos tenido éxito cuando veamos:** Que el 20% de los usuarios muestra interés en el plan premium; Que al menos el 10% estaría dispuesto a pagar por estas funcionalidades

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas resume la visión del producto, los problemas identificados, los segmentos de usuarios, las suposiciones y las hipótesis definidas previamente. Este modelo permite alinear el desarrollo del software con las necesidades reales del usuario y los objetivos del negocio. A continuación, se presenta el Lean UX Canvas del proyecto:

