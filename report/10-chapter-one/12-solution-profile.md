## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

El crecimiento del Internet de las Cosas (IoT) ha transformado los hogares tradicionales en entornos inteligentes capaces de automatizar tareas, mejorar la seguridad y optimizar energía. Sin embargo, este crecimiento ha generado una problemática grave: **la fragmentación en la administración de dispositivos**. Cada fabricante obliga al usuario a usar su propia aplicación, volviendo la experiencia compleja, poco intuitiva y frustrante para usuarios sin conocimientos técnicos avanzados. 

Para comprender mejor esta problemática, aplicamos la metodología **5W2H**:

* **What (¿Qué está ocurriendo?):** Los usuarios enfrentan gran dificultad para administrar sus dispositivos debido a la fragmentación en múltiples aplicaciones propietarias que no se comunican entre sí.
  
* **Why (¿Por qué ocurre?):** Falta de un estándar de interoperabilidad universal entre los fabricantes de hardware y ecosistemas cerrados que priorizan la retención del cliente sobre la usabilidad.
  
* **Where (¿Dónde ocurre?):** En hogares inteligentes y proyectos residenciales automatizados, especialmente en zonas urbanas con alta adopción tecnológica.
  
* **When (¿Cuándo ocurre?):** En el uso diario, particularmente al configurar rutinas, supervisar la seguridad al salir de casa o al intentar medir el consumo de energía general.
  
* **Who (¿Quiénes se ven afectados?):** Propietarios de viviendas, usuarios que recién inician en domótica y técnicos/empresas instaladoras que no pueden brindar soporte remoto eficiente.

* **How (¿Cómo ocurre?):** El usuario debe abrir la app A para encender luces, la app B para ver cámaras y la app C para el aire acondicionado, imposibilitando rutinas cruzadas (ej. "si la cámara detecta movimiento, encender la luz").

* **How much (¿Qué impacto tiene?):** * Incremento de hasta un 15% - 20% en la factura eléctrica debido a la imposibilidad de monitorear y apagar dispositivos ineficientes.
    
    * Pérdida de entre 3 a 5 horas mensuales en re-configuraciones y resolución de problemas técnicos por incompatibilidades.
    
    * Una alta tasa de frustración que lleva a que el 30% de los usuarios subutilice sus dispositivos inteligentes tras el primer mes de compra.

**Objetivo general:** Desarrollar una plataforma web capaz de centralizar la administración y monitoreo de dispositivos IoT domésticos, optimizando la experiencia de usuario y mejorando la eficiencia operativa del hogar inteligente.


### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Hemos consolidado los problemas clave para enfocar el desarrollo en soluciones reales:

* **Problem Statement 1 (Fragmentación):** Los usuarios de hogares inteligentes experimentan "fatiga de aplicaciones" al usar múltiples plataformas propietarias, lo que genera pérdida de tiempo y reduce la utilidad real de su inversión domótica.

* **Problem Statement 2 (Eficiencia y Energía):** Los propietarios necesitan optimizar el consumo de sus hogares, pero carecen de una herramienta unificada que les traduzca el uso de los dispositivos a métricas de ahorro económico comprensibles.

* **Problem Statement 3 (Soporte B2B):** Los técnicos instaladores enfrentan altos costos operativos post-venta porque no cuentan con una plataforma centralizada que les permita diagnosticar y gestionar remotamente los dispositivos de sus clientes.

#### 1.2.2.2. Lean UX Assumptions

Nuestras suposiciones iniciales se categorizan y priorizan según su nivel de riesgo y conocimiento para el proyecto:

**Suposiciones de Alto Riesgo / Poco Conocidas (High Risk - Unknown):**

* **Negocio:** Los usuarios y técnicos estarán dispuestos a pagar una suscripción Premium mensual por reportes energéticos avanzados y automatizaciones complejas.

* **Técnica:** Es factible integrar y comunicar de manera estable APIs de distintos fabricantes de IoT (Orvibo, Tuya, SmartThings) bajo nuestro propio backend sin alta latencia.

**Suposiciones de Riesgo Medio / Conocidas (Medium Risk - Known):**

* **Usuario:** Los usuarios valoran una interfaz intuitiva por encima de una sobrecarga de funciones técnicas.

* **Valor:** La visualización de datos de consumo energético incentivará hábitos más eficientes e incrementará la retención (engagement) en la plataforma.

#### 1.2.2.3. Lean UX Hypothesis Statements

Para mantener el foco del MVP, hemos consolidado nuestras hipótesis en las cuatro más críticas para el modelo de negocio:

* **Hipótesis 1: Centralización y Control (Core Value)**
    
    * **Creemos que:** Diseñar un dashboard centralizado que agrupe dispositivos de múltiples marcas...
    * **Para:** Propietarios de hogares inteligentes fatigados por el uso de múltiples apps...
    * **Lograremos:** Simplificar drásticamente la interacción diaria con el hogar.
    * **Sabremos que hemos tenido éxito cuando:** El 80% de las acciones diarias se ejecuten con éxito desde nuestra plataforma sin que el usuario necesite abrir la app del fabricante original.

* **Hipótesis 2: Automatización Intuitiva (Usability)**
    
    * **Creemos que:** Implementar un motor de creación de rutinas visual y sin código...
    * **Para:** Usuarios sin conocimientos técnicos avanzados...
    * **Lograremos:** Que los usuarios exploten el verdadero potencial autónomo de sus dispositivos.
    * **Sabremos que hemos tenido éxito cuando:** El 60% de los usuarios registrados configure al menos 2 rutinas automatizadas en su primera semana de uso, tardando menos de 2 minutos por rutina.

* **Hipótesis 3: Analítica de Consumo (Retention & Engagement)**
    
    * **Creemos que:** Incorporar un módulo de analítica que traduzca kilowatts a ahorro monetario local...
    * **Para:** Usuarios preocupados por la eficiencia energética y el costo de servicios...
    * **Lograremos:** Incrementar el uso recurrente de la plataforma y justificar el valor del sistema.
    * **Sabremos que hemos tenido éxito cuando:** El 50% de los usuarios revise el módulo de energía al menos una vez por semana y logre una reducción medible en su consumo estimado.

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas resume la visión del producto, los problemas identificados, los segmentos de usuarios, las suposiciones y las hipótesis definidas previamente. Este modelo permite alinear el desarrollo del software con las necesidades reales del usuario y los objetivos del negocio. 

A continuación, se presenta el Lean UX Canvas del proyecto:

\includegraphics[width=\linewidth]{assets/lean-ux-canvas-01.png}