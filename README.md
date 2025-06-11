# Explorador de Unidades CSS

![Versión](https://img.shields.io/badge/versión-0.1.0-blue)
![Licencia](https://img.shields.io/badge/licencia-MIT-green)

Una aplicación web educativa e interactiva que visualiza cómo funcionan las diferentes unidades CSS responsivas. Comprende visualmente cómo se comportan px, em, rem, %, vw/vh y fr en diferentes contextos y pantallas.

## 📋 Tabla de Contenidos

- [Características](#-características)
- [Unidades Visualizadas](#-unidades-visualizadas)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Contribuir](#-contribuir)
- [Licencia](#-licencia)

## ✨ Características

- Visualizaciones interactivas de cada unidad CSS
- Controles en tiempo real para experimentar con diferentes valores
- Comparaciones visuales entre unidades relacionadas
- Diseño responsivo para visualizar en cualquier dispositivo
- Ejemplos prácticos de uso para cada unidad
- Explicaciones detalladas de las características y casos de uso

## 📏 Unidades Visualizadas

El explorador visualiza el comportamiento de:

- **Píxeles (px)**: Unidades absolutas para control preciso
- **EM (em)**: Unidades relativas al tamaño de fuente del elemento padre
- **REM (rem)**: Unidades relativas al tamaño de fuente del elemento raíz
- **Porcentajes (%)**: Unidades relativas a las dimensiones del elemento padre
- **Viewport (vw/vh)**: Unidades relativas a las dimensiones del viewport
- **Fracciones (fr)**: Unidades para distribución de espacio en CSS Grid

## 🚀 Tecnologías Utilizadas

- [Astro](https://astro.build/) - Framework web de alto rendimiento
- HTML, CSS y JavaScript
- Diseño responsivo con CSS moderno
- Visualizaciones interactivas con JavaScript nativo

## 💻 Instalación

Para ejecutar este proyecto localmente:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/hugo510/gitpages_practica.git
   cd Visualizador-de-Medidas-Responsivas
   ```

2. Instala las dependencias:

   ```bash
   npm install
   ```

3. Inicia el servidor de desarrollo:

   ```bash
   npm run dev
   ```

4. Accede a `http://localhost:4321` en tu navegador

## 🖱️ Uso

1. Navega a través de las diferentes secciones mediante el menú de navegación superior
2. Experimenta con los controles deslizantes para modificar valores de cada unidad CSS
3. Observa cómo cambian las visualizaciones en tiempo real
4. Redimensiona tu navegador para ver cómo las diferentes unidades responden a los cambios de tamaño
5. Consulta los ejemplos de código para implementar estas unidades en tus propios proyectos

## 📁 Estructura del Proyecto

```
src/
├── components/       # Componentes reutilizables
│   ├── Header.astro
│   ├── Footer.astro
│   ├── IntroSection.astro
│   ├── UnitSection.astro
│   └── visualizations/  # Visualizaciones interactivas por unidad
│       ├── PixelViz.astro
│       ├── EmViz.astro
│       ├── RemViz.astro
│       ├── PercentageViz.astro
│       ├── ViewportViz.astro
│       └── FrViz.astro
├── layouts/          # Plantillas de página
│   └── Layout.astro
└── pages/            # Páginas de la aplicación
    └── index.astro
```

## 👥 Contribuir

Las contribuciones son bienvenidas. Para contribuir:

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/amazing-feature`)
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir una característica increíble'`)
4. Push a la rama (`git push origin feature/amazing-feature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

Desarrollado con ❤️ por [Hugo](https://github.com/hugo510)
