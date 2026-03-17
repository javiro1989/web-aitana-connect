# Aitana Landing Page

Landing page de **Aitana Connect** — Sistema inteligente de gestión de comunicación con pacientes vía WhatsApp para clínicas médicas en Latinoamérica.

## Sobre Aitana

Aitana es una plataforma SaaS que opera como agente inteligente sobre WhatsApp para clínicas y consultorios médicos. Automatiza la atención a pacientes: recordatorios de citas, respuestas a preguntas frecuentes, detección de leads con intención de compra, recolección de feedback y derivación a agentes humanos.

## Estructura

```
index.html    ← Landing page completa (HTML/CSS/JS en un solo archivo)
README.md     ← Este archivo
```

## Características de la landing

- **Posicionamiento Blue Ocean**: "Construido para clínicas. Por médicos." — diferenciación explícita vs. CRMs genéricos y chatbots
- **Messaging centrado en problemas del cliente**, no en features del producto
- **Secciones**: Hero → Problema → Solución (outcomes) → Antes/Después → Diferenciadores → Pricing → Prueba social → Equipo → FAQ → CTA
- **Branding**: Paleta Aitana (#6529FF, #EDE6FF, #1A1A2E), tipografía Poppins, logos embebidos en base64
- **CTAs**: Todos apuntan a TidyCal para agendar demo
- **Responsive**: Adaptado a desktop, tablet y móvil
- **Animaciones**: Scroll reveal, floating phone mockup, chat bubble sequence
- **Self-contained**: Sin dependencias externas más allá de Google Fonts (Poppins)

## Deploy

Archivo estático. Se puede servir desde cualquier hosting:

- **Netlify**: Arrastra la carpeta al dashboard
- **GitHub Pages**: Settings → Pages → Deploy from branch
- **Vercel**: `vercel --prod`
- **Cualquier servidor**: Sirve `index.html` como archivo estático

## Notas de desarrollo

### v1.0 — 17 de marzo, 2026

- Landing page completa con todas las secciones
- Posicionamiento alineado al análisis Blue Ocean (vs. Kommo, ManyChat, AgendaPro)
- Sección de solución reescrita desde outcomes del cliente, no features del producto
- CTAs unificados a TidyCal (`tidycal.com/javiersanchez/aitana-gestion-de-pacientes-por-whatsapp`)
- Logos oficiales de Aitana embebidos (color para fondos claros, b/n para fondos oscuros)
- Copyright actualizado: "Aitana es una marca de Innovation & Healthcare Technologies S.A.C."
- Footer simplificado: solo secciones Producto y Contacto (hola@aitana.pro)
- Phone mockup usa "Clínica Aitana" (nombre genérico, no clientes reales)

### Pendientes

- [ ] Conectar dominio definitivo
- [ ] Reemplazar placeholder de TidyCal si cambia el link de agendamiento
- [ ] Agregar Google Analytics / tag de conversión
- [ ] Producir y agregar casos de éxito con datos concretos (Limatambo, Mácula, IPOR, Salaverry)
- [ ] Crear páginas secundarias: blog, casos de éxito individuales, comparación vs. competidores genéricos
- [ ] Integrar formulario de contacto directo como alternativa al calendario
- [ ] Optimizar imágenes de logo para producción (servir desde CDN en lugar de base64)

## Marca

**Aitana** es una marca de Innovation & Healthcare Technologies S.A.C.

Meta Tech Provider certificado.
