# Quindío/chan v1.0 BETA 🖥️

## Foro Técnico-Académico del Eje Cafetero

![Terminal](https://img.shields.io/badge/Style-Terminal-green)
![Version](https://img.shields.io/badge/Version-1.0--BETA-blue)
![License](https://img.shields.io/badge/License-MIT-orange)

### 🎯 Descripción

Quindío/chan es un foro estilo 4chan con estética de terminal Linux, diseñado específicamente para la comunidad técnica y académica del Quindío. Un espacio para discutir sobre programación, sistemas operativos, ciencias de la computación, física, matemáticas y más.

### 🏛️ Instituciones Representadas

- **CUE Alexander Von Humboldt**
- **Universidad del Quindío**
- **SENA**
- **EAM**

### 📋 Boards Disponibles

- `/prog/` - Programación (C, C++, Python, Java, JavaScript, Rust, Go)
- `/linux/` - GNU/Linux (Distribuciones, kernel, administración)
- `/soft/` - Software (Aplicaciones, herramientas, desarrollo)
- `/cs/` - Ciencias de la Computación (Algoritmos, estructuras de datos)
- `/unix/` - Unix-like (macOS, FreeBSD, OpenBSD, Solaris)
- `/ia/` - Inteligencia Artificial (ML, DL, NLP, Computer Vision, LLMs)
- `/net/` - Redes y Servidores (DevOps, SysAdmin, Cloud)
- `/sec/` - Seguridad (Ciberseguridad, pentesting, criptografía)
- `/math/` - Matemáticas
- `/phys/` - Física
- `/sci/` - Ciencias
- `/tic/` - TIC
- `/ing/` - Ingenierías
- `/acad/` - Académico
- `/meta/` - Meta (sobre el foro)

### 🚀 Deploy en GitHub Pages

#### Paso 1: Crear repositorio

```bash
git init
git add .
git commit -m "Initial commit - Quindío/chan v1.0 BETA"
```

#### Paso 2: Renombrar archivo

Renombra `quindio-chan.html` a `index.html`:

```bash
mv quindio-chan.html index.html
```

#### Paso 3: Subir a GitHub

```bash
git remote add origin https://github.com/tu-usuario/quindio-chan.git
git branch -M main
git push -u origin main
```

#### Paso 4: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Click en **Settings**
3. En el menú lateral, click en **Pages**
4. En **Source**, selecciona la rama `main`
5. Selecciona la carpeta `/ (root)`
6. Click en **Save**

Tu foro estará disponible en: `https://tu-usuario.github.io/quindio-chan/`

### ⚙️ Características Técnicas

#### Stack Tecnológico
- **Frontend**: HTML5, CSS3, JavaScript Vanilla
- **Almacenamiento**: localStorage (persistencia local)
- **Estilo**: Terminal retro con colores verde sobre negro
- **Responsive**: Adaptable a diferentes tamaños de pantalla

#### Funcionalidades
- ✅ Creación de threads por board
- ✅ Sistema de respuestas
- ✅ Persistencia local con localStorage
- ✅ Formato de texto estilo 4chan
- ✅ Greentext support (>texto)
- ✅ Timestamps automáticos
- ✅ Contador de uptime
- ✅ Neofetch simulado estilo Fedora
- ✅ 100% funcional sin backend
- ✅ Compatible con GitHub Pages

### 🎨 Estética Terminal

El diseño simula una terminal de Linux con:
- Font monospace (Courier New)
- Colores verde (#33ff33) sobre negro (#0a0a0a)
- Efectos de glow/sombra
- Borde estilo ASCII
- Neofetch al estilo Fedora

### 💾 Almacenamiento

Los datos se guardan en el **localStorage** del navegador:
- Cada board tiene su propio storage key
- Los threads incluyen: ID, asunto, autor, contenido, timestamp
- Las respuestas se anidan dentro de cada thread
- Los datos persisten entre sesiones (local al navegador)

**Nota**: Como usa localStorage, los posts son locales a cada navegador. Para un sistema con base de datos compartida, se necesitaría un backend.

### 🔧 Personalización

Puedes personalizar fácilmente:

1. **Colores**: Modifica las variables CSS en la sección `<style>`
2. **Boards**: Edita el array `boards` en el JavaScript
3. **Instituciones**: Actualiza la sección `.institutions` en el HTML

### 📱 Uso

1. **Navegar**: Click en cualquier board para ver los threads
2. **Crear thread**: Click en "Crear nuevo thread"
3. **Responder**: Abre un thread y click en "Responder"
4. **Greentext**: Usa `>` al inicio de una línea para crear greentext
5. **Volver**: Usa los botones de navegación para regresar

### 🐛 Versión BETA

Esta es la versión **1.0 BETA**. Características futuras planeadas:
- [ ] Markdown support
- [ ] Syntax highlighting para código
- [ ] Búsqueda de threads
- [ ] Filtros por fecha
- [ ] Export/Import de datos
- [ ] Modo oscuro alternativo
- [ ] Estadísticas del board

### 🤝 Contribuir

Este es un proyecto de código abierto para la comunidad tech del Quindío. ¡Las contribuciones son bienvenidas!

### 📄 Licencia

MIT License - Libre para usar, modificar y distribuir.

### 🌐 Compatibilidad

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Navegadores modernos con soporte de localStorage

### 💡 Inspiración

Inspirado en:
- 4chan/2chan (estructura de boards y threads)
- Terminal de Linux (estética y UX)
- Neofetch (display de sistema)
- Cultura hacker y open source

---

**Hecho con ♥ para la comunidad tech del Quindío**

*"In the beginning there was the command line" - Neal Stephenson*

```
root@quindio-chan:~$ cat /etc/motd
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Welcome to Quindío/chan Terminal v1.0
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```