---
title: "Serie, número y UUID: cómo identificar cada factura FEL"
description: "Entendé qué son la serie, número y UUID de una factura electrónica FEL en Guatemala. Para qué sirve cada uno y cómo verificarlos."
pubDate: 2026-04-30
slug: "serie-numero-uuid-factura-fel"
draft: false
---

# Serie, número y UUID: cómo identificar cada factura FEL

Cada factura electrónica en Guatemala tiene tres identificadores principales: **serie, número y UUID**. Si alguna vez viste estos datos en tu factura y no supiste qué significaban, esta guía es para vos.

## Los tres identificadores de una factura FEL

Cuando emitís o recibís una factura electrónica, siempre vas a ver estos tres datos:

### Serie

La **serie** es un código alfanumérico que identifica el "bloque" o "lote" de facturas. Cada contribuyente puede tener una o varias series asignadas.

**Ejemplo:** A, B, FACT-001, etc.

La serie se asigna al configurar tu sistema de facturación y generalmente no cambia a menos que solicitás una nueva.

### Número

El **número** es un correlativo secuencial dentro de cada serie. Empieza en 1 y va subiendo: 1, 2, 3, 4...

**Ejemplo:** Si tu serie es "A", tus facturas serían A-1, A-2, A-3, etc.

El número nunca se repite dentro de la misma serie. Si la factura A-15 ya fue emitida, la siguiente será A-16. No se pueden saltar números ni repetir.

### UUID

El **UUID (Universally Unique Identifier)** es un código único universal asignado por la SAT al momento de certificar la factura. Es el identificador más importante de todos.

**Ejemplo:** `8A7B9C3D-1234-5678-ABCD-EF1234567890`

El UUID es:

- **Único a nivel mundial** — no hay dos facturas con el mismo UUID
- **Asignado por la SAT** — no lo elegís vos
- **Inmutable** — una vez asignado, no cambia
- **El identificador oficial** de la factura ante la SAT

## Para qué sirve cada uno

| Identificador | ¿Quién lo asigna? | ¿Para qué sirve? |
|---------------|-------------------|-------------------|
| Serie | El certificador/contribuyente | Organizar facturas por grupos |
| Número | Correlativo automático | Llevar secuencia consecutiva |
| UUID | La SAT | Identificar la factura de forma única |

### En la práctica

- Cuando hablás de "factura número 123", te referís al número correlativo
- Cuando la SAT verifica una factura, usa el UUID
- Cuando tu sistema organiza facturas, usa la serie + número

## Dónde encontrás estos datos

### En el PDF de la factura

Todo PDF de factura electrónica muestra los tres identificadores, generalmente en la parte superior:

- Serie y número: "Serie A, Número 123" o "A-123"
- UUID: puede aparecer como "UUID", "Número de autorización" o en un código QR

### En el XML

El archivo XML (que es la factura "real") contiene los tres datos en campos técnicos específicos. Pero a menos que seas técnico, probablemente nunca vas a necesitar leer el XML directamente.

### En FEL Simple

Cuando emitís una factura con FEL Simple, el bot te muestra los tres datos en el mensaje de confirmación:

> ✅ **Factura emitida**
> Serie: A | Número: 123
> UUID: 8A7B9C3D-1234-5678-ABCD-EF1234567890
> Autorización SAT: confirmada

## Cómo verificar una factura con el UUID

Si querés verificar que una factura es legítima:

1. Ingresá a la **Agencia Virtual SAT**
2. Buscá la opción de **verificación de facturas FEL**
3. Ingresá el UUID de la factura
4. El sistema te muestra los datos: emisor, receptor, monto, fecha

Esto es útil para:

- Verificar facturas que te dieron como comprobante
- Confirmar que tu factura fue certificada correctamente
- Resolver disputas sobre facturación

## Número de autorización

Además de la serie, número y UUID, algunas veces vas a ver un **número de autorización**. Este es un dato adicional que la SAT asigna como confirmación de que la factura fue certificada exitosamente.

En el sistema FEL moderno, el UUID prácticamente reemplaza al número de autorización como identificador principal. Pero algunos formatos de PDF todavía muestran ambos.

## Qué pasa si se salta un número

Si por alguna razón hay un "salto" en la numeración (por ejemplo, pasás de la factura 15 a la 17, sin la 16), puede deberse a:

- Una factura que fue rechazada por la SAT (por datos incorrectos)
- Un error técnico en el sistema
- Una factura que se intentó emitir pero no se completó

Los saltos en la numeración pueden llamar la atención de la SAT durante una auditoría. Si notás un salto, documentá la razón.

## Código QR de verificación

Muchas facturas electrónicas incluyen un **código QR** en el PDF. Este código generalmente contiene el UUID y permite verificar la factura escaneándolo con un celular.

Es una forma rápida de verificar la autenticidad de una factura sin tener que ingresar manualmente el UUID en el portal de la SAT.

## Series múltiples

Un contribuyente puede tener **varias series** activas. Esto es útil para:

- **Sucursales** — una serie por local
- **Puntos de venta** — una serie por caja registradora
- **Tipos de operación** — una serie para ventas, otra para servicios
- **Equipos** — cada vendedor con su propia serie

Con FEL Simple, generalmente usás una sola serie, a menos que necesités organizar tus facturas por categorías.

## Preguntas frecuentes

### ¿Puedo elegir mi número de serie?

Depende del certificador y la herramienta. Algunos permiten personalizar la serie, otros la asignan automáticamente. Con FEL Simple, se configura durante el setup inicial.

### ¿El UUID se puede memorizar?

No es práctico — es un código largo y complejo. Lo mejor es buscarlo en tu historial de facturas o en el PDF. FEL Simple te permite buscar facturas por cliente, fecha o número.

### ¿Qué hago si necesito el UUID y no lo tengo?

Podés consultar en la Agencia Virtual SAT las facturas emitidas a tu nombre (como emisor o receptor). También en FEL Simple podés buscar en tu historial.

### ¿El número de factura se reinicia cada año?

Depende de cómo esté configurada tu serie. Algunos sistemas reinician la numeración cada año, otros son continuos. Ambos son válidos.

### ¿Puedo tener la misma serie para facturas y notas de crédito?

Generalmente, cada tipo de documento (FACT, NCRE, NDEB, etc.) tiene su propia serie. Esto facilita la organización y el control.

### ¿Qué hago si mi factura no tiene UUID?

Si recibís una factura sin UUID, probablemente no fue certificada por la SAT y podría no ser válida. Pedile al emisor que verifique y te proporcione una factura certificada.

## Facturación clara y organizada

Con FEL Simple, cada factura que emitís viene con su serie, número y UUID claramente identificados. Todo queda registrado para que lo consultés cuando lo necesités.

**Empezá a facturar:** [https://wa.me/50231151818](https://wa.me/50231151818)
