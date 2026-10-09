# MonteSion Campestre · Lotes en Lorica

App (PWA) estilo Toyota para que **Sonia Polo (300 265 7818)** venda lotes de MonteSion Campestre, hecha con la información del brochure oficial del proyecto.

**URL:** https://haroldco45.github.io/montesion-lotes/

## Qué trae
- Portada a pantalla completa con la portería, precio desde $70.000.000 y cuota inicial desde $3.000.000.
- Cifras: 15 hectáreas, 181 lotes, 500 m², 3 etapas, 0% intereses.
- Ubicación estratégica: 3 km de Lorica, 15 min de San Antero, 20 min de Coveñas, vista a la ciénaga.
- Las 3 etapas (Flamenco, Colibrí, Pelícano) con sello "¡Se acaban!" en Flamenco.
- Plano general y **selector de lote de Flamenco**: el cliente toca un número y le pregunta a Sonia por ese lote.
- **Simulador de los 4 planes de pago** del brochure, con cuotas calculadas.
- Promo 7% (8 oct – 8 nov 2026) con contador; se oculta sola al vencer.
- Por qué elegirlo (10 razones), servicios, amenidades en carrusel, diseño arquitectónico.
- Piezas para descargar y compartir.
- Sala de ventas con "Abierta / Cerrada ahora" (hora Colombia) y agenda de visitas por WhatsApp.
- Llamar y WhatsApp a Sonia desde la barra fija. Habeas Data. Instalable.

## Código de referido
Todo sale con **HAROLD-HM (Harold Marín)** al final de cada mensaje a Sonia. El botón Compartir manda `?ref=HAROLD-HM`. Otro referidor usa su propio enlace, por ejemplo `?ref=ANA-77`.

## Configuración (index.html)
```js
const WHATSAPP = "573002657818"; // Sonia Polo
const VALOR_LOTE = 70000000;     // si cambia el precio, se cambia aquí y el simulador se recalcula
```

## Publicar
1. Crear el repo `haroldco45/montesion-lotes`.
2. Subir **todos los archivos sueltos en la raíz** (no hay carpetas).
3. Settings → Pages → Branch `main` / root.

---
Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados
