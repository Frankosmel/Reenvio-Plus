# 📖 Guía de Uso - Reenvío Plus Bot & Web Platform

Bienvenido al manual oficial de usuario de **Reenvío Plus**. Esta guía te explica paso a paso cómo automatizar el reenvío de mensajes, gestionar canales y maximizar el alcance de tus publicaciones en Telegram sin riesgo de sanciones.

---

## 📑 Contenido
1. [Primeros Pasos y Acceso](#1-primeros-pasos-y-acceso)
2. [Gestión de Canales y Listas](#2-gestión-de-canales-y-listas)
3. [Creación de Publicaciones y Reenvíos](#3-creación-de-publicaciones-y-reenvíos)
4. [Modo Espejo (Clonación en Tiempo Real)](#4-modo-espejo-clonación-en-tiempo-real)
5. [Filtros de Contenido y Limpieza de Enlaces](#5-filtros-de-contenido-y-limpieza-de-enlaces)
6. [Protección Anti-Flood y Horarios Silenciosos](#6-protección-anti-flood-y-horarios-silenciosos)

---

## 1. Primeros Pasos y Acceso
Reenvío Plus se integra directamente con Telegram a través de su **Mini App** y su panel web centralizado:
- Puedes iniciar sesión directamente desde Telegram sin contraseñas complicadas: el sistema autentica tu identidad mediante el estándar seguro `initData` de Telegram.
- La primera vez que accedes se te asignará automáticamente un plan **Trial de prueba gratuito** con publicaciones incluidas para que verifiques el funcionamiento.

---

## 2. Gestión de Canales y Listas

Para poder enviar o clonar contenido, debes clasificar tus canales en dos grupos:

### Canales Origen (Source Channels)
- Son los canales o grupos donde se publica el contenido original que deseas redistribuir.
- El sistema puede leer mensajes de canales públicos o privados en los que tengas acceso como miembro o administrador.

### Canales Destino y Listas de Difusión (Target Lists)
- Son los grupos, supergrupos o canales donde se publicarán tus mensajes.
- **Creación de Listas:** Puedes agrupar múltiples destinos en una lista única (ej. *"Grupos de Compra/Venta La Habana"*, *"Canales de Ofertas"*, *"Red de Difusión 1"*).
- Enviar a una lista reenviará el mensaje a todos los destinos configurados secuencialmente respetando los intervalos de seguridad.

---

## 3. Creación de Publicaciones y Reenvíos

Reenvío Plus permite tres modalidades de programación:

1. **Reenvío Inmediato / Único:** Envía una publicación seleccionada a tu lista de destinos con un solo clic.
2. **Intervalo Periódico:** Repite el mensaje cada X minutos u horas (ej. cada 45 minutos o cada 2 horas).
3. **Horarios Fijos y Diarios:** Programa horas exactas del día para tus publicaciones (ej. 09:00 AM, 02:00 PM y 08:30 PM).

---

## 4. Modo Espejo (Clonación en Tiempo Real)
*(Disponible en planes Plus y Pro)*

El **Modo Espejo** replica automáticamente cualquier mensaje nuevo que se publique en un canal origen hacia tus canales destino:
- **Instantáneo:** Cada vez que el canal origen publica una noticia, foto, video o documento, el bot lo replica en milisegundos.
- **Copia Limpia o Reenvío:** Puedes elegir si se envía como *"Reenviado de [Canal]"* o como una *"Copia Limpia"* (mensaje nuevo con el mismo contenido sin la cabecera de reenvío).

---

## 5. Filtros de Contenido y Limpieza de Enlaces

Para evitar publicidad no deseada al replicar contenido:
- **Reemplazo automático de enlaces:** Reemplaza enlaces del canal original por tus propios enlaces de afiliado o contacto.
- **Filtro de palabras prohibidas:** Omite mensajes que contengan ciertas frases o marcas no deseadas.
- **Filtro de multimedia:** Elige si solo deseas replicar texto, solo imágenes, videos o documentos.

---

## 6. Protección Anti-Flood y Horarios Silenciosos

Para garantizar la salud de tus cuentas y canales:
- **Delays Inteligentes:** El sistema añade pausas aleatorias y configurables entre cada envío para evitar restricciones de `FloodWait` impuestas por Telegram.
- **Horarios Silenciosos:** Define franjas horarias (por ejemplo de 11:00 PM a 07:00 AM) donde el bot pausará automáticamente los envíos para no molestar a tu audiencia.
