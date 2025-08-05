[![🛠️ Build map](https://github.com/azagramac/OSMforGarmin/actions/workflows/workflow-spain.yaml/badge.svg)](https://github.com/azagramac/OSMforGarmin/actions/workflows/workflow-spain.yaml)

# 🛰️ Garmin Map Builder – OpenStreetMap
<a href="https://wiki.openstreetmap.org/wiki/Mkgmap" target="_blank" rel="noopener noreferrer"> <img width="92" height="92" alt="OpenStreetMap Logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/Openstreetmap_logo.svg/100px-Openstreetmap_logo.svg.png" /> </a>

Compilación de mapas .img compatibles con dispositivos Garmin eTrex 22x / 30x / 32x y similares, usando datos oficiales de OpenStreetMap.

---

## 🚀 Características

- ✅ Generación automática del fichero `*-gmapsupp.img` de diferentes regiones, España Peninsular, Islas Canarias e Islas Baleares de [Geofabrik](https://download.geofabrik.de/europe/spain.html).

---

## 📂 Archivo generado

- `peninsula-gmapsupp.img`: Mapa principal con la región España 🇪🇸 (península).
- `canarias-gmapsupp.img`: Mapa con la región 🇮🇨 Islas Canarias.
- `baleares-gmapsupp.img`: Mapa con la región 🏝️ Islas Baleares.

---

## 📦 Instalación
💽 En memoria interna Garmin

- Conecta el dispositivo Garmin por USB.
- Renombra `*-gmapsupp.img` correspondiente a `gmapsupp.img`.
- Copia `gmapsupp.img` dentro de la carpeta `Garmin`.

💾 En tarjeta SD externa (recomendada para múltiples mapas)

- Inserta la tarjeta SD (formateada en `FAT32`, máximo 32GB).
- Crea la carpeta `Garmin` en la raíz.
- Copia el fichero `*-gmapsupp.img` (puedes renombrar para tener varios mapas simultáneos, ej.: `peninsula-gmapsupp.img`, `baleares-gmapsupp.img`, `canarias-gmapsupp.img`, ...) dentro de la carpeta `Garmin`.

> ⚠️ Nota: En memoria interna del dispositivo solo se reconoce un archivo .img llamado `gmapsupp.img`
> En tarjeta SD puedes tener varios mapas con diferentes nombres.

### ⚙️ Activación del mapa en el dispositivo Garmin

- Navega a: Setup > Map > Select Map y activa el mapa nuevo.

---

## 🧪 Environment

- ☕ Java 17
- 📦 [mkgmap](https://www.mkgmap.org.uk/download/mkgmap.html) `r4923`
- 🔀 [splitter](https://www.mkgmap.org.uk/download/splitter.html) `r654`
- 🗺️ Datos OSM de [Geofabrik](https://download.geofabrik.de/)

---

## 🌐 Mapas ya compilados en .img

- [userbeam](https://www.userbeam.de/osm/maps/europe/spain/)
- [alternativaslibres](https://alternativaslibres.org/es/downloads.php)
- [wanderreitkarte](https://www.wanderreitkarte.de/garmin_de.php)
