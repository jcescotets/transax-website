# Transax — Landing Page Oficial

Infraestructura Fintech Inteligente para la Economía Real.  
Sitio web: **www.transax-payments.com**

---

## 📁 Estructura del proyecto

```
transax-site/
├── index.html                  ← Página principal
├── CNAME                       ← Configuración de dominio personalizado
├── transax-logo.png            ← Logo para tema dark
├── transax-logo-light.png      ← Logo original (fondo claro)
├── transax-video.mp4           ← Video corporativo "El Oráculo IA"
├── transax-whitepaper.pdf      ← White Paper descargable
└── README.md                   ← Este archivo
```

---

## 🚀 INSTRUCCIONES DE DESPLIEGUE

### Paso 1: Crear repositorio en GitHub

1. Ve a **https://github.com/new**
2. Nombre del repositorio: `transax-website` (u otro nombre que prefieras)
3. Selecciona **Public** (necesario para GitHub Pages gratuito)
4. **NO** inicialices con README (lo subiremos nosotros)
5. Clic en **Create repository**

### Paso 2: Subir archivos al repositorio

#### Opción A — Desde la interfaz web de GitHub (más fácil):
1. En el repositorio recién creado, haz clic en **"uploading an existing file"**
2. Arrastra TODOS los archivos de esta carpeta (index.html, CNAME, logo, video, pdf)
3. ⚠️ **IMPORTANTE**: El video pesa ~28MB, la subida puede tardar unos minutos
4. En "Commit changes", escribe: "Initial commit - Transax landing page"
5. Clic en **Commit changes**

#### Opción B — Desde terminal (si tienes Git instalado):
```bash
cd transax-site
git init
git add .
git commit -m "Initial commit - Transax landing page"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/transax-website.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. Ve a tu repositorio → **Settings** (pestaña superior)
2. En el menú lateral, busca **Pages**
3. En **Source**, selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
4. Clic en **Save**
5. GitHub te mostrará la URL temporal: `https://tu-usuario.github.io/transax-website/`

### Paso 4: Configurar el dominio www.transax-payments.com

#### 4a. En tu proveedor de dominio (donde compraste transax-payments.com):

Ve a la configuración DNS y añade estos registros:

**Para el dominio raíz (transax-payments.com):**
```
Tipo: A
Nombre: @
Valor: 185.199.108.153

Tipo: A
Nombre: @
Valor: 185.199.109.153

Tipo: A
Nombre: @
Valor: 185.199.110.153

Tipo: A
Nombre: @
Valor: 185.199.111.153
```

**Para www (www.transax-payments.com):**
```
Tipo: CNAME
Nombre: www
Valor: TU_USUARIO.github.io
```

> Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub.

#### 4b. En GitHub Pages:

1. Ve a Settings → Pages
2. En **Custom domain**, escribe: `www.transax-payments.com`
3. Clic en **Save**
4. Espera a que aparezca ✅ "DNS check successful"
5. Marca la casilla **Enforce HTTPS** (puede tardar hasta 24h en activarse)

> ⏳ La propagación DNS puede tardar entre 15 minutos y 48 horas.

---

## ✅ Verificación

Una vez completados todos los pasos:
- `https://www.transax-payments.com` → Tu landing page
- `https://transax-payments.com` → Redirige a www automáticamente
- El certificado SSL se genera automáticamente (HTTPS gratuito)

---

## 🔧 Mantenimiento

Para actualizar contenido:
1. Edita `index.html` directamente en GitHub (clic en el archivo → ícono de lápiz)
2. O sube una nueva versión del archivo
3. Los cambios se publican automáticamente en 1-2 minutos

---

## 📧 Contacto

- **Email**: transax@iqtsystems.com
- **Teléfono**: +34 600 622 887
- **Países**: Venezuela · España

---

© 2026 Transax · IQT Systems. Todos los derechos reservados.
