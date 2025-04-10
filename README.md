<!-- 🌈 BANNER INICIAL -->
<p align="center">
  <img src="./banner_inicio.jpg" alt="Banner del proyecto Beacoder" width="100%" />
</p>

# 🚀 Beacoder_app  
**Código para una app ejemplo de estudiantes en Riwi**

---

## 📌 Bloque 1 – Requisitos (10 min)

👤 **Responsable:** Felipe Hincapié Murillo (Product Owner)  
🎯 **Solución digital:** Plataforma interactiva que **gamifica el proceso de aprendizaje**

🧩 **Problema que resuelve:**  
> Volver el proceso de aprendizaje más dinámico y atractivo mediante la gamificación.

👥 **Público objetivo:** Coders de Riwi

✨ **3 funcionalidades clave:**

- 🔐 **Sistema de login:** Registro e inicio de sesión de usuarios  
- 🗺️ **Ruta de aprendizaje interactiva:** Se desbloquea progresivamente (tipo Duolingo)  
- 🏆 **Tabla de puntajes:** Ranking visible con puntuaciones de todos los usuarios

---

## 🔍 Bloque 2 – Análisis (10 min)

👤 **Responsable:** Brayan (Analista)

📌 **Tareas clave:**

### 🔐 Login / Usuario
- Crear formulario de registro  
- Opción de personalizar perfil  
🟢 **Dificultad:** baja  
🚫 **Restricciones:**
  - Solo coders de Riwi con código de usuario pueden acceder  
  - No se aceptan nombres ni fotos de perfil inapropiados

---

### 🗺️ Ruta de aprendizaje interactiva
- Crear funcionalidad de niveles  
- Comparativa de respuestas para avanzar  
- Desbloqueo progresivo de nuevas funciones  
🔴 **Dificultad:** alta  
🚫 **Restricciones:**
  - Si no responde correctamente, no avanza al siguiente nivel

---

### 🏆 Tabla de puntajes
- Asignar puntos según progreso  
- Mostrar ranking general  
🟠 **Dificultad:** media  
🚫 **Restricciones:**
  - El puntaje debe ser justo y acorde al nivel  
  - El usuario no puede manipular la tabla

---

## 🎨 Bloque 3 – Diseño (10 min)

👤 **Responsable:** Alejandra (Diseñadora UX/UI)

🖼️ **Entregables de diseño:**

- <p align="center">
  <a href="https://www.figma.com/design/7IlKIdH5nFi9mJ9si3VH0N/Beacoder-desing?node-id=1-4670&t=uCMs8bNSdFegSxfc-1" target="_blank">
    <img src="https://img.shields.io/badge/🎨%20Ver%20en%20Figma-blueviolet?style=for-the-badge&logo=figma&logoColor=white" alt="Botón de Figma" />
  </a>
</p>

- 🔄 Diagrama simple del flujo de usuario

---

## 💻 Bloque 4 – Implementación (15 min)

👤 **Responsable:** Santiago (Desarrollador)

🛠️ **Feature implementada:** Registro de usuarios

📖 **Descripción:**

> Se permitirá crear un usuario por medio de un formulario. Se pedirá nombre de usuario y contraseña (doble validación). Luego podrá iniciar sesión con validación de datos.

<p align="center">
  <img src="./code.png" alt="Vista previa del algoritmo" width="600"/>
</p>

---

## 🧪 Bloque 5 – Pruebas (10 min)

👤 **Responsable:** Juan Pablo

🧬 **Redactar 3 casos de prueba funcionales:**

1. **Registro exitoso de usuario**
   - **Dado:** un formulario con campos válidos (nombre de usuario y contraseñas coincidentes)  
   - **Cuando:** el usuario hace clic en "Registrarse"  
   - **Entonces:** se crea la cuenta y redirige al login

2. **Inicio de sesión con credenciales correctas**
   - **Dado:** un usuario registrado  
   - **Cuando:** introduce su usuario y contraseña correctamente  
   - **Entonces:** puede acceder a la plataforma

3. **Restricción de acceso sin código de Riwi**
   - **Dado:** un formulario de registro  
   - **Cuando:** un usuario sin código Riwi intenta registrarse  
   - **Entonces:** el sistema muestra un mensaje de error e impide el acceso

⚠️ **Anticipación de posibles errores:**

- Contraseñas que no coinciden → advertencia
- Usuario ya registrado → alerta y evitar duplicados
- Campos vacíos o inválidos → bloqueo del formulario
- Intento de ingreso sin autenticación → redirección al login
- Fallo del servidor → mensaje de error general

---

## 🚢 Bloque 6 – Despliegue y Mantenimiento (5 min)

👤 **Responsable:** Susana

📦 **Estrategia de despliegue:**

- 🚀 **Frontend:** Deploy en [Netlify](https://www.netlify.com/) o [Vercel](https://vercel.com/)
- 🛠️ **Backend y Base de datos:** [Render](https://render.com/) o servidor propio con MongoDB Atlas
- 🛍️ **Almacenamiento futuro:** Stores tipo Google Play, App Store si se convierte en PWA o app móvil

🛠️ **Mejoras futuras:**

1. 🎯 Sistema de logros y recompensas por hitos
2. 🌐 Soporte para múltiples idiomas e internacionalización

---

<!-- 🎬 BANNER FINAL -->
<p align="center">
  <img src="./banner_final.jpg" alt="Gracias por leer - Beacoder App" width="100%" />
</p>
