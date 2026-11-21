# 🏠 HogarBalance — Finanzas Familiares (Método 50 · 25 · 15 · 5 · 5)

**HogarBalance** es una aplicación web progresiva (PWA) ligera, moderna y autocontenida diseñada para gestionar el presupuesto familiar de forma colaborativa bajo la regla financiera **50 / 25 / 15 / 5 / 5**.

---

## 📊 Distribución del Método 50 · 25 · 15 · 5 · 5

A partir del ingreso total mensual del hogar, la aplicación calcula automáticamente los topes y metas ideales para cada rubro:

* **🔵 50% Necesidades Básicas:** Vivienda, alimentación, servicios públicos, salud, educación y transporte esencial.
* **🟣 25% Deseos y Estilo de Vida:** Salidas a comer, entretenimiento, suscripciones, ropa y vacaciones.
* **🟢 15% Ahorro e Inversión:** Metas familiares a mediano y largo plazo, vivienda propia o fondos de inversión.
* **🟡 5% Fondo de Emergencia:** Colchón de seguridad para imprevistos médicos o reparaciones urgentes.
* **🩷 5% Ayudas y Regalos:** Apoyo a familiares, donaciones, ofrendas y detalles especiales.

---

## ✨ Funcionalidades Principales

* **Gestión de Ingresos Multi-Integrante:** Registra las distintas fuentes de ingreso de la familia (*Papá, Mamá, ingresos extra*) y visualiza el saldo disponible en tiempo real.
* **Control de Movimientos por Integrante:** Asigna cada gasto o aporte a un miembro del hogar con filtros rápidos y comparación visual (*Real vs. Ideal*).
* **Cuentas por Cobrar (CxC) y Cuentas por Pagar (CxP):**
  * Soporte para **abonos parciales** o liquidación total con barra de progreso.
  * **Selector de destino en CxC:** Al cobrar un dinero pendiente, permite elegir si entra como *Ingreso General* (repartiéndose en los 5 porcentajes) o si se *reintegra directamente a un rubro específico* para liberar cupo.
* **Sincronización Familiar en Tiempo Real:** Conecta múltiples celulares al mismo presupuesto compartiendo un **Código de Hogar** (`HOGAR-XXXX`).
* **Respaldo Portátil:** Exporta e importa toda la información financiera en formato `.json` con un clic.
* **Instalable como App (PWA):** Funciona a pantalla completa sin barras de navegador en Android, iOS y escritorio, incluyendo soporte sin conexión.

---

## 🚀 Cómo publicar e instalar en el celular (con GitHub Pages)

1. Crea un nuevo repositorio público en **GitHub** (por ejemplo, `hogar-balance`).
2. Sube el archivo HTML de la aplicación renombrado como **`index.html`** junto con este **`README.md`**.
3. Ve a **Settings → Pages** en tu repositorio, selecciona la rama `main` (carpeta `/root`) y haz clic en **Save**.
4. Abre el enlace generado (`https://tu-usuario.github.io/hogar-balance/`) desde tu celular:
   * **Android (Chrome):** Menú de 3 puntos `⋮` → *"Instalar aplicación"* o *"Añadir a pantalla de inicio"*.
   * **iPhone / iPad (Safari):** Botón Compartir `⬆️` → *"Agregar a inicio"*.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 & JavaScript (Vanilla ES6+):** Arquitectura de archivo único sin dependencias de compilación.
* **Tailwind CSS:** Diseño responsivo adaptado a móviles y escritorio.
* **Firebase Firestore & Auth:** Sincronización multi-dispositivo en tiempo real.
* **PWA (Manifest + Service Worker):** Capacidad de instalación nativa y caché local.