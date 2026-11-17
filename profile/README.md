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
| `web` | App de escritorio para la agente | En construcción |
| `mobile` | Bandeja y ficha desde el celular | En construcción |
| `api` | WhatsApp, copiloto, tarifas y HubSpot | En construcción |
| `design` | Tokens, especificaciones y referencias de Figma | En construcción |

---

<p align="center">Proyecto desarrollado con la Cámara de Comercio · Colombia 🇨🇴</p>
