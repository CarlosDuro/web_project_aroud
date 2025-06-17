# 🚀 Proyecto Sprint 7, 8, 9, 10 y 11 - Web Interactiva con POO

Una evolución progresiva del proyecto anterior, donde no solo se integran funcionalidades dinámicas sino también un enfoque profesional de arquitectura con **Programación Orientada a Objetos avanzada (POO)** y la incorporación de herramientas modernas como **NPM** para una mejor gestión del código y dependencias. Se trata de una página web interactiva enfocada en perfiles de usuario, con opciones para agregarlos, editarlos, eliminarlos y reaccionar a ellos. 💬👥

---

## 🧰 Tecnologías Utilizadas

| Herramienta                      | Descripción breve                                  |
| -------------------------------- | -------------------------------------------------- |
| 🎨 **Figma**                     | Diseño y prototipado de interfaz                   |
| 🌐 **HTML**                      | Estructura básica del sitio                        |
| 🎨 **CSS**                       | Estilos visuales y animaciones                     |
| 🔄 **Metodología BEM**           | Organización escalable de clases CSS               |
| 🧱 **CSS Grid**                  | Sistema de maquetado flexible                      |
| 📱 **Responsive Design**         | Adaptabilidad a diferentes dispositivos            |
| 🧠 **JavaScript (POO avanzada)** | Estructura del proyecto basada en clases modulares |
| 📦 **NPM**                       | Gestión de dependencias y scripts de construcción  |
| 🧾 **Validación de Formularios** | Control y validación de entradas del usuario       |
| 🛠️ **GIT**                       | Control de versiones y trabajo colaborativo        |

---

## ✨ Descripción del Proyecto

> Esta aplicación web representa una interfaz moderna para manejar perfiles de usuarios, donde el usuario puede:

- ➕ **Añadir nuevos perfiles**
- ❌ **Eliminar tarjetas existentes**
- ✏️ **Editar información del perfil**
- ❤️ **Marcar perfiles como favoritos**
- 🔍 **Ver imágenes en pantalla completa**
- ❌ **Cerrar popups con Escape o clic en la superposición**

Todo esto se implementa con una arquitectura orientada a objetos en JavaScript, dividiendo responsabilidades en clases específicas, facilitando el mantenimiento y escalabilidad del proyecto.

---

## 💡 Mejora clave: Programación Orientada a Objetos

El proyecto fue refactorizado profundamente usando principios avanzados de **POO en JavaScript** junto con **modularización mediante ES Modules y herramientas de entorno profesional como NPM**.

### Características implementadas:

- 🔹 **Encapsulación**: Cada componente (Card, Form, Popup, UserInfo) maneja sus propios datos y métodos.
- 🔹 **Herencia y composición**: Clases como `PopupWithImage`, `PopupWithForm` extienden de una clase base `Popup`, reutilizando y personalizando funcionalidad.
- 🔹 **Responsabilidad única**: Cada clase tiene una única responsabilidad (principio SRP).
- 🔹 **Uso de NPM**:
  - Scripts de desarrollo: `npm run build`, `npm run start`
  - Estructura moderna del proyecto (`package.json`, `modules`, `dist`)
  - Posible integración de herramientas como Webpack y Babel

---

## 📸 Vista Previa (opcional)

_![Demo de la app](images/moved_project-4-01-eng.gif)
_

---

## 📂 Estructura del Código

```plaintext
📁 proyecto/
├── 📁 blocks/                   # Estilos CSS modulares organizados por componentes (BEM)
│   ├── cards.css
│   ├── footer.css
│   ├── header.css
│   ├── page.css
│   ├── popup.css
│   ├── profile.css
│
├── 📁 images/                  # Recursos gráficos
│
├── 📁 pages/
│   ├── index.html             # Página principal
│   └── index.css              # Estilos globales
│
├── 📁 scripts/
│   ├── index.js               # Punto de entrada del proyecto
│   ├── utils.js               # Utilidades y configuración global
│   └── 📁 components/         # Clases modulares (POO)
│       ├── Card.js
│       ├── FormValidator.js
│       ├── Popup.js
│       ├── PopupWithForm.js
│       ├── PopupWithImage.js
│       ├── Section.js
│       └── UserInfo.js
│
├── 📁 vendor/                 # Recursos de terceros (si aplica)
├── 📄 package.json            # Configuración NPM
├── 📄 .gitignore              # Archivos y carpetas ignoradas por Git
├── 📄 README.md               # Este documento
└── 📄 favicon.ico             # Ícono del sitio
```

🌐 **Ver el proyecto en línea:**  
👉 [https://carlosduro.github.io/web_project_around/](https://carlosduro.github.io/web_project_around/)
