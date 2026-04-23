# 📊 Dashboard POI 2026 — UTI · Programa Nacional Cuna Más

> **Tablero interactivo de seguimiento del Plan Operativo Institucional 2026**  
> Unidad de Tecnologías de la Información · PNCM / MIDIS

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Publicado-005B8E?style=flat-square&logo=github)](https://TU-USUARIO.github.io/poi-uti-pncm-2026/)
[![POI 2026](https://img.shields.io/badge/POI-2026-E8A020?style=flat-square)](https://www.cunamas.gob.pe)
[![PNCM](https://img.shields.io/badge/PNCM-MIDIS-1A9E5C?style=flat-square)](https://www.cunamas.gob.pe)

---

## 📋 Descripción

Este repositorio contiene el **dashboard interactivo** de seguimiento del Plan Operativo Institucional (POI) 2026 de la **Unidad de Tecnologías de la Información (UTI)** del Programa Nacional Cuna Más, así como el **informe técnico** en formato Word correspondiente a los períodos de **Febrero y Marzo 2026**.

### 🎯 ¿Qué contiene?

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Dashboard interactivo (renombrado desde `dashboard_poi_uti_pncm.html`) |
| `Informe_POI_UTI_PNCM_Feb_Mar_2026.docx` | Informe técnico descargable |
| `README.md` | Este archivo |

---

## 🚀 Publicación en GitHub Pages — Paso a Paso

### PASO 1 — Crear una cuenta en GitHub (si aún no la tienes)

1. Abre tu navegador y ve a **[https://github.com](https://github.com)**
2. Haz clic en **"Sign up"** (esquina superior derecha)
3. Completa el formulario:
   - **Username:** elige un nombre de usuario (ej. `uti-pncm` o tu nombre)
   - **Email:** ingresa tu correo institucional o personal
   - **Password:** crea una contraseña segura
4. Verifica tu cuenta a través del correo electrónico recibido
5. Selecciona el plan **Free** (gratuito) — es suficiente para GitHub Pages

---

### PASO 2 — Crear el repositorio

1. Una vez iniciada sesión, haz clic en el ícono **"+"** (esquina superior derecha)
2. Selecciona **"New repository"**
3. Completa los campos:
   - **Repository name:** `poi-uti-pncm-2026`
   - **Description:** `Dashboard POI 2026 - UTI Programa Nacional Cuna Más`
   - **Visibility:** selecciona ✅ **Public** (requerido para GitHub Pages gratuito)
   - Marca ✅ **"Add a README file"**
4. Haz clic en **"Create repository"**

> ⚠️ **Importante:** El repositorio debe ser **público** para usar GitHub Pages de forma gratuita.

---

### PASO 3 — Subir los archivos al repositorio

#### Opción A — Subida directa desde el navegador (más sencilla) ✅ Recomendada

1. Dentro de tu repositorio, haz clic en **"Add file"** → **"Upload files"**
2. Arrastra o selecciona los siguientes archivos:
   - `dashboard_poi_uti_pncm.html` → **renómbralo a `index.html`** antes de subir
   - `Informe_POI_UTI_PNCM_Feb_Mar_2026.docx`
   - `README.md`
3. En la sección **"Commit changes"**:
   - Escribe un mensaje, ej.: `Carga inicial: Dashboard POI 2026 UTI`
   - Selecciona **"Commit directly to the main branch"**
4. Haz clic en **"Commit changes"**

> 💡 **Nota sobre el nombre del archivo:**  
> GitHub Pages sirve automáticamente el archivo llamado `index.html` como página principal.  
> Por eso debes renombrar `dashboard_poi_uti_pncm.html` → `index.html` antes de subirlo.

#### Opción B — Usando Git desde la terminal (para usuarios avanzados)

```bash
# 1. Clona el repositorio vacío
git clone https://github.com/TU-USUARIO/poi-uti-pncm-2026.git
cd poi-uti-pncm-2026

# 2. Copia los archivos al directorio clonado
cp /ruta/a/dashboard_poi_uti_pncm.html ./index.html
cp /ruta/a/Informe_POI_UTI_PNCM_Feb_Mar_2026.docx ./
cp /ruta/a/README.md ./

# 3. Agrega, confirma y sube los cambios
git add .
git commit -m "Carga inicial: Dashboard POI 2026 UTI PNCM"
git push origin main
```

---

### PASO 4 — Activar GitHub Pages

1. En tu repositorio, ve a **"Settings"** (ícono ⚙️ en el menú superior)
2. En el menú lateral izquierdo, haz clic en **"Pages"**
3. Bajo la sección **"Build and deployment"**:
   - **Source:** selecciona `Deploy from a branch`
   - **Branch:** selecciona `main` y la carpeta `/ (root)`
4. Haz clic en **"Save"**
5. Espera entre **1 y 3 minutos** mientras GitHub construye tu sitio

---

### PASO 5 — Acceder a tu Dashboard publicado

Después de unos minutos, aparecerá un mensaje verde en la página de Settings → Pages:

```
✅ Your site is live at:
https://TU-USUARIO.github.io/poi-uti-pncm-2026/
```

Haz clic en ese enlace para verificar que el dashboard está funcionando correctamente.

> 🔗 **Comparte este enlace** con la Dirección Ejecutiva, la UPPM y otras unidades del PNCM.

---

### PASO 6 — Actualizar el dashboard en el futuro

Cuando necesites actualizar los datos (nuevos períodos de seguimiento):

1. Ve a tu repositorio en GitHub
2. Haz clic en el archivo `index.html`
3. Haz clic en el ícono **✏️ (lápiz)** para editarlo
4. Modifica los datos directamente en el editor web
5. Haz clic en **"Commit changes"** para guardar

O bien, sube una nueva versión del archivo `index.html` siguiendo el **Paso 3 — Opción A**.

---

## 📐 Estructura del Dashboard

El dashboard contiene **6 secciones** navegables:

| Sección | Contenido |
|---------|-----------|
| 📊 Resumen Ejecutivo | KPIs, gráficos de avance trimestral y mensual |
| 🎯 Metas Físicas | Tabla detallada mes a mes con estados y % avance |
| 📝 Análisis Cualitativo | Factores, dificultades y medidas por período |
| ⚠️ Riesgos | Matriz de riesgos identificados con mapa de calor |
| 📁 Documentos | Listado de memorandos sustentatorios |
| 🔗 Alineación PEI | Cadena estratégica OEI → AEI → Tarea POI |

---

## 🎨 Identidad Visual PNCM

Los colores utilizados corresponden a la identidad institucional del Programa Nacional Cuna Más:

| Color | Código HEX | Uso |
|-------|-----------|-----|
| 🔵 Azul PNCM | `#005B8E` | Encabezados, navbar, KPIs principales |
| 🟠 Naranja PNCM | `#E8A020` | Acentos, badges, highlights |
| 🟢 Verde | `#1A9E5C` | Estados cumplidos, indicadores positivos |
| 🔴 Rojo | `#D63031` | Alertas, riesgos altos |

---

## 📊 Datos del POI 2026 — UTI

| Indicador | Valor |
|-----------|-------|
| Tarea | Implementación y Administración de los Sistemas de TI |
| Unidad Ejecutora | 003 — Programa Nacional Cuna Más |
| Meta Anual | 17 informes |
| OEI | OEI 08 — Fortalecer la gestión institucional |
| AEI | AEI.08.02 — Transformación Digital en el MIDIS |
| Avance Febrero | 2/2 → 100% |
| Avance Marzo | 2/2 → 100% |
| Avance Acumulado (I Trim.) | 4/17 → 23.53% |
| Base legal | R.M. N.° 351-2025-MIDIS |

---

## 🗂️ Base Legal

- Resolución Ministerial N.° 351-2025-MIDIS — Aprueba el POI Anual 2026
- Resolución Ministerial N.° 060-2024-MIDIS — Aprueba el PEI 2024–2030
- Decreto Legislativo N.° 1412 — Ley de Gobierno Digital
- Decreto Supremo N.° 029-2021-PCM — Reglamento de la Ley de Gobierno Digital
- Resolución de Secretaría de Gobierno Digital N.° 005-2018-PCM/SEGDI

---

## 👤 Responsable

**Giovanna Nancy Hernández Portal**  
Ejecutiva de Tecnologías de la Información  
Unidad de Tecnologías de la Información — UTI  
Programa Nacional Cuna Más · MIDIS  
Lima, Perú · 2026

---

*Generado el 22 de abril de 2026 · Dashboard POI UTI PNCM 2026*
