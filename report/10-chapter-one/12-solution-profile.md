## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

En los últimos años, el crecimiento del Internet de las Cosas (IoT) ha impulsado la adopción de dispositivos inteligentes en los hogares, tales como luces automatizadas, cámaras de seguridad, sensores de movimiento, sistemas de climatización y electrodomésticos conectados. Sin embargo, este avance tecnológico ha traído consigo una problemática importante: la fragmentación en la gestión de dispositivos.

Muchos usuarios deben utilizar múltiples aplicaciones para controlar distintos dispositivos, lo que genera una experiencia poco eficiente, confusa y limitada. Además, existe una falta de herramientas accesibles que permitan integrar, automatizar y monitorear todos los dispositivos desde una sola plataforma.

Para comprender mejor esta problemática, se aplica la metodología 5W2H, la cual permite analizar el problema de forma estructurada:

* **What (¿Qué está ocurriendo?):** Los usuarios de hogares inteligentes enfrentan dificultades para gestionar sus dispositivos debido a la existencia de múltiples plataformas y aplicaciones independientes. Esto limita la eficiencia, la comodidad y el control integral del hogar.

* **Why (¿Por qué ocurre?):** Porque cada fabricante de dispositivos IoT desarrolla su propia aplicación, lo que impide una integración unificada. Además, muchas soluciones existentes son complejas, poco intuitivas o requieren conocimientos técnicos avanzados.

* **Where (¿Dónde ocurre?):** Este problema se presenta en hogares que cuentan con dispositivos inteligentes, especialmente en aquellos donde se han adquirido productos de diferentes marcas o proveedores tecnológicos.

* **When (¿Cuándo ocurre?):** Ocurre de manera constante durante el uso cotidiano de los dispositivos, especialmente cuando el usuario necesita controlar múltiples elementos del hogar o realizar tareas repetitivas sin automatización.

* **Who (¿Quiénes se ven afectados?):**
    * Propietarios de viviendas inteligentes
    * Personas que desean convertir su hogar en smart home
    * Técnicos o empresas de instalación domótica
    * Usuarios con conocimientos tecnológicos básicos que buscan soluciones simples

* **How (¿Cómo ocurre?):** La problemática se manifiesta a través de:
    * uso de múltiples aplicaciones para diferentes dispositivos
    * dificultad para monitorear el estado general del hogar
    * falta de automatización centralizada
    * procesos manuales repetitivos
    * poca visibilidad del consumo energético

* **How much (¿Qué impacto tiene?):** El impacto incluye:
    * pérdida de tiempo en la gestión de dispositivos
    * reducción en la eficiencia del hogar
    * menor aprovechamiento de la tecnología IoT
    * aumento del consumo energético por falta de control
    * frustración del usuario debido a la complejidad del sistema

**Conclusión del análisis**

A partir del análisis, se identifica la necesidad de una solución que permita centralizar, simplificar y optimizar la gestión de dispositivos inteligentes en el hogar. En este contexto, la propuesta de una aplicación web como Smart Home HERA surge como una alternativa que busca integrar todos los dispositivos en una única plataforma, mejorando la experiencia del usuario y promoviendo la eficiencia, seguridad y comodidad.

En base a la problemática identificada, se definen los siguientes objetivos de la solución:

* **Objetivos de la solución:**
    * Desarrollar una aplicación web que centralice la gestión de dispositivos IoT
    * Facilitar el control y monitoreo del hogar inteligente
    * Permitir la automatización de tareas domésticas
    * Mejorar la experiencia de usuario mediante una interfaz intuitiva

* **Restricciones del proyecto:**
    * Dependencia de la compatibilidad con dispositivos IoT existentes
    * Limitaciones de integración con APIs de terceros
    * Necesidad de conexión a internet para el funcionamiento del sistema
    * Alcance limitado a una aplicación web (no app móvil nativa)
    * Tiempo y recursos del equipo de desarrollo

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

* **Problem Statement 1:** Los propietarios de hogares inteligentes necesitan una forma sencilla y centralizada de gestionar todos sus dispositivos, ya que actualmente deben utilizar múltiples aplicaciones, lo que genera confusión, pérdida de tiempo y una experiencia poco eficiente.

* **Problem Statement 2:** Los usuarios requieren visualizar el estado general de su hogar en tiempo real, debido a que no cuentan con una plataforma que les permita monitorear de forma integrada aspectos como iluminación, seguridad, temperatura y consumo energético.

* **Problem Statement 3:** Las personas que desean automatizar su hogar necesitan herramientas intuitivas para programar rutinas, ya que las soluciones actuales suelen ser complejas o requieren conocimientos técnicos avanzados.

* **Problem Statement 4:** Los usuarios necesitan optimizar el consumo energético de sus hogares, pero no disponen de información clara ni de herramientas que les permitan analizar y controlar el uso de energía de sus dispositivos.

* **Problem Statement 5:** Los técnicos y empresas de instalación domótica requieren una plataforma que facilite la gestión y monitoreo de múltiples hogares, ya que actualmente no cuentan con una solución unificada para brindar soporte eficiente a sus clientes.

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

