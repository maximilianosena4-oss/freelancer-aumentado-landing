# Botiquín del Freelancer Aumentado

Landing page de captura de leads: ofrece una guía gratuita ("7 Herramientas IA
+ 5 Prompts Gratis") a cambio del email del visitante.

## Qué hace

Formulario de suscripción que envía el email a una lista de contactos vía la
API de Brevo (función serverless `netlify/functions/brevo-subscribe.js`,
API key manejada por variable de entorno, sin hardcodear).

## Stack

HTML/CSS/JS estático + función serverless de Netlify (Node.js) para la
integración con Brevo.

## Estado del proyecto

Publicado en Netlify.
