---
title: "Tipos de documentos FEL: FACT, NCRE, NDEB, FEXP y FESP explicados"
description: "Conocé los 5 tipos de documentos FEL en Guatemala: factura, nota de crédito, nota de débito, exportación y especial. Cuándo usar cada uno."
pubDate: 2026-04-24
slug: "tipos-documento-fel-guatemala"
draft: false
---

# Tipos de documentos FEL: FACT, NCRE, NDEB, FEXP y FESP explicados

En el sistema de Facturación Electrónica en Línea (FEL) de Guatemala no existe solo un tipo de documento. Hay **5 tipos principales**, cada uno para una situación diferente. Saber cuál usar y cuándo es fundamental para facturar correctamente.

Te los explicamos todos de forma clara.

## Los 5 tipos de documentos FEL

| Código | Nombre | ¿Para qué? |
|--------|--------|-------------|
| FACT | Factura | Documentar una venta o servicio |
| NCRE | Nota de Crédito | Anular o ajustar una factura emitida |
| NDEB | Nota de Débito | Cargos adicionales sobre una factura |
| FEXP | Factura de Exportación | Ventas a clientes fuera de Guatemala |
| FESP | Factura Especial | Compras a proveedores sin factura |

Vamos a ver cada uno en detalle.

## FACT — Factura

La **factura (FACT)** es el documento más común. Lo usás cada vez que vendés un producto o prestás un servicio.

### Cuándo emitir una FACT

- Vendiste un producto a un cliente
- Prestaste un servicio profesional
- Cobraste una consultoría, diseño, reparación, etc.
- Cualquier transacción comercial dentro de Guatemala

### Datos que lleva una factura

- **Emisor:** tu NIT, nombre y datos fiscales
- **Receptor:** NIT del cliente (o CF si es consumidor final), nombre
- **Detalle:** descripción del producto o servicio
- **Monto:** valor total, impuestos incluidos
- **Fecha y hora:** cuándo se emitió
- **Serie, número y UUID:** identificadores únicos asignados por la SAT

### Factura a consumidor final (CF)

Si tu cliente no te da su NIT, emitís la factura a **Consumidor Final (CF)**. Es perfectamente legal. La diferencia es que el cliente no puede usar esa factura para deducir gastos.

Con FEL Simple, emitir una factura es tan simple como escribir en WhatsApp:

> "Facturar Q500 a Juan Pérez NIT 1234567 por servicio de consultoría"

Y listo. En segundos tenés tu factura certificada.

## NCRE — Nota de Crédito

La **nota de crédito (NCRE)** es el documento que usás para anular, total o parcialmente, una factura ya emitida.

### Cuándo emitir una NCRE

- **Te equivocaste en una factura** — monto incorrecto, datos del cliente mal, etc.
- **El cliente devolvió el producto** — necesitás reversar la venta
- **Diste un descuento posterior** — rebaja después de facturar
- **Anulación de la transacción** — la venta no se concretó

### Cómo funciona

La nota de crédito **hace referencia a la factura original**. No podés emitir una nota de crédito "suelta" — siempre va ligada a una factura existente.

Ejemplo: emitiste una factura por Q1,000 pero el monto correcto era Q800. Emitís una nota de crédito por Q200 referenciando la factura original. Ahora el efecto neto es Q800.

### ¿Puedo anular una factura completamente?

Sí. Emitís una nota de crédito por el monto total de la factura original. Esto la anula efectivamente.

**Importante:** No podés "borrar" una factura ya emitida. La forma legal de corregirla es siempre a través de una nota de crédito.

Con FEL Simple, anular una factura es tan simple como decirle al bot:

> "Anular factura" 

Y te guía por el proceso.

## NDEB — Nota de Débito

La **nota de débito (NDEB)** es lo opuesto a la nota de crédito. Se usa para agregar cargos a una factura ya emitida.

### Cuándo emitir una NDEB

- **Intereses por pago tardío** — el cliente pagó fuera de plazo
- **Cargos adicionales** — gastos que no estaban en la factura original
- **Ajuste de precio al alza** — el precio subió después de facturar
- **Diferencias de tipo de cambio** — en transacciones en moneda extranjera

### Cómo funciona

Similar a la nota de crédito, la nota de débito **hace referencia a una factura original**. Agrega un monto adicional a la transacción documentada.

Ejemplo: facturaste Q1,000 pero olvidaste incluir el envío de Q100. Emitís una nota de débito por Q100 referenciando la factura original.

### ¿Es común usar notas de débito?

Honestamente, no tanto como las facturas o notas de crédito. Muchos negocios pequeños nunca necesitan emitir una. Pero es bueno saber que existe por si la necesitás.

## FEXP — Factura de Exportación

La **factura de exportación (FEXP)** se usa cuando vendés productos o servicios a clientes **fuera de Guatemala**.

### Cuándo emitir una FEXP

- Exportás productos físicos a otro país
- Prestás servicios a una empresa extranjera
- Vendés software, diseño u otros servicios digitales al exterior
- Cualquier transacción donde el receptor está fuera de Guatemala

### Diferencias con una factura normal

- **No lleva IVA** — las exportaciones están exentas de IVA en Guatemala
- **El receptor puede ser extranjero** — no necesita NIT guatemalteco
- **Puede estar en otra moneda** — dólares, euros, etc.
- **Requiere información adicional** — datos del importador, país de destino

### ¿Los freelancers que trabajan para empresas de EE.UU. necesitan FEXP?

Sí. Si prestás servicios a una empresa en Estados Unidos (o cualquier otro país), deberías emitir una factura de exportación. Es la forma correcta de documentar esa transacción ante la SAT.

## FESP — Factura Especial

La **factura especial (FESP)** es quizás la menos conocida pero muy útil en ciertos casos. La emitís **vos como comprador** cuando tu proveedor no puede o no quiere emitir factura.

### Cuándo emitir una FESP

- Comprás productos a un vendedor informal que no factura
- Pagás un servicio a alguien que no está inscrito como contribuyente
- Adquirís productos agrícolas directamente de un productor
- Cualquier compra donde tu proveedor no te da factura

### Cómo funciona

A diferencia de los otros documentos donde vos sos el emisor de una venta, en la factura especial **vos sos el comprador que documenta una compra**. La emitís vos, no tu proveedor.

Esto tiene implicaciones fiscales: al emitir una factura especial, **vos retenés el impuesto** que tu proveedor debería pagar. Esencialmente, estás haciendo de "agente retenedor".

### Consideraciones importantes

- La factura especial tiene **límites de monto** según la legislación
- Debés **retener y pagar** los impuestos correspondientes
- No podés usar factura especial para compras a contribuyentes que sí pueden facturar
- Es recomendable consultar con un contador si tenés dudas sobre cuándo usarla

## ¿Cuál documento necesito?

Aquí tenés una guía rápida:

| Situación | Documento |
|-----------|-----------|
| Vendiste algo a un cliente en Guatemala | FACT |
| Te equivocaste en una factura | NCRE |
| El cliente devolvió el producto | NCRE |
| Necesitás cobrar algo extra | NDEB |
| Vendiste a un cliente fuera de Guatemala | FEXP |
| Compraste a alguien que no factura | FESP |

## Todos los documentos FEL son electrónicos

Un punto importante: **los 5 tipos de documentos son electrónicos**. Se certifican a través de tu certificador FEL, se registran en la SAT en tiempo real, y tienen la misma validez legal que si fueran en papel (que ya no existe).

Cada uno tiene su propio UUID, serie y número de autorización. Y todos son consultables en la Agencia Virtual SAT.

## Preguntas frecuentes

### ¿Puedo emitir todos los tipos de documento con FEL Simple?

Sí. FEL Simple soporta los 5 tipos: FACT, NCRE, NDEB, FEXP y FESP, todos desde WhatsApp.

### ¿La nota de crédito tiene costo adicional?

Con FEL Simple, no. Las notas de crédito están incluidas en tu plan, igual que las facturas.

### ¿Puedo emitir una nota de crédito meses después?

Sí, pero hay plazos razonables. La SAT puede cuestionar notas de crédito emitidas mucho tiempo después de la factura original. Lo recomendable es emitirla lo antes posible.

### ¿Cuántas facturas de exportación puedo emitir?

No hay límite en la cantidad. Si tu negocio vende al exterior, podés emitir tantas FEXP como necesités.

### ¿Necesito permiso especial para emitir facturas especiales?

No un permiso especial, pero sí debés cumplir con las obligaciones de retención de impuestos. Consultá con tu contador para los detalles de tu caso.

### ¿Qué pasa si uso el tipo de documento equivocado?

Si ya emitiste el documento, podés anularlo con una nota de crédito y emitir el correcto. Es importante usar el tipo adecuado para evitar problemas con la SAT.

## Empezá a facturar con todos los tipos de documento

Con FEL Simple tenés acceso a todos los tipos de documentos FEL desde WhatsApp. No importa si necesitás una factura simple o una nota de crédito — todo lo hacés desde tu celular.

**Probalo ahora:** [https://wa.me/50231151818](https://wa.me/50231151818)
