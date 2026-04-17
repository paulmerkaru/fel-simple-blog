---
title: "El XML de tu factura electrónica: qué contiene y por qué importa"
description: "Descubrí qué es el XML de tu factura electrónica FEL en Guatemala, qué información contiene y por qué es el documento legal real."
pubDate: 2026-05-01
slug: "xml-factura-electronica-guatemala"
draft: false
---

# El XML de tu factura electrónica: qué contiene y por qué importa

Cuando emitís una factura electrónica, recibes un PDF bonito que le podés enviar a tu cliente. Pero, ¿sabías que ese PDF **no es la factura**? La factura real es un archivo XML que probablemente nunca has visto. Te explicamos qué es y por qué importa.

## Qué es el XML de una factura

**XML (eXtensible Markup Language)** es un formato de archivo que organiza información de forma estructurada. Es como una tabla de datos, pero en un formato que las computadoras pueden leer perfectamente.

Tu factura electrónica es, en esencia, un archivo XML que contiene toda la información de la transacción en un formato estandarizado que la SAT puede procesar.

### ¿Y el PDF?

El PDF que vos y tu cliente ven es simplemente una **representación visual** del XML. Es más bonito, más fácil de leer para humanos, pero no es el documento fiscal oficial.

Pensalo así:

- **XML** = la factura legal, el documento oficial
- **PDF** = la foto bonita de la factura, para que la gente la lea fácilmente
- **Papel impreso** = una copia del PDF en papel, opcional

## Qué contiene el XML de tu factura

El archivo XML de una factura FEL guatemalteca contiene múltiples secciones con datos estructurados:

### Datos del emisor (vos)

- NIT del emisor
- Nombre o razón social
- Dirección fiscal
- Régimen fiscal (pequeño contribuyente, general, etc.)
- Información del establecimiento

### Datos del receptor (tu cliente)

- NIT del receptor (o CF)
- Nombre del receptor
- Dirección (si se incluye)

### Detalle de la transacción

- Descripción del producto o servicio
- Cantidad
- Precio unitario
- Monto total por línea
- Descuentos (si los hay)

### Totales

- Subtotal
- Impuestos (IVA u otros)
- Total de la factura
- Moneda

### Datos de certificación

- UUID asignado por la SAT
- Fecha y hora de emisión
- Serie y número
- Número de autorización
- Firma electrónica del emisor
- Firma del certificador

### Información adicional

- Frases fiscales requeridas (ej: "pequeño contribuyente - paga directo")
- Tipo de documento (FACT, NCRE, etc.)
- Información complementaria según el tipo de documento

## Por qué importa el XML

### 1. Es el documento legal

Ante la SAT y ante la ley, el XML es el documento oficial. Si hay una discrepancia entre lo que dice el PDF y lo que dice el XML, prevalece el XML.

### 2. Es lo que la SAT procesa

Cuando tu certificador envía tu factura a la SAT, lo que envía es el XML. La SAT lo procesa, lo valida, lo almacena y lo usa para cruzar información fiscal.

### 3. Es verificable

Cualquier persona puede tomar el UUID de tu factura, consultarlo en la SAT, y verificar que los datos del XML son correctos. Esto previene falsificación.

### 4. Es permanente

El XML queda almacenado en los servidores de la SAT indefinidamente. Aunque vos pierdas el archivo, la SAT lo tiene.

## ¿Necesitás ver o guardar el XML?

### Para la mayoría de emprendedores: no

Honestamente, la mayoría de pequeños contribuyentes nunca necesitan interactuar directamente con el XML. Tu herramienta de facturación (como FEL Simple) se encarga de generar, enviar y almacenar el XML automáticamente.

Vos solo necesitás:

- El **PDF** para enviar a tu cliente
- El **UUID** para verificar o consultar la factura
- El **historial** en tu herramienta para tus registros

### Para contadores y auditores: sí

Si tu contador necesita los XML para algún proceso contable o si la SAT te los pide en una auditoría, podés obtenerlos de:

- Tu certificador (Digifact, en el caso de FEL Simple)
- La Agencia Virtual SAT (consultando por UUID)
- Tu herramienta de facturación

### Para desarrolladores e integraciones: definitivamente

Si estás integrando un sistema de facturación con otro software (ERP, CRM, sistema de inventario), los XML son la fuente de datos oficial.

## Validez del XML vs el PDF

Un escenario que puede pasar:

1. Emitís una factura (se genera el XML y el PDF)
2. Alguien modifica el PDF (cambia el monto, el nombre, etc.)
3. El PDF modificado no coincide con el XML original

En este caso, **el XML prevalece**. El PDF modificado no tiene ninguna validez legal. Esto es precisamente una de las ventajas de la facturación electrónica — la información certificada es inalterable.

## El XML y las firmas digitales

Cada XML de factura incluye dos firmas digitales:

### Tu firma electrónica (.pfx)

Garantiza que vos emitiste la factura. Es tu sello de autenticidad.

### La firma del certificador

Garantiza que el certificador validó y procesó la factura. Agrega una capa adicional de seguridad.

Estas firmas están embebidas en el XML y son verificables criptográficamente. Cualquier modificación al XML después de firmado invalidaría las firmas.

## Formato del XML guatemalteco

El formato del XML para facturas FEL en Guatemala sigue un estándar definido por la SAT. Incluye:

- **Versión del documento** — actualmente "1.00" para NUC
- **Namespace** — identificadores técnicos del formato
- **Estructura jerárquica** — datos organizados en secciones lógicas
- **Encoding UTF-8** — para soportar caracteres especiales (tildes, eñes)

Este formato es el mismo para todos los certificadores. No importa si usás Digifact, Infile o cualquier otro — el XML final tiene la misma estructura que la SAT espera.

## Preguntas frecuentes

### ¿Puedo abrir el XML en mi computadora?

Sí. El XML se puede abrir con cualquier editor de texto (Notepad, TextEdit) o navegador web. Pero no va a verse "bonito" — verás código con etiquetas. Es información para computadoras, no para humanos.

### ¿Si pierdo el PDF, puedo regenerarlo del XML?

Sí. Cualquier sistema que procese XML de facturas FEL puede generar un PDF a partir de él. Tu certificador generalmente ofrece esta opción.

### ¿El XML ocupa mucho espacio?

No. Un XML de factura típico pesa entre 5KB y 50KB. Podrías guardar miles de facturas en un USB sin problema.

### ¿Puedo enviar el XML al cliente en lugar del PDF?

Técnicamente sí, pero la mayoría de clientes no van a saber qué hacer con un archivo XML. El PDF es la forma estándar de compartir facturas.

### ¿La SAT puede cambiar el formato del XML?

Sí, la SAT puede actualizar el formato. Cuando lo hace, los certificadores actualizan sus sistemas automáticamente. Vos no tenés que hacer nada — tu herramienta se encarga.

### ¿Qué pasa si el XML tiene un error?

Si el XML fue certificado por la SAT, ya fue validado y aceptado. Si hay un error en los datos (monto incorrecto, NIT equivocado), la forma de corregirlo es emitiendo una nota de crédito.

## No te preocupés por el XML

Con FEL Simple, todo el manejo del XML es transparente. Vos facturás desde WhatsApp, y nosotros nos encargamos de generar el XML, certificarlo con la SAT, y darte el PDF listo para enviar.

**Facturá sin complicaciones técnicas:** [https://wa.me/50231151818](https://wa.me/50231151818)
