---
title: "Seguridad de tus datos en la facturación electrónica"
description: "Cómo se protegen tus datos fiscales en la facturación electrónica FEL en Guatemala. Seguridad y privacidad con FEL Simple."
pubDate: 2026-07-21
slug: "seguridad-datos-facturacion-electronica"
draft: false
---

# Seguridad de tus datos en la facturación electrónica

Cuando empezás a facturar electrónicamente, es normal preguntarse: "¿Mis datos están seguros?" Estamos hablando de información sensible — tu NIT, tus ingresos, los datos de tus clientes, tu firma electrónica. Es una preocupación legítima y es bueno que te la hagás.

En este artículo te voy a explicar cómo funciona la seguridad en la facturación electrónica FEL en Guatemala, qué medidas toma FEL Simple para proteger tu información, y qué podés hacer vos para mantener tus datos seguros.

## Qué datos maneja la facturación electrónica

Cuando facturás electrónicamente, se manejan varios tipos de información sensible:

**Datos del emisor (vos)**:
- NIT y nombre registrado en la SAT
- Dirección fiscal
- Régimen tributario
- Firma electrónica (.pfx)
- Historial de facturas emitidas

**Datos de tus clientes**:
- NIT y nombre
- Historial de facturas recibidas
- Montos facturados

**Datos financieros**:
- Total de ingresos mensuales y anuales
- Impuestos calculados
- Registro de gastos

Toda esta información necesita estar protegida. Y lo está.

## Cómo funciona la seguridad en el sistema FEL

El sistema de Factura Electrónica en Línea (FEL) de Guatemala tiene varias capas de seguridad:

### Certificación por la SAT

Cada factura electrónica es certificada por un certificador autorizado por la SAT. Este proceso garantiza que:
- La factura fue emitida por un contribuyente real y verificado.
- Los datos no pueden ser alterados después de la certificación.
- Cada factura tiene un número de autorización único que permite verificarla.
- La SAT tiene un registro independiente de cada factura emitida.

### Firma electrónica (.pfx)

Tu firma electrónica es como tu "sello digital". Es un archivo criptográfico que:
- Te identifica de forma única ante la SAT.
- Está protegido por una contraseña que solo vos conocés.
- Garantiza que nadie puede emitir facturas a tu nombre sin tu autorización.
- Tiene fecha de vencimiento y debe renovarse periódicamente.

### Protocolo de comunicación

Las comunicaciones entre tu dispositivo, FEL Simple y el certificador de la SAT viajan encriptadas:
- WhatsApp usa encriptación de extremo a extremo.
- Las conexiones con el certificador usan protocolos HTTPS/TLS.
- Los datos en tránsito no pueden ser interceptados ni leídos por terceros.

## Cómo protege FEL Simple tu información

FEL Simple implementa múltiples medidas de seguridad:

### Encriptación de datos

Toda la información almacenada en nuestros servidores está encriptada. Esto significa que incluso si alguien accediera a la base de datos, no podría leer tu información sin las claves de encriptación.

Tu firma electrónica (.pfx) recibe un nivel adicional de protección: se almacena con encriptación especializada y nunca se comparte ni se expone.

### Almacenamiento seguro

Los datos se almacenan en servidores con:
- Acceso restringido por múltiples capas de autenticación.
- Respaldos automáticos para prevenir pérdida de datos.
- Monitoreo continuo de seguridad.
- Infraestructura de bases de datos con estándares de seguridad modernos.

### Acceso limitado

- Solo vos tenés acceso a tu información fiscal.
- Cada cuenta está vinculada a un número de WhatsApp único.
- No compartimos tu información con terceros.
- Nuestro equipo técnico tiene acceso limitado y auditado a los datos.

### Sin almacenamiento de contraseñas

FEL Simple no almacena la contraseña de tu firma electrónica en texto plano. Se usa un sistema de encriptación que protege esta información sensible.

## Buenas prácticas de seguridad para vos

Más allá de lo que FEL Simple hace por protegerte, hay cosas que vos podés hacer:

### Protegé tu firma electrónica

- **No compartás tu archivo .pfx** con nadie que no sea de confianza.
- **Usá una contraseña fuerte** para tu firma electrónica.
- **No enviés tu .pfx por canales inseguros** (email sin encriptar, grupos de WhatsApp públicos).
- **Renová tu firma** antes de que venza.

### Protegé tu cuenta de WhatsApp

- **Activá la verificación en dos pasos** en WhatsApp.
- **No prestés tu celular** cuando tengás sesión activa con FEL Simple.
- **Si perdés tu celular**, contactanos inmediatamente para proteger tu cuenta.

### Protegé tu NIT

- **No publiqués tu NIT innecesariamente** en redes sociales.
- **Verificá quién te pide NIT** y para qué lo necesita.
- **Revisá periódicamente** tus facturas emitidas en la SAT para detectar actividad sospechosa.

## Qué pasa si alguien accede a tu cuenta

En el caso improbable de que alguien acceda a tu WhatsApp y use FEL Simple:

1. **Contactanos inmediatamente** para bloquear tu cuenta de facturación.
2. **Cambiá la contraseña** de tu WhatsApp (verificación en dos pasos).
3. **Revisá las facturas emitidas** para detectar cualquier factura no autorizada.
4. **Si hay facturas fraudulentas**, te ayudamos a generar las notas de crédito correspondientes.

## La diferencia entre seguridad en papel y electrónica

Mucha gente piensa que la factura en papel era "más segura". La realidad es lo contrario:

| Aspecto | Factura en papel | Factura electrónica |
|---------|-----------------|-------------------|
| Falsificación | Fácil de falsificar | Imposible (certificación SAT) |
| Pérdida | Si se pierde, se perdió | Siempre hay copia digital |
| Verificación | Difícil de verificar | Verificable en portal SAT |
| Alteración | Se puede borrar o modificar | No se puede alterar post-emisión |
| Respaldo | Sin respaldo automático | Respaldada en SAT y tu sistema |
| Acceso no autorizado | Cualquiera puede copiar | Protegida por firma electrónica |

La factura electrónica es significativamente más segura que la factura en papel.

## Cumplimiento normativo

FEL Simple cumple con:

- **Regulaciones de la SAT** para certificadores y emisores de facturas electrónicas.
- **Ley de Acceso a la Información Pública** en cuanto a protección de datos personales.
- **Estándares de la industria** en encriptación y almacenamiento seguro de datos.

## Planes de FEL Simple

Todos los planes incluyen las mismas medidas de seguridad:

| Plan | Precio | Facturas/mes | Seguridad |
|------|--------|-------------|-----------|
| Gratis | Q0 | 5 | Completa |
| Emprendedor | Q49 | 30 | Completa |
| Profesional | Q149 | 100 | Completa |
| Negocio | Q299 | Ilimitadas | Completa |

La seguridad no es un feature premium. Todos los usuarios reciben la misma protección.

## Preguntas frecuentes

### ¿FEL Simple puede ver mis facturas?

Nuestro sistema procesa tus facturas para generarlas y certificarlas, pero tu información es confidencial. No la compartimos con terceros ni la usamos para otros fines.

### ¿Qué pasa con mis datos si dejo de usar FEL Simple?

Tus facturas emitidas permanecen registradas en la SAT independientemente de si usás FEL Simple o no. Si dejás de usar el servicio, podés solicitar la eliminación de tus datos de nuestros servidores.

### ¿Es seguro enviar mi firma electrónica por WhatsApp?

WhatsApp tiene encriptación de extremo a extremo, lo que significa que el archivo viaja encriptado. Sin embargo, recomendamos enviar la firma electrónica solo cuando sea necesario (durante la configuración inicial) y no compartirla en grupos.

### ¿Alguien puede facturar a mi nombre sin mi permiso?

No sin tu firma electrónica y la contraseña de la misma. La firma electrónica es tu llave única para emitir facturas. Sin ella, nadie puede emitir facturas a tu nombre.

### ¿Los datos de mis clientes están seguros?

Sí. Los datos de tus clientes (NIT, nombre) se almacenan de forma encriptada y solo vos tenés acceso a ellos. No compartimos la información de tus clientes con nadie.

---

## Tu información fiscal en buenas manos

La seguridad de tus datos es nuestra prioridad. Facturá con la tranquilidad de saber que tu información está protegida.

**Escribinos por WhatsApp y empezá con confianza:**

👉 [https://wa.me/50231151818](https://wa.me/50231151818)

Empezá gratis. Seguro. Sin contratos. Tus datos, protegidos.
