# Legaz Psicología

Código fuente de la web de Ianire Legaz.

## Estructura

- `dist/index.html`: página completa, estilos y JavaScript.
- `dist/hero-consulta.webp`: imagen principal.
- `.openai/hosting.json`: configuración del proyecto en ChatGPT Sites.
- <div style="margin-bottom: 24px; text-align: center;">
  <img src="Iani.jpeg" 
       alt="Ianire Legaz Sagarzazu, Psicóloga General Sanitaria" 
       style="width: 240px; height: 240px; object-fit: cover; border-radius: 24px; box-shadow: 0 10px 25px rgba(0,0,0,0.08);" />
</div>
<div style="display: flex; flex-wrap: wrap; gap: 12px; margin-top: 16px;">
  <a href="https://wa.me..." 
     target="_blank" 
     rel="noopener noreferrer"
     style="background-color: #163638; color: #ffffff; padding: 12px 20px; border-radius: 999px; text-decoration: none; font-weight: 600;">
    Pedir cita por WhatsApp
  </a>

  <a href="https://doctoralia.es" 
     target="_blank" 
     rel="noopener noreferrer"
     style="background-color: #ffffff; color: #163638; border: 1px solid #163638; padding: 12px 20px; border-radius: 999px; text-decoration: none; font-weight: 600;">
    Reservar en Doctoralia
  </a>

  <a href="mailto:psicologialegaz@://gmail.com"
     style="background-color: #ffffff; color: #163638; border: 1px solid #163638; padding: 12px 20px; border-radius: 999px; text-decoration: none; font-weight: 600;">
    psicologialegaz@gmail.com
  </a>
</div>


## Abrir la web

Puedes abrir `dist/index.html` directamente en un navegador. Para publicarla en otro alojamiento, sube el contenido completo de la carpeta `dist` manteniendo la carpeta `assets`.

## Estado actual

- La web contiene `noindex,nofollow` mientras esté en preparación.
- El formulario de cita es una demostración visual y todavía no envía ni guarda información.
- Antes del lanzamiento deben completarse los datos profesionales, contacto, textos legales y la conexión con la agenda.

## Dominio

El dominio no se configura dentro del HTML. Debe conectarse desde ChatGPT Sites y mediante los registros DNS del proveedor donde se compró.
