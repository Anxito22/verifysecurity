# Privacy Score (versión 100 % gratuita)

Pegas una URL y obtienes una nota A–F sobre su política de privacidad.

## Publicar gratis
1. Cuenta en https://github.com y en https://vercel.com (con GitHub). Sin tarjeta.
2. Clave gratuita de Gemini: https://aistudio.google.com/apikey → "Create API key" (sin tarjeta, no actives facturación).
3. Sube esta carpeta a un repositorio de GitHub → en Vercel: Add New > Project > Import.
4. Antes de Deploy: Environment Variables → `GEMINI_API_KEY` = tu clave. Deploy.

## Opcional
- `GEMINI_MODEL`: cambia el modelo si el por defecto deja de ser gratuito (elige uno marcado "Free of charge" en la página de precios de Gemini).

## Ojo
- Con la capa gratuita de Google, lo que se envía puede usarse para mejorar sus productos (aquí solo texto público de políticas).
- Los límites son bajos: si hay muchas visitas, saldrá el aviso de límite alcanzado.
- NO activar facturación en Google AI Studio si quieres garantía de coste cero.
