## 'https://wave110-lab.github.io/album-de-figuritas/'

# 🎴 Álbum Digital Pro 2026 - Colección Legendaria

Un álbum interactivo de figuritas (cromos/stickers) digitales desarrollado como una aplicación web moderna, estética y responsiva. Ofrece apertura de sobres en 3D, animación de cartas holográficas, sistema de gestión de repetidas y persistencia de datos mediante una base de datos local JSON (`localStorage`).

## ✨ Características Principales

- 🌓 **Diseño Moderno & Bootstrap 5:** Interfaz en modo oscuro/claro con diseño adaptativo (*glassmorphism*) para cualquier dispositivo (móvil, tablet o PC).
- 🔐 **Sistema de Usuarios & Perfiles:** Autenticación local con soporte para múltiples cuentas guardadas en el navegador.
- 🎴 **Álbum por Categorías:** Colecciones divididas en *Leyendas*, *Estrellas*, *Estadios* y *Momentos Históricos* con siluetas para figuritas faltantes y acabados *foil* (holográficos) para cartas Épicas y Leyendas.
- 📦 **Apertura de Sobres 3D:** Animación interactiva de rasgado con probabilidad de rareza (Común, Rara, Épica, Leyenda) y lanzamiento de confeti.
- 🔊 **Efectos de Sonido Sintetizados:** Audio interactivo generado mediante la Web Audio API (sonidos de rasgado, pegado y cartas especiales).
- 🔄 **Mercado de Repetidas:** Sistema de reciclaje e intercambio que permite canjear 3 figuritas repetidas por 1 sobre nuevo.
- 📊 **Inspector de Base de Datos:** Panel interactivo para auditar el estado del JSON local y visualizar estadísticas en tiempo real.

---

## 👥 Colaboración y Trabajo en Equipo

Para que los miembros del equipo puedan contribuir al proyecto de forma simultánea:

### 1. Añadir Colaboradores al Repositorio
1. En GitHub, ve a la pestaña **Settings** > **Collaborators**.
2. Haz clic en **Add people**.
3. Ingresa el usuario o correo de GitHub de tus compañeros y envía la invitación.

### 2. Flujo de Trabajo (Git)
Cada colaborador puede clonar el proyecto, hacer cambios y enviarlos a la rama principal:

```bash
# Clonar el repositorio
git clone https://github.com/TU-USUARIO/album-de-figuritas.git

# Subir cambios al repositorio
git add .
git commit -m "Añadida nueva funcionalidad / mejora de diseño"
git push origin main
```

---

## 👨‍🏫 Instrucciones para la Evaluación (Profesor)

Existen dos formas simples de revisar y calificar la aplicación:

### Opción A: Demostración en Vivo (GitHub Pages)
Puedes acceder a la versión web desplegada directamente en el navegador:
👉 https://wave110-lab.github.io/album-de-figuritas/
### Opción B: Ejecución Local
1. Haz clic en el botón **Code** > **Download ZIP** en este repositorio.
2. Descomprime el archivo `.zip` en tu computadora.
3. Abre el archivo `index.html` haciendo doble clic sobre él (no requiere servidores web adicionales).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3:** Estructura semántica y animaciones 3D.
- **Bootstrap 5:** Sistema de grilla responsivo y tematización (`data-bs-theme`).
- **JavaScript (ES6+):** Lógica orientada a objetos para la gestión del álbum y persistencia.
- **Web Audio API:** Efectos sonoros procedimentales nativos.
- **Canvas Confetti:** Efectos visuales al completar álbumes o desbloquear cartas Leyenda.

---

## 📁 Estructura del Repositorio

```text
├── index.html   # Aplicación web completa (HTML, CSS y JS integrado)
└── README.md    # Documentación y guía del proyecto
```
PROMPTS: https://share.gemini.google/prPMrWDTnXFr
