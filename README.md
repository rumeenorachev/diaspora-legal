# 🏫 Diaspora — Plataforma SaaS para academias de idiomas

<img src="images/1. Login.png" width="250">

**Diaspora** es una plataforma SaaS diseñada para **digitalizar la gestión de academias de idiomas** mediante una aplicación móvil conectada a un backend centralizado.

Permite administrar:

- alumnos
- profesores
- clases
- resultados académicos
- facturación
- comunicación interna

Todo desde una **única aplicación móvil**.

Actualmente el sistema se encuentra en **fase piloto**, siendo probado inicialmente en la academia **Diaspora Languages Zaragoza**.

---

# 📱 Descargar aplicación (Android)

La aplicación se encuentra actualmente en **fase de pruebas cerradas** antes de su publicación oficial en Google Play.

Si tienes Android puedes solicitar acceso para probarla:

👉 https://play.google.com/store/apps/details?id=es.rumenorachev.diaspora

Debido a que se trata de una **versión de testing**, es necesario solicitar permiso para poder instalarla.

---

# 🎯 Objetivo del proyecto

Muchas academias gestionan su información mediante:

- hojas de Excel
- correos electrónicos
- WhatsApp
- documentos manuales

El objetivo de este proyecto es **centralizar toda la gestión académica en una única plataforma digital**.

Esto permite:

- mejorar la comunicación
- automatizar procesos
- facilitar el seguimiento académico
- gestionar pagos y facturación

---

# 🧱 Arquitectura

La plataforma sigue una arquitectura **cliente-servidor**.

## Backend

- Django
- Django REST Framework
- PostgreSQL
- Cloudflare Tunnel
- generación automática de facturas en PDF

## App móvil

- Flutter
- arquitectura modular
- consumo de API REST
- interfaz adaptada según rol de usuario

---

# 👥 Roles del sistema

La plataforma incluye **tres tipos de usuario**.

---

## 👨‍💼 Administrador

El administrador gestiona toda la academia.

Puede:

- gestionar profesores
- crear clases
- matricular alumnos
- publicar resultados
- gestionar facturación
- enviar anuncios

<img src="images/2. Panel administrador.jpg" width="300">

---

## 👩‍🏫 Profesor

El profesor dispone de un panel adaptado a su actividad docente.

Puede:

- consultar sus clases
- ver los alumnos de cada grupo
- publicar resultados
- comunicarse con alumnos mediante chat

<img src="images/3. Panel profesor.jpg" width="300">

---

## 👨‍🎓 Alumno

El alumno tiene acceso a un panel simplificado.

Puede:

- consultar anuncios de la academia
- revisar resultados de exámenes
- ver el estado de sus facturas
- comunicarse con profesores y compañeros

<img src="images/4. Panel alumno.jpg" width="300">

---

# 🔐 Sistema de acceso

El acceso se realiza mediante:

- usuario o email
- contraseña

También se pueden utilizar **códigos de invitación** para registrar nuevos usuarios en la plataforma.

<img src="images/1. Login.png" width="300">

---

# 💬 Chat interno

La aplicación incluye un **sistema de mensajería interna** que permite la comunicación entre profesores y alumnos dentro de cada grupo.

<img src="images/5. Chat.jpg" width="300">

---

# 📊 Resultados académicos

Los profesores pueden publicar resultados de exámenes y comentarios personalizados.

Cada resultado incluye:

- puntuación
- estado (APTO / NO APTO)
- comentario del profesor
- fecha de publicación

<img src="images/6. Resultado.jpg" width="300">

---

# 💳 Gestión de facturación

Los alumnos pueden consultar el estado de sus pagos directamente desde la aplicación.

La plataforma permite:

- visualizar facturas
- consultar fechas de vencimiento
- descargar facturas en PDF
- ver el estado del pago

<img src="images/7. Facturas.jpg" width="300">

---

# 🧪 Academia piloto

La primera academia en utilizar el sistema es:

**Diaspora Languages**

Este entorno real se utiliza para **probar y validar la plataforma antes de expandirla a más academias**.

---

# 🚀 Estado del proyecto

Actualmente el sistema se encuentra en **fase piloto**.

Funcionalidades implementadas:

- gestión de usuarios
- gestión de clases
- chat interno
- publicación de resultados
- facturación
- generación automática de PDFs

El sistema continuará evolucionando con nuevas funcionalidades.

---

# 🔒 Código fuente

El código completo de la plataforma se encuentra en un repositorio **privado**.

Este repositorio público incluye:

- documentación del proyecto
- capturas de la aplicación
- explicación funcional de la plataforma

Si deseas revisar el código (empresas, profesores o reclutadores):

📩 Contacta conmigo y te enviaré acceso.

---

# 🌐 Portfolio

Puedes ver este proyecto en mi portfolio:

👉 https://www.rumenorachev.es

---

# 👤 Autor

**Rumen Orachev**

Desarrollador Full Stack

Proyecto desarrollado como parte de mi formación en  
**Desarrollo de Aplicaciones Multiplataforma (DAM)**.
