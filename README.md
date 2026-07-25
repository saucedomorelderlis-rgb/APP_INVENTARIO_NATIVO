# 🎮 Proyecto de Videojuego / Game Development Project

[Español](#español) | [English](#english)

---

<a name="español"></a>
## 🇪🇸 Español

### 📌 Descripción del Proyecto
Este es un proyecto de desarrollo de videojuegos 3D independiente desarrollado por un **único creador**, construido completamente con **Python 3.12**. Utiliza **motores gráficos de código abierto** (como **Panda3D**) e integra modelos 3D y recursos de código libre (Open Source / Creative Commons), gestionados mediante una arquitectura modular de archivos y rutas relativas.

### 🚀 Características Principales
* **Desarrollo:** Proyecto individual e independiente.
* **Tecnología Base:** Python 3.12 y Motores Gráficos Open Source (Panda3D).
* **Recursos Abiertos:** Integración de modelos 3D, texturas y sonidos de código abierto.
* **Configuración Flexible:** Personalización de gráficos, pantalla y rendimiento mediante el archivo `Config.prc`.

### ⚙️ Configuración del Proyecto (`Config.prc`)

Para definir el entorno, variables de pantalla y rutas de recursos sin tocar el código principal:

**Opción A: Desde el archivo de configuración (`Config.prc`)**
Busca o crea el archivo `Config.prc` en la carpeta raíz de tu proyecto y añade las siguientes líneas de configuración básica y rutas:

```text
# ===============================================
# Configuración del Motor y Rutas de Assets
# ===============================================
# Configurar la carpeta principal de recursos (Assets)
model-path $MAIN_DIR/assets

# Configuración de Ventana y Gráficos
window-title Proyecto de Videojuego - Open Source Engine
win-size 1280 720
fullscreen false
show-frame-rate-meter true
sync-video true
