TRADING AI PRO — MVP inicial

Qué incluye:
- Interfaz responsive en español.
- Navegación Inicio / Oportunidades / Analista IA / Mi cartera / Mercados.
- Registro manual de compras y ventas.
- Historial local guardado en el navegador.
- Estructura PWA instalable desde un navegador compatible.

Limitaciones importantes:
- Esta primera versión NO tiene cotizaciones en directo.
- El ranking de 20 oportunidades aún no está conectado a datos de mercado.
- El analista IA es una interfaz preparada, no un modelo conectado.
- No existe conexión con Trade Republic; no se deben compartir credenciales.
- El cálculo de cartera es preliminar: no calcula todavía coste medio, posiciones netas, valoración actual ni plusvalías fiscales.

Para activar datos reales:
1. Elegir proveedores según mercados y presupuesto (por ejemplo, proveedor de cotizaciones, noticias y un servicio de IA).
2. Crear un backend seguro para guardar las claves API; nunca incrustarlas en la app.
3. Implementar normalización de símbolos, divisas, horarios, retrasos y calidad de datos.
4. Añadir análisis técnico y ranking reproducible con fecha/hora de datos.
5. Probar y empaquetar para Android con Android Studio/SDK y firma de APK.

Instalación de prueba:
- Publicar estos archivos en un hosting HTTPS o servirlos localmente.
- Abrir index.html en un navegador moderno para probar la interfaz.
- Para instalar como PWA, abrir la URL HTTPS y elegir “Añadir a pantalla de inicio”.

Este paquete es un prototipo funcional de interfaz y registro local, no una plataforma de asesoramiento ni ejecución bursátil.
