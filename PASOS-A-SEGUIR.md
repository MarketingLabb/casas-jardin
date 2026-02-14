# 🚀 PASOS A SEGUIR - SISTEMA DE TRACKING PROFESIONAL

## 📋 RESUMEN DEL PROYECTO

Implementar sistema profesional de tracking para el micrositio **CASAS JARDÍN** que registre cada visitante antes de acceder al contenido.

---

## ✅ ESTADO ACTUAL

- ✅ Repositorio Git creado y sincronizado con GitHub
- ✅ Código HTML/CSS base funcionando con imágenes retocadas
- ✅ Commit inicial (v1) establecido como versión base
- ✅ GitHub repo: https://github.com/MarketingLabb/casas-jardin
- ⏳ GitHub Pages pendiente de activación

---

## 🎯 OBJETIVO: OPCIÓN 3 - SISTEMA PROFESIONAL

### LO QUE SE VA A IMPLEMENTAR:

### 1. **PANTALLA DE BIENVENIDA (Landing Page)**
- Formulario obligatorio antes de ver el contenido
- Campos: Nombre, Email, Teléfono (opcional)
- Diseño elegante que mantenga la estética del sitio
- Botón "VER CASAS JARDÍN"
- Validación de email

### 2. **BASE DE DATOS (Firebase/Google)**
- Almacenamiento de cada registro:
  - Nombre completo
  - Email
  - Teléfono (si lo proporciona)
  - Fecha y hora exacta de entrada
  - IP del visitante
  - Dispositivo usado (móvil/desktop)
  - Navegador

### 3. **TRACKING AUTOMÁTICO EN TIEMPO REAL**
Mientras el usuario navega:
- Tiempo total de permanencia en el sitio
- Páginas visitadas (qué casas vio)
- Tiempo en cada página/casa
- Orden de navegación
- Scrolls y clics registrados
- Hora de salida del sitio

### 4. **PANEL DE ADMINISTRACIÓN**
Ruta especial: `/admin` o `/dashboard`
- Login con password
- Vista de todos los visitantes
- Tabla con datos completos
- Gráficas y estadísticas:
  - Visitas por día/hora
  - Casa más vista
  - Tiempo promedio de visita
  - Dispositivos más usados
- Exportar datos a Excel/CSV
- Búsqueda y filtros

### 5. **EXTRAS PROFESIONALES**
- [ ] Email automático a Paula cuando alguien entra
- [ ] Links únicos por cliente (tracking de quién compartió)
- [ ] Posibilidad de "expirar" el sitio después de fecha X
- [ ] Opción de restringir acceso por password adicional

---

## 📝 INFORMACIÓN PENDIENTE (NECESARIA PARA CONTINUAR)

Antes de ejecutar, necesito:

1. **Email de Gmail** para configurar Firebase
2. **Password para el panel admin** (mínimo 8 caracteres)
3. **¿Notificaciones por email?** Sí/No - ¿A qué email?
4. **Logo o imagen** para el formulario de bienvenida (opcional, puedo usar el branding actual)
5. **Título del formulario:** Ejemplo: "Bienvenido a CASAS JARDÍN" o personalizado

---

## 🛠️ STACK TÉCNICO A USAR

- **Frontend:** HTML, CSS (existente), JavaScript
- **Base de datos:** Firebase Firestore (gratis, de Google)
- **Autenticación admin:** Firebase Auth
- **Analytics:** Firebase Analytics + código custom
- **Hosting:** GitHub Pages (actual)
- **Notificaciones:** Firebase Cloud Functions o EmailJS

---

## ⏱️ ESTIMACIÓN DE TIEMPO

- Configuración Firebase: 10 min
- Formulario de entrada: 10 min
- Sistema de tracking: 15 min
- Panel de administración: 20 min
- Testing y ajustes: 15 min
- **TOTAL: 60-70 minutos**

---

## 🚦 PARA RETOMAR EL TRABAJO

**Cuando vuelvas, solo di:**

> "Verde nena! Retomemos el tracking profesional"

Y yo leeré este archivo y continuaremos desde donde lo dejamos.

---

## 📌 NOTAS IMPORTANTES

- El repositorio actual está limpio (solo v1)
- Las imágenes actuales son las retocadas (verde unificado)
- El servidor local funciona en: http://localhost:8000
- GitHub Pages URL (cuando se active): https://marketinglabb.github.io/casas-jardin/

---

## 🔄 PRÓXIMOS PASOS INMEDIATOS

1. Activar GitHub Pages en la configuración del repo
2. Obtener la información pendiente listada arriba
3. Configurar Firebase
4. Implementar formulario de entrada
5. Crear sistema de tracking
6. Desarrollar panel admin
7. Testing completo
8. Deploy final

---

**Última actualización:** 14 de febrero, 2026  
**Versión actual:** v1 (2039daf)  
**Estado:** Proyecto pausado - Pendiente de confirmación para continuar
