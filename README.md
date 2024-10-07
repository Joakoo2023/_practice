# Navbar Responsivo con Vite y React

Este proyecto es un componente de navbar (barra de navegación) responsivo hecho con Vite y React, que se adapta a diferentes tamaños de pantalla (mobile, tablet y desktop). El diseño sigue las especificaciones proporcionadas en un archivo de Figma.

## Características

- React y Vite: Desarrollado con React para componentes modulares y utilizando Vite como build tool para una experiencia de desarrollo rápida.
- Responsivo: El componente se adapta a diferentes tamaños de pantalla usando media queries.
- Desplegable en mobile/tablet: En mobile y tablet, el menú de navegación se oculta y aparece mediante un botón de menú (ícono "hamburger"), que despliega los enlaces de navegación con una animación de derecha a izquierda.
- Diseño exacto: Se siguen las medidas, colores, tipografías y espaciados del archivo de diseño de Figma.

## Requisitos

- Node.js (versión LTS recomendada)
- npm o yarn

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/navbar-responsivo.git
   ```

2. Instala las dependencias:
   Si usas npm:
   ```bash
   npm install
   ```
   O si usas yarn:
   ```bash
   yarn install
   ```

3. Ejecuta el proyecto en modo de desarrollo:
   ```bash
   npm run dev
   ```
   O con yarn:
   ```bash
   yarn dev
   ```

4. Abre tu navegador en `http://localhost:3000` para ver el componente.

## Estructura del proyecto

```
/navbar-responsivo
│
├── /src
│   ├── /components
│   │   └── Navbar.jsx      # Componente principal del navbar.
│   ├── /assets
│   │   └── logo.svg        # Imagen o ícono del logo.
│   ├── /styles
│   │   └── Navbar.css      # Estilos CSS del navbar.
│   └── main.jsx            # Punto de entrada principal de la app.
├── /public
│   └── index.html          # Archivo HTML base.
├── package.json            # Archivo de configuración de dependencias.
├── vite.config.js          # Archivo de configuración de Vite.
└── README.md               # Documentación del proyecto.
```

## Funcionalidades principales

- Desktop: El navbar muestra todos los enlaces de forma horizontal.
- Tablet: El navbar usa un menú hamburguesa. Al hacer clic en el ícono, los enlaces se deslizan desde la derecha.
- Mobile: El menú hamburguesa permite desplegar los enlaces en un menú deslizable.

## Scripts disponibles

- `npm run dev`: Inicia el servidor de desarrollo.
- `npm run build`: Genera la versión optimizada para producción.
- `npm run preview`: Previsualiza la versión de producción.

## Personalización

Puedes personalizar el navbar modificando:
- Los estilos en `Navbar.css`.
- La estructura del componente en `Navbar.jsx`.

## Contribuciones

Si deseas contribuir, sigue los siguientes pasos:
1. Haz un **fork** de este repositorio.
2. Crea una nueva **branch** para tu funcionalidad o corrección.
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y **haz un commit**.
   ```bash
   git commit -m "Agregada nueva funcionalidad"
   ```
4. Envía un **pull request** con tus cambios.

## Licencia

Este proyecto está licenciado bajo la [MIT License](https://opensource.org/licenses/MIT).
