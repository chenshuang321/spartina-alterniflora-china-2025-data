# *Spartina alterniflora* distribution along the coast of China, 2025

This dataset contains the polygon mapping result associated with the manuscript:

> **Large-scale mapping of *Spartina alterniflora* using Sentinel-2 imagery through probability-map-mediated spectral–spatial decoupling**

## Files

```text
data/
  spartina_alterniflora_china_coast_2025.shp
  spartina_alterniflora_china_coast_2025.shx
  spartina_alterniflora_china_coast_2025.dbf
  spartina_alterniflora_china_coast_2025.prj
  spartina_alterniflora_china_coast_2025.cpg
CITATION.cff
LICENSE.md
metadata.yaml
checksums.sha256
```

All five Shapefile components are required. The accompanying ZIP archive is the recommended download for users who need the Shapefile representation.

## Dataset description

- Feature type: polygon
- Coordinate reference system: WGS 84 geographic coordinates
- Spatial extent: 108.96124221880576°E to 122.36491474162473°E; 21.43838408704079°N to 39.186129660804944°N
- Number of feature records: 12,856
- Attribute field: `value` (integer); `1` denotes mapped *Spartina alterniflora*
- Mapping year: 2025
- Source imagery: Sentinel-2
- Mapping workflow: random-forest probability maps followed by Attention ResU-Net spatial refinement

Area should not be calculated directly in EPSG:4326. Reproject to a suitable equal-area CRS before deriving patch or regional area statistics.

## License

The dataset is released under the Creative Commons Attribution 4.0 International license (CC BY 4.0). See `LICENSE.md`.

## Citation

Use `CITATION.cff`. After Zenodo assigns the data DOI, update the citation metadata and the manuscript's Data and software availability statement.
