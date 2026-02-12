# Reporte Turístico Chihuahua 2025 | Descuubre + Bankaool

## Descripción del Proyecto

Dashboard interactivo de análisis turístico para el estado de Chihuahua, México. Presenta datos estratégicos del sector turístico 2025 a través de tres niveles de visualización: Nacional, Estatal y Municipal.

## Características Principales

- **Vista Nacional**: Contexto macroeconómico de México (divisas, ocupación hotelera, flujo de pasajeros)
- **Vista Estatal**: Perfil detallado del visitante en Chihuahua (sectores económicos, motivos de viaje)
- **Vista Municipal**: Ranking interactivo de 40 municipios clave (98% de la actividad turística total)
- **Buscador Inteligente**: Filtrado dinámico de municipios
- **Fichas Detalladas**: Indicadores anualizados por municipio (turistas, derrama económica, ocupación, estadía)

## Tecnologías Utilizadas

- **HTML5** + **CSS3** + **JavaScript Vanilla**
- **Tailwind CSS** (vía CDN) - Framework de utilidades CSS
- **Lucide Icons** - Sistema de iconos modernos
- **Google Fonts** (Inter) - Tipografía profesional
- **Chart.js** - Librería de gráficos (preparado para futuras visualizaciones)

## Estructura del Proyecto

```
webapp/
├── index.html       # Aplicación web de página única (SPA)
├── README.md        # Documentación del proyecto
└── .gitignore       # Archivos excluidos del control de versiones
```

## Uso

### Visualización Local

Simplemente abre el archivo `index.html` en cualquier navegador web moderno:

```bash
# Opción 1: Abrir directamente
open index.html

# Opción 2: Servidor local con Python
python3 -m http.server 8000

# Opción 3: Servidor local con Node.js
npx serve .
```

### Navegación

1. **Header**: Utiliza los botones de navegación (Nacional / Estatal / Municipios)
2. **Footer Flotante**: Acceso rápido a las tres vistas principales
3. **Vista Municipios**: 
   - Usa el buscador para filtrar municipios
   - Haz clic en cualquier municipio del ranking para ver sus detalles
   - Los indicadores se muestran en tarjetas interactivas

## Fuentes de Datos

- **Nacional**: DATATUR (Análisis Integral de Datos Turísticos)
- **Estatal**: SICHITUR (Sistema de Información Turística de Chihuahua)
- **Municipal**: Reporte de Indicadores SICHITUR 2025

**Nota**: Los 40 municipios representados concentran más del 98% de la actividad turística total del estado.

## Paleta de Colores (Branding Bankaool + Descuubre)

- **Primary (Descuubre)**: `#ff5d37` (Naranja vibrante)
- **Secondary (Bankaool)**: `#105b46` (Verde institucional)
- **Blue**: `#4b6db5` (Azul corporativo)
- **Gold**: `#f0a748` (Dorado destacado)

## Características Técnicas

- ✅ **Responsive Design**: Adaptable a móvil, tablet y desktop
- ✅ **Sin dependencias de backend**: 100% frontend estático
- ✅ **Rendimiento optimizado**: Carga de recursos vía CDN
- ✅ **UX mejorada**: Animaciones suaves, transiciones fluidas
- ✅ **Accesibilidad**: Estructura semántica HTML5

## Estado del Proyecto

- **Versión**: 1.0.0
- **Última Actualización**: Febrero 2026
- **Estado**: ✅ Activo y funcional

## Próximos Pasos Recomendados

1. **Despliegue**: Publicar en Cloudflare Pages, GitHub Pages o Netlify
2. **Visualizaciones**: Activar gráficos con Chart.js (tendencias temporales, comparativas)
3. **Exportación**: Añadir funcionalidad para exportar datos en PDF/Excel
4. **Integración API**: Conectar con fuentes de datos en tiempo real (SICHITUR API)
5. **Analytics**: Implementar Google Analytics o Plausible para tracking de uso

## Autor

Desarrollado como parte de la estrategia digital **Bankaool** en colaboración con **Descuubre Chihuahua**.

## Licencia

Uso interno y estratégico. Todos los derechos reservados © 2025.
