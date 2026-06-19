## 3.3. Product Backlog.

El Product Backlog se ordena según el valor de negocio entregado al usuario, no por dependencias técnicas. Por ello, las User Stories de captación y comprensión de la propuesta (visitante) encabezan la lista, seguidas del acceso a la cuenta y de la gestión central de dispositivos, que constituye el núcleo de valor para el propietario del hogar. Las stories técnicas/habilitadoras (endpoints de API y seguridad con JWT, US35–US40) se ubican como soporte de las funcionalidades que habilitan y se planifican dentro del sprint de Web Services; colocarlas al inicio sería incorrecto, ya que no entregan valor directo al usuario final.

| \# Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
| :---- | :---- | :---- | :---- | :---- |
| 1 | US01 | Visualizar propuesta de valor | Como visitante, deseo visualizar la información general de la startup para conocer su propósito. | 2 |
| 2 | US04 | Visualizar beneficios de integración | Como visitante, deseo conocer los beneficios de centralizar mis dispositivos para entender el valor de la plataforma. | 2 |
| 3 | US02 | Consultar planes de suscripción | Como visitante, deseo ver los planes de suscripción para evaluar el costo del servicio. | 1 |
| 4 | US03 | Internacionalización de contenido | Como visitante, deseo cambiar el idioma del contenido para leerlo en mi idioma preferido. | 3 |
| 5 | US05 | Soporte de accesibilidad básica | Como visitante con discapacidad visual, deseo que la plataforma soporte herramientas de asistencia. | 5 |
| 6 | US06 | Registro de cuenta nueva | Como visitante, deseo crear una cuenta para empezar a gestionar mi hogar inteligente. | 3 |
| 7 | US07 | Inicio de sesión seguro | Como propietario del hogar, deseo iniciar sesión de forma segura para acceder a mi panel central. | 3 |
| 8 | US09 | Cierre de sesión activo | Como propietario del hogar, deseo cerrar mi sesión para proteger mi información en computadoras compartidas. | 1 |
| 9 | US08 | Recuperación de credenciales | Como propietario del hogar, deseo recuperar mi contraseña si la olvido para restablecer el acceso a mi cuenta. | 5 |
| 10 | US16 | Visualización de panel de control | Como propietario del hogar, deseo visualizar un resumen del estado de mi casa en tiempo real para tomar decisiones rápidas. | 5 |
| 11 | US12 | Listado general de dispositivos | Como propietario del hogar, deseo ver todos mis dispositivos vinculados para saber qué equipos tengo integrados. | 2 |
| 12 | US11 | Vinculación de nuevo hardware | Como usuario explorador, deseo agregar un nuevo dispositivo IoT para integrarlo al sistema. | 5 |
| 13 | US17 | Control manual de encendido/apagado | Como usuario explorador, deseo encender o apagar dispositivos de forma remota para controlarlos sin estar presente. | 3 |
| 14 | US15 | Asignación espacial de dispositivos | Como propietario del hogar, deseo agrupar mis dispositivos por habitación para una gestión estructurada. | 3 |
| 15 | US13 | Edición de identificador de dispositivo | Como propietario del hogar, deseo cambiar el nombre de un dispositivo para reconocerlo más fácilmente. | 2 |
| 16 | US14 | Desvinculación de hardware obsoleto | Como usuario avanzado, deseo desvincular un dispositivo que ya no uso para mantener mi lista organizada. | 2 |
| 17 | US22 | Diagnóstico básico de hardware | Como usuario avanzado, deseo ver si un dispositivo pierde conexión para saber si hay problemas. | 3 |
| 18 | US18 | Monitoreo visual de cámaras | Como Vicente, deseo acceder a la transmisión de mis cámaras de seguridad para ver el estado de mi mascota. | 8 |
| 19 | US20 | Notificaciones de alerta de seguridad | Como propietario del hogar, deseo recibir alertas visuales en la plataforma para reaccionar ante posibles riesgos. | 5 |
| 20 | US21 | Activación de Modo Salida | Como propietario del hogar, deseo activar el "Modo Ausencia" al salir con un solo clic. | 5 |
| 21 | US19 | Regulación de temperatura | Como Jenny, deseo ajustar la temperatura del clima remotamente para encontrar mi casa confortable al llegar. | 3 |
| 22 | US23 | Creación de rutina horaria simple | Como Jenny, deseo programar el encendido de mi cafetera en la mañana para ahorrar tiempo al despertar. | 5 |
| 23 | US24 | Visualización de automatizaciones | Como propietario del hogar, deseo listar todas mis rutinas programadas para recordar qué procesos se ejecutan solos. | 3 |
| 24 | US25 | Modificación de hora de rutina | Como usuario avanzado, deseo cambiar la hora de una rutina existente para adaptarla a mi nuevo horario de trabajo. | 2 |
| 25 | US27 | Suspensión temporal de rutina | Como usuario explorador, deseo pausar una rutina sin borrarla para que no se ejecute mientras estoy de vacaciones. | 2 |
| 26 | US26 | Eliminación de programación | Como propietario del hogar, deseo borrar permanentemente una rutina que ya no necesito. | 1 |
| 27 | US28 | Resumen numérico de consumo | Como Vicente, deseo visualizar una estimación de mi consumo energético del mes para tener noción de mi gasto. | 5 |
| 28 | US29 | Desglose gráfico por equipo | Como propietario del hogar, deseo ver un gráfico circular para identificar visualmente qué aparato gasta más luz. | 3 |
| 29 | US30 | Gráfico de barras de historial | Como usuario avanzado, deseo comparar mi consumo en un gráfico de barras mensual para saber si mis ahorros funcionan. | 5 |
| 30 | US31 | Definición de límite de consumo | Como propietario del hogar, deseo establecer una meta de kWh mensual máxima en la web para no excederme. | 3 |
| 31 | US10 | Actualización de datos de perfil | Como usuario explorador, deseo actualizar mi información personal para mantener mis datos de contacto al día. | 2 |
| 32 | US33 | Visualización del estado del plan | Como propietario del hogar, deseo ver claramente en mi perfil qué tipo de plan tengo activo. | 1 |
| 33 | US32 | Mejora a plan Premium | Como usuario avanzado, deseo mejorar mi cuenta a plan premium para desbloquear la retención de datos. | 5 |
| 34 | US34 | Retorno a plan básico | Como propietario del hogar, deseo cancelar mi plan premium con un botón en mi perfil. | 3 |
| 35 | US36 | Endpoint GET de dispositivos | Como Developer, deseo construir un endpoint GET que devuelva el array de dispositivos en formato JSON. | 3 |
| 36 | US37 | Endpoint POST para registrar hardware | Como Developer, deseo crear un endpoint POST que inserte nuevos dispositivos en la base de datos validando los campos. | 3 |
| 37 | US38 | Endpoint PATCH de cambio de estado | Como Developer, deseo habilitar un endpoint PATCH ligero que solo modifique el valor booleano de un equipo. | 2 |
| 38 | US40 | Endpoint DELETE para borrar dispositivo | Como Developer, deseo exponer un endpoint DELETE que elimine definitivamente el hardware de la base de datos. | 2 |
| 39 | US35 | Seguridad de API con Token JWT | Como Developer, deseo implementar un endpoint de login que devuelva un JWT para proteger las transacciones. | 5 |
| 40 | US39 | Middleware de control de errores | Como Developer, deseo implementar un middleware global que capture excepciones para no mostrar el stack trace. | 3 |
