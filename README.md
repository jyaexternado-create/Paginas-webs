# Páginas web

## El Memorialista (`generador-documentos/`)

Generador gratuito de documentos jurídicos para Colombia. El usuario llena un formulario y el documento se redacta en vivo:

- **Derecho de petición** (art. 23 C.P., Ley 1755 de 2015), con plazos de 10, 15 o 30 días hábiles y opción para empresas privadas.
- **Acción de tutela** (art. 86 C.P., Decreto 2591 de 1991), con juramento del art. 37 y procedencia.
- **Reclamación de garantía** (Ley 1480 de 2011, arts. 7, 10, 11 y 58).

Funciones: copiar texto, descargar en Word (.doc) e imprimir o guardar como PDF. Los datos se guardan solo en el navegador del usuario.

Es una sola página HTML sin dependencias: basta con abrir `generador-documentos/index.html` o publicarla con GitHub Pages.

> Aviso: es una herramienta de redacción con modelos generales; no reemplaza la asesoría de un abogado.

## San Marcos · Huevos criollos (`huevos-san-marcos/`)

Página de venta para un comercio de huevos criollos en Agustín Codazzi (Cesar). Incluye precios por empaque (6, 12 y 20 huevos), calculadora de pedido que arma el mensaje de WhatsApp para recoger en el local (no hay domicilios), galería, opiniones, ubicación con mapa y preguntas frecuentes.

Para personalizarla:
- **Fotos:** guárdalas en `huevos-san-marcos/imagenes/` con los nombres de `imagenes/LEEME.md`.
- **Dirección, horario, medios de pago y opiniones:** busca los comentarios `✏️` en `index.html` (los espacios pendientes se ven resaltados en amarillo).
- **WhatsApp y mapa:** cambia `CONFIG.whatsapp` y `CONFIG.mapa` al final de `index.html`.
