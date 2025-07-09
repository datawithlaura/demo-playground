4i Digital - Playground de Verificación
Introducción
Bienvenido al Playground de Verificación de 4i Digital. Esta es una aplicación web interactiva diseñada para demostrar las capacidades de nuestra suite de servicios de verificación de identidad. Los clientes y desarrolladores pueden usar este "sandbox" para probar los flujos de trabajo de cada servicio de una manera segura y controlada, utilizando datos de simulación.

La aplicación es completamente funcional en el navegador y no requiere ninguna instalación ni configuración de backend.

Características Principales
Este playground incluye demostraciones para los siguientes servicios:

1. Liveness (Prueba de Vida)
Función: Verifica que un usuario es una persona real y presente físicamente.

Demo: Guía al usuario a través de un escaneo de video corto, simulando movimientos de cabeza para prevenir ataques de suplantación de identidad (spoofing) con fotos o videos.

2. Face Match
Función: Compara biométricamente una selfie en vivo con la foto de un documento de identidad.

Demo: Permite al usuario subir una foto de su ID y luego capturar una selfie. El sistema simula una comparación y devuelve un puntaje de similitud.

3. Verificación de Documentos
Función: Extrae y valida datos de documentos de identidad oficiales.

Demo: Permite seleccionar un país de América Latina (México, Argentina, Colombia, Perú) y simula la carga del anverso y reverso de un documento para extraer y mostrar los datos verificados.

4. Detector de Edad
Función: Estima el rango de edad de una persona a partir de su rostro.

Demo: Utiliza la cámara para capturar una imagen del usuario y proporciona una estimación de su edad.

5. Inteligencia de Dispositivo
Función: Recopila datos del dispositivo del usuario para análisis de riesgo y prevención de fraude.

Demo: Muestra información básica del dispositivo que se está utilizando, como el navegador, sistema operativo y resolución de pantalla, para ilustrar el tipo de datos que se pueden analizar.

6. Credenciales Verificables (VC)
Función: Demuestra la emisión y verificación de credenciales digitales descentralizadas.

Demo: Permite simular la emisión de una "Identidad Verificada" en formato JWT (JSON Web Token) y luego verificar la validez de dicha credencial.

¿Cómo Usar la Aplicación?
Navegación: Utilice el menú de la barra lateral izquierda para seleccionar el servicio que desea probar.

Interacción: Cada módulo tiene instrucciones claras en pantalla. Siga los pasos, como activar su cámara o subir archivos.

Resultados: Después de cada proceso, la aplicación mostrará un resultado simulado (éxito o fallo) junto con datos de ejemplo.

Nota Importante: Esta aplicación es una demostración. No se almacenan ni se envían datos personales a ningún servidor. Todas las operaciones y resultados son simulados para fines ilustrativos.

Detalles Técnicos
Frontend: La aplicación está construida como un único archivo HTML.

Estilos: Se utiliza Tailwind CSS para un diseño moderno y responsivo.

Lógica: Toda la interactividad se maneja con JavaScript puro (vanilla JS), sin dependencias de frameworks externos.
