<p align="center">
  <img src="https://github.com/excursion-copilot.png" width="120" alt="Excursion Copilot">
</p>

<h1 align="center">Excursion Copilot</h1>

<p align="center">
  Un copiloto de cotización para la agencia de viajes Excursión por Colombia y el Mundo.<br>
  La IA prepara, la agente decide.
</p>

---

## ¿Qué estamos construyendo?

Hoy cada cotización se arma a mano: la agente lee el chat de WhatsApp, busca hoteles y vuelos uno por uno en HotelDO, pasa los precios a un Excel, calcula su margen y responde. Eso puede tomar unas tres horas por cliente, y es fácil que se escape una fecha, un aeropuerto o un tramo del viaje.

Excursion Copilot lee la conversación con el cliente, saca los datos del viaje, arma el itinerario, compara tarifas vigentes y deja lista la cotización para que la agente la revise y la envíe. La idea es pasar de horas a unos 20 minutos, sin perder el trato personal que hace que los clientes vuelvan.

## Cómo funciona

1. Bandeja de solicitudes: los mensajes de WhatsApp Business se convierten en solicitudes con fechas, ciudades, viajeros y preferencias ya extraídas.
2. Ficha del cliente: la agente confirma lo que entendió la IA y envía, con un clic, las preguntas que faltan.
3. Itinerario: una línea de tiempo día a día que avisa si falta un hotel, un vuelo o si algo no coincide con lo que pidió el cliente.
4. Comparador: vuelos, hoteles y traslados con tarifas vigentes y una recomendación explicada.
5. Cotización: desglose, margen de la agencia, PDF para el cliente y aprobación antes de enviar.
6. Seguimiento: cada cotización queda registrada en HubSpot con su estado y la tasa de cierre.

## Principios

- Nada le llega al cliente sin la aprobación de la agente.
- Los precios salen de tarifas consultadas con fecha de vigencia, nunca de la memoria del modelo.
- La base de conocimiento guarda políticas, hoteles y criterios de la agencia, no precios.
- Cada itinerario se valida contra lo que el cliente pidió en el chat.

## Repositorios

| Repositorio | Qué contiene | Estado |
| --- | --- | --- |
| [`excursion-copilot-web`](https://github.com/excursion-copilot/excursion-copilot-web) | App de la agente en escritorio y celular: bandeja, ficha, itinerario, comparador, cotización, seguimiento y proveedores | ✅ Todas las pantallas del Figma · 🔄 conexión con la API en revisión |
| [`excursion-copilot-api`](https://github.com/excursion-copilot/excursion-copilot-api) | Inicio de sesión con roles (agente y administrador), datos de cada pantalla y PDF de la cotización | 🔄 Primera versión en revisión |
| Integraciones | WhatsApp, tarifas en vivo y HubSpot | 🗓️ Siguiente etapa |
| [Diseño en Figma](https://www.figma.com/design/PUkTOA1b5ydSnf8niAJBym/Copiloto-de-Cotizaci%C3%B3n-%C2%B7-Excursi%C3%B3n-por-Colombia-y-el-Mundo?node-id=70-2) | Mockup y prototipo navegable de todas las pantallas | ✅ Listo |

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-0B3B47?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/TypeScript-5-1A6273?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind-4-E8603C?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/FastAPI-0.115-0E4D5C?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Figma-dise%C3%B1o-6B4FA0?style=flat-square&logo=figma&logoColor=white" alt="Figma">
</p>

---

<p align="center">Proyecto desarrollado con la Cámara de Comercio · Colombia 🇨🇴</p>
