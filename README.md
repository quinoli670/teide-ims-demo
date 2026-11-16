# Teide IMS · Prefabricados Teide S.L.

Prototipo funcional de la plataforma integral de gestión técnica de Teide IMS (Grupo Fedola).

**Demo en línea (PWA instalable):** https://quinoli670.github.io/teide-ims-demo/

> Todos los datos son **datos de ejemplo** ficticios. Se guardan solo en el navegador o equipo de cada usuario (localStorage) y se pueden restablecer en *Ajustes*.

## Módulos
Cuadro de mando con asistente IA · Helpdesk de incidencias (10 estados, SLA, kanban) · Partes de trabajo (firma, fotos, PDF) · App del técnico (sin conexión) · Planificación con propuestas de IA y mapa de Tenerife · CRM y pipeline · Obras (presupuesto frente a ejecutado) · Contratos (SLA, renovaciones, facturación) · Instalaciones y QR (preventivo, predictivo y correctivo) · Almacén y compras · Rentabilidad · Documentación · Integración GF Hoteles: gestión de activos y eficiencia energética (EMS) · Comparativa de soluciones.

## Instalación
- **Navegador (Chrome/Edge):** abre la demo y pulsa «Instalar» en la barra de direcciones o en la barra superior de la aplicación.
- **Android/iOS:** abre la demo y elige «Añadir a pantalla de inicio».
- **Windows:** instalador `Teide-IMS-Setup-1.0.0.exe` o versión portable (se distribuyen aparte).

## Desarrollo
```bash
npm install
npm run dev          # desarrollo
npm run build        # web/PWA en dist/
npm run dist:win     # instalador NSIS + portable para Windows (release/)
npm run dist:linux   # AppImage (release/)
```
Stack: Vite, React 18, TypeScript, Recharts, vite-plugin-pwa y Electron.
