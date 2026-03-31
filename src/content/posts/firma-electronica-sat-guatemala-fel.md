---
title: "Cómo activar tu firma electrónica SAT Guatemala para facturar FEL"
description: "Paso a paso para generar tu firma electrónica en la Agencia Virtual SAT de Guatemala. Necesaria para facturar FEL con cualquier certificador."
pubDate: 2026-03-31
slug: "firma-electronica-sat-guatemala-fel"
draft: false
---

Antes de poder emitir tu primera factura FEL en Guatemala, hay un paso que no podés saltarte: **generar tu firma electrónica** en el portal de la SAT y acreditar al certificador que va a procesar tus facturas.

Muchos se traban aquí porque las instrucciones del portal de la SAT no son las más claras. Esta guía te lleva paso a paso por todo el proceso — desde cero hasta tener el archivo .pfx listo para usar.

---

## ¿Qué es la firma electrónica SAT y para qué sirve?

La **firma electrónica** (o firma digital) es tu identidad ante el sistema FEL de la SAT. Es lo que garantiza que las facturas que emitís vienen realmente de tu NIT y no de otra persona.

Técnicamente, es un archivo con extensión **.pfx** que la SAT genera para vos en la Agencia Virtual. Ese archivo contiene un certificado digital vinculado a tu NIT. Cuando tu certificador (la empresa que transmite tu factura a la SAT) recibe una factura tuya, usa ese archivo para verificar que la instrucción realmente vino de vos.

**Sin firma electrónica, ningún certificador puede emitir facturas a tu nombre.** Es un requisito obligatorio de la SAT para cualquier emisor FEL en Guatemala.

La buena noticia: es gratis, la genera la misma SAT, y el proceso toma unos 30 minutos.

---

## Paso 1 — Acreditar al certificador en tu Agencia Virtual

Antes de generar la firma, necesitás decirle a la SAT qué empresa va a ser tu certificador de facturas. Este proceso se llama **acreditación de certificadores**.

1. Entrá a **[portal.sat.gob.gt](https://portal.sat.gob.gt)** con tu NIT y la contraseña de tu Agencia Virtual.

2. En el menú de servicios, buscá **"Factura Electrónica en Línea (FEL)"**.

3. Dentro de FEL, seleccioná **"Acreditación de Certificadores"**.

4. Aparece una lista de certificadores autorizados por la SAT. Buscás el que querés usar. Si vas a usar FEL Simple, el certificador es **CARI LATINOAMERICA (NIT 96941243)**.

5. Cambiás el estado a **"ACREDITADO"** y guardás.

Con esto le estás diciendo a la SAT: "esta empresa está autorizada para emitir facturas en mi nombre". Solo podés tener un certificador acreditado a la vez.

---

## Paso 2 — Generar tu firma electrónica

Con el certificador acreditado, ahora podés generar el archivo .pfx:

1. Seguís dentro de la sección **"Factura Electrónica en Línea (FEL)"** en la Agencia Virtual.

2. Seleccionás **"Generar Firma Electrónica"** (o "Generar/Actualizar Firma").

3. El sistema te pregunta para qué tipo de emisión querés la firma. Elegís **"Otros Certificadores de DTE (Terceros)"** — esa es la opción para certificadores que no son el sistema propio de la SAT.

4. Te pide que crees una **contraseña para proteger el archivo .pfx**. Esta contraseña debe cumplir:
   - Mínimo 7 caracteres
   - Al menos una letra mayúscula
   - Al menos un número
   - Al menos un carácter especial (como !, @, #, $)

   Ejemplos de contraseñas válidas: `FEL@2026`, `Factura#1`, `MiNIT!123`

   **Guardá esta contraseña en un lugar seguro.** La vas a necesitar cada vez que alguien (o un sistema) use tu firma electrónica. Si la perdés, vas a tener que regenerar el archivo.

5. Hacés clic en **"Generar y descargar firma"**. El sistema descarga automáticamente un archivo **.pfx** con tu NIT como nombre (por ejemplo: `12345678.pfx`).

---

## ¿Qué hago con el archivo .pfx?

El archivo .pfx es tu firma digital. Guardalo bien — es como el sello físico de tu negocio, pero en versión digital.

**¿Dónde guardarlo?**
- En tu celular (en una carpeta que no se borre fácilmente)
- En Google Drive o Dropbox con acceso personal
- En tu computadora + una copia en la nube
- En un USB de respaldo si trabajás mucho desde escritorio

**¿Cuándo lo necesitás?**
- Al configurar tu cuenta en FEL Simple: el bot te pide que le enviés el archivo .pfx por WhatsApp para activar tu cuenta.
- Si alguna vez cambiás de certificador y necesitás reconfigurar.
- Si la firma vence (tiene una vigencia de 2 años) y necesitás renovarla.

**¿Es seguro enviar el .pfx por WhatsApp?**
Sí, siempre y cuando sea al número oficial de FEL Simple (+502 3115 1818) y la contraseña la ponés en un mensaje separado o la ingresás en el proceso de configuración. El archivo solo es útil si alguien tiene también la contraseña.

---

## ¿Qué pasa si perdés la contraseña o el archivo .pfx?

### Si perdiste solo la contraseña

No hay forma de recuperar la contraseña de un archivo .pfx existente. Tenés que **generar una nueva firma** desde la Agencia Virtual, lo que crea un nuevo archivo .pfx con una nueva contraseña. El archivo anterior queda inválido automáticamente.

### Si perdiste el archivo .pfx

Igual: generás una nueva firma desde la Agencia Virtual. El proceso es el mismo que la primera vez. La firma anterior queda inactiva.

### Si la firma venció (2 años)

La firma tiene una **vigencia de 2 años**. Cuando vence, necesitás regenerarla usando el mismo proceso. Algunos sistemas te notifican antes de que venza; si usás FEL Simple, el bot te avisará cuando se acerque la fecha de vencimiento.

### Si olvidaste tu contraseña de la Agencia Virtual SAT

Este es el problema más común. La contraseña del .pfx y la contraseña de la Agencia Virtual SAT son dos cosas distintas:
- La **contraseña de la Agencia Virtual** es la que usás para entrar a portal.sat.gob.gt. Si la olvidaste, podés restablecerla desde el portal con tu NIT y correo registrado.
- La **contraseña del .pfx** es la que protege el archivo de firma. Solo vos la sabés — la SAT no la guarda.

---

## Preguntas frecuentes sobre la firma electrónica

**¿Puedo tener más de un certificador acreditado al mismo tiempo?**

No. El sistema de la SAT solo permite un certificador activo a la vez. Si querés cambiar de certificador, tenés que desacreditar al anterior y acreditar al nuevo. En FEL Simple, si ya tenés una firma generada con otro certificador, necesitás regenerar la firma con CARI LATINOAMERICA acreditado.

**¿La firma electrónica tiene costo?**

No. Generarla en la Agencia Virtual de la SAT es completamente gratuito. No hay que pagar nada por el archivo .pfx.

**¿Necesito una firma por cada negocio o establecimiento?**

La firma está vinculada a tu NIT, no a tu establecimiento. Si tenés un solo NIT con múltiples establecimientos, usás la misma firma para todos. Si tenés NITs separados (por ejemplo, uno personal y uno de una empresa), cada NIT tiene su propia firma.

**¿Qué pasa si alguien más tiene mi archivo .pfx y mi contraseña?**

Técnicamente podría emitir facturas en tu nombre. Por eso es importante: no compartir el .pfx ni la contraseña con personas que no sean de confianza. Si sospechas que tu firma fue comprometida, regenerala inmediatamente desde la Agencia Virtual.

**¿El proceso es igual para cualquier certificador FEL en Guatemala?**

El proceso de generación de la firma en la SAT es el mismo. Lo que cambia es qué certificador acreditás en el Paso 1. Si usás Digifact directamente, InFile, Megaprint u otro, el certificador que acreditás cambia. Para FEL Simple, siempre es CARI LATINOAMERICA (NIT 96941243).

---

Con la firma electrónica lista y el certificador acreditado, ya tenés todo para empezar a facturar. Solo queda configurar tu cuenta en la herramienta de emisión que elijas.

Si querés empezar con **FEL Simple**, el proceso es sencillo: escribile al bot en [WhatsApp](https://wa.me/50231151818), el bot te guía paso a paso para enviar tu .pfx y dejarte listo para emitir facturas en minutos. Las primeras 5 facturas son gratis.
