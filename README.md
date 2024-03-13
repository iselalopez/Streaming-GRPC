# Streaming-GRPC
Ejemplo desarrollado para probar los diferentes tipos de Streaming ofrecidos por gRPC.

Streaming bidireccional: en la que tanto el cliente como el servidor envían mensajes entre sí de forma simultánea, es decir, sin esperar respuesta del otro lado.
Streaming del servidor: el cliente envía una única solicitud y el servidor puede retornar múltiples respuestas, es decir, un flujo de respuesta.
Streaming del cliente: donde el cliente envía múltiples peticiones y el servidor devuelve una única respuesta.
Unaria: el cliente envía una única solicitud y el servidor devuelve una única respuesta.
