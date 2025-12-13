# 💖 “¿Estás enojada conmigo?”


[![Ver video]([https://www.youtube.com/watch?v=VIDEO_ID](https://youtu.be/PWB0uCoBo6w))

Mini página en **HTML + CSS + JS** con modo “enojo ➜ arrepentido” y lluvia de **“TE AMO”** al presionar un botón.  
Optimizada para **móvil (responsive + scroll OK)**.

---

## ✅ Demo / Preview
> Cuando esté desplegado en Vercel, pega aquí tu enlace:
- **Live:** https://TU-PROYECTO.vercel.app

---

## 🧩 Tecnologías
- HTML5
- CSS3 (responsive)
- JavaScript (vanilla)

---

## 📁 Estructura recomendada
Asegúrate de tener **`index.html`** en la raíz del proyecto:


> Importante: Vercel carga `/` desde `index.html`.  
> Si tu archivo se llama `love.htm`, renómbralo a `index.html`.

---

## ▶️ Probar local (antes de subir)
Opción rápida:
1. Abre `index.html` en tu navegador (doble click)

Opción recomendada (servidor local):
- **VS Code** ➜ instala extensión **Live Server** ➜ clic derecho en `index.html` ➜ **Open with Live Server**

---

# 🚀 Subir a GitHub usando GitHub Desktop

## 1) Crear el repositorio en GitHub
1. Entra a GitHub (web)
2. **New repository**
3. Nombre: `love-page` (o el que quieras)
4. **Create repository**

## 2) Subir el proyecto con GitHub Desktop
1. Abre **GitHub Desktop**
2. Ve a **File ➜ Add Local Repository…**
3. Selecciona la carpeta donde está tu `index.html`
   - Si no está inicializado como repo, GitHub Desktop te va a ofrecer **Create a Repository** ➜ acéptalo.
4. En **Summary** escribe algo como: `Initial commit`
5. Clic en **Commit to main**
6. Clic en **Publish repository**
   - (Opcional) Desmarca “Keep this code private” si lo quieres público.

✅ Listo: ya está en GitHub.

---

# 🌐 Deploy en Vercel (HTML plano)

## 1) Importar el repo
1. Entra a **Vercel**
2. **Add New ➜ Project**
3. Selecciona tu repo `love-page`
4. Clic en **Import**

## 2) Configuración correcta (IMPORTANTE)
En **Framework Preset** selecciona:
- ✅ **Other** (o “No Framework”)

Luego verifica:
- **Build Command:** *(vacío / none)*
- **Output Directory:** *(vacío)* o `.`  
  - ⚠️ Si tu proyecto tiene una carpeta `public/`, Vercel puede intentar servir desde `public`.  
    En ese caso, mueve `index.html` a `public/index.html` **o** fuerza Output Directory = `.`

5. Clic en **Deploy**

✅ Tu web debe quedar en algo como:
- `https://love-page-xxxx.vercel.app`

---

## 🧯 Errores comunes (y solución rápida)

### ❌ No carga en Vercel / sale 404
- Falta `index.html` en la raíz.
- Solución: **renombra tu archivo a `index.html`** y redeploy.

### ❌ CSS/JS no cargan en Vercel
- Revisa rutas y mayúsculas/minúsculas (Linux es estricto).
- Usa rutas así:
  - `./style.css`
  - `./app.js`

### ❌ En móvil no deja hacer scroll
- No uses `overflow: hidden` en `body`.
- (Ya está corregido en la versión actual.)

---

## 🔁 Actualizar cambios
1. Edita tu `index.html`
2. GitHub Desktop:
   - Summary: `Update UI` (ejemplo)
   - **Commit to main**
   - **Push origin**
3. Vercel detecta el push y redeploy automáticamente ✅

---

# 🎥 Video (debajo)
Pega aquí tu video:

## Opción A: Link directo
👉 **Video:** TU_LINK_AQUI

## Opción B: YouTube con miniatura (recomendado)
Reemplaza `VIDEO_ID` por el ID de YouTube:



