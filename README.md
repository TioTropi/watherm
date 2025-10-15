# Watherm Solutions Website

Sitio web corporativo moderno para Watherm Solutions, empresa especializada en tratamiento de aguas industriales.

## Tecnologías

- **React 19.1.0** - Última versión de React con mejoras de rendimiento
- **Next.js 15.5.4** - Framework de React con App Router
- **Tailwind CSS v4** - Framework de CSS utility-first
- **TypeScript 5** - Tipado estático para JavaScript
- **Radix UI** - Componentes accesibles y sin estilos
- **React Hook Form + Zod** - Validación de formularios
- **Recharts** - Gráficos interactivos
- **Sonner** - Notificaciones toast

## Instalación

\`\`\`bash
# Instalar dependencias
npm install

# Ejecutar en desarrollo
npm run dev

# Construir para producción
npm run build

# Iniciar servidor de producción
npm start
\`\`\`

## Estructura del Proyecto

\`\`\`
├── app/
│   ├── api/contact/       # API route para formulario de contacto
│   ├── layout.tsx         # Layout principal con metadata
│   ├── page.tsx           # Página principal
│   └── globals.css        # Estilos globales con Tailwind
├── components/
│   ├── navigation.tsx     # Menú de navegación flotante
│   ├── products-services-section.tsx  # Sección de productos y servicios
│   ├── theme-provider.tsx # Proveedor de tema claro/oscuro
│   └── ui/                # Componentes UI reutilizables
├── data/
│   └── problems.tsx       # Datos de problemas y soluciones
├── public/                # Archivos estáticos (imágenes, logos)
└── lib/
    └── utils.ts           # Utilidades (cn function)
\`\`\`

## Características

- ✅ Diseño responsive (móvil, tablet, desktop)
- ✅ Modo claro/oscuro
- ✅ Animaciones suaves con Intersection Observer
- ✅ Formulario de contacto con validación
- ✅ Gráficos interactivos de impacto
- ✅ Navegación flotante moderna
- ✅ Tarjetas flip interactivas en productos/servicios
- ✅ Optimizado para SEO con metadata
- ✅ Accesibilidad (ARIA labels, skip links)
- ✅ Analytics de Vercel integrado

## Despliegue en cPanel

1. Construir el proyecto:
\`\`\`bash
npm run build
\`\`\`

2. Subir los siguientes archivos/carpetas al servidor:
   - `.next/` (carpeta generada)
   - `public/`
   - `package.json`
   - `next.config.mjs`
   - `node_modules/` (o ejecutar `npm install` en el servidor)

3. Configurar Node.js en cPanel:
   - Versión de Node: 18.x o superior
   - Comando de inicio: `npm start`
   - Puerto: 3000 (o el configurado)

4. Configurar variables de entorno si es necesario

## Compatibilidad

- ✅ React 19 (compatible con React 18)
- ✅ Next.js 15 App Router
- ✅ Node.js 18+
- ✅ Navegadores modernos (Chrome, Firefox, Safari, Edge)
- ✅ Dispositivos móviles (iOS, Android)

## Licencia

© 2025 Watherm Solutions. Todos los derechos reservados.
