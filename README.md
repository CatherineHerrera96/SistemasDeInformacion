¿Qué es AWS Lambda?

AWS Lambda permite ejecutar código en la nube solo cuando es necesario, sin administrar servidores ni infraestructura.
AWS se encarga de:

Activar la función cuando ocurre un evento

Ejecutarla

Escalar automáticamente

Cobrar únicamente por el tiempo de ejecución

⭐ ¿Por qué es útil?

Sin servidores que instalar o configurar

Bajo costo, ya que solo se paga por uso

Escalado automático sin configuraciones adicionales

Integración sencilla con servicios como S3, DynamoDB, API Gateway, etc.

⚙️ ¿Cómo funciona?

AWS Lambda actúa como una función que se activa cuando ocurre un evento.
Ejemplos:

Se sube un archivo a S3 → Lambda lo procesa

Una API recibe una petición → Lambda la responde

Una tarea programada llega a su hora → Lambda se ejecuta

La función permanece apagada hasta que es requerida.
