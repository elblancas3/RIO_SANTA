# Río Vivo · Geovisor

Atlas interactivo de biodiversidad y cobertura territorial del corredor ripario del Río Santa Catarina, ZMM.

## Publicar en GitHub Pages

### 1. Crear repositorio
```bash
git init
git add .
git commit -m "init: geovisor río vivo"
```

### 2. Subir a GitHub
```bash
# Crear repo en github.com, luego:
git remote add origin https://github.com/TU_USUARIO/riovivo-geovisor.git
git branch -M main
git push -u origin main
```

### 3. Activar GitHub Pages
- Ir a **Settings → Pages**
- Source: **Deploy from branch → main → / (root)**
- Guardar

En ~2 minutos estará en: `https://TU_USUARIO.github.io/riovivo-geovisor`

## Estructura de archivos
```
riovivo-geovisor/
├── index.html          ← Geovisor principal
├── rsc_web.geojson     ← Cobertura de suelo (18 categorías, ~1.8MB)
├── biod_points.json    ← Observaciones biodiversidad (~680KB)
└── README.md
```

## Datos
- **RSC 2024**: 6,733 polígonos originales disueltos en 18 categorías de cobertura, reproyectados de UTM14N a WGS84
- **Biodiversidad**: 3,851 observaciones de iNaturalist, 703 especies, 102 amenazadas

## Créditos
Río Vivo RSC 2024 · Geomática MX · iNaturalist
