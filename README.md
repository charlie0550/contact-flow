# ContactFlow 📇

ContactFlow es una aplicación web moderna diseñada para la gestión eficiente de contactos, construida con **Next.js** y **Supabase**. Permite a los usuarios importar, organizar, editar y exportar contactos de manera intuitiva.

## 🚀 Características

- **Gestión Completa de Contactos:** Crea, edita, ve y elimina contactos con campos personalizados, fotos y etiquetas.
- **Importación Flexible:** Importa contactos fácilmente desde archivos `.csv` y tarjetas virtuales de formato `.vcf` (vCard).
- **Internacionalización (i18n):** Soporte multiidioma completo (Español e Inglés).
- **Tema Claro / Oscuro:** Interfaz moderna y adaptable que cuida tu vista.
- **Pruebas Automatizadas:** Cobertura de pruebas unitarias con Vitest y pruebas extremo a extremo (E2E) con Playwright.

## 🛠️ Tecnologías utilizadas

- **Framework:** [Next.js](https://nextjs.org/) (App Router)
- **Base de datos y Autenticación:** [Supabase](https://supabase.com/)
- **Estilos:** Tailwind CSS y Radix UI
- **Pruebas:** Vitest (unitarias) y Playwright (E2E)

## 📦 Instalación y Configuración

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/charlie0550/contact-flow.git
   cd contact-flow
   ```

2. **Instala las dependencias:**
   ```bash
   npm install
   ```

3. **Configura las variables de entorno:**
   Crea un archivo `.env.local` en la raíz del proyecto y añade tus credenciales de Supabase:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=tu-supabase-url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=tu-supabase-anon-key
   ```

4. **Inicia el servidor de desarrollo:**
   ```bash
   npm run dev
   ```
   Abre [http://localhost:3000](http://localhost:3000) en tu navegador para ver la aplicación.

## 🧪 Pruebas

Para ejecutar las pruebas unitarias:
```bash
npm run test
```

Para ejecutar las pruebas de integración/E2E con Playwright:
```bash
npm run test:e2e
```
