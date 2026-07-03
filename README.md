## Overview

This dataset provides the geographic locations and mapped footprint areas of
intertidal and nearshore solar photovoltaic (PV) installations along the coast
of China. Each record corresponds to one PV installation. The dataset was
compiled by the authors through manual visual interpretation of high-resolution
satellite imagery in Google Earth. It is the source data underlying Figure 1b of
the associated manuscript.

## Associated publication

This dataset supports the following manuscript:

Zhang Y., Guo Y., Yang S., Pennings S.C. Green-on-green conflicts between
ecological and energy engineering along China's coast. (Add journal and DOI upon
publication.)

Corresponding author: Yaolin Guo (yaolinguo22@gmail.com)

## File

- File name: `China_coastal_PV_area.xlsx`
- Worksheet: `PV_sites`
- Records: 166 installations
- Missing values: none

## Column definitions

| Column | Description | Type | Units / format |
|---|---|---|---|
| `No.` | Sequential site identifier | integer | 1 to 166 |
| `Province` | Coastal province or region in which the installation is located | text | English name |
| `Longitude` | Longitude of a representative point on the installation | numeric | decimal degrees, WGS84, 4 decimal places |
| `Latitude` | Latitude of a representative point on the installation | numeric | decimal degrees, WGS84, 4 decimal places |
| `Area_ha` | Mapped footprint area of the installation | numeric | hectares (ha), 2 decimal places |

## Data collection and extraction

All installations were identified and measured manually in Google Earth
(Google Earth Pro) by visual interpretation of high-resolution satellite imagery.
No automated classification was used. The procedure was as follows:

1. **Systematic visual survey.** The Chinese coastline was inspected
   systematically, province by province, from north to south. Candidate PV arrays
   on tidal flats and in adjacent nearshore areas were located one site at a time.

2. **Site confirmation.** Each candidate was examined individually and confirmed
   visually as a solar-panel array. Features that can resemble PV arrays in
   imagery, such as aquaculture ponds, salt pans, greenhouses, and inland rooftop
   arrays, were excluded.

3. **Coordinate recording.** For each confirmed installation, a placemark was
   placed on the array in Google Earth and its geographic coordinates (longitude,
   latitude) were recorded.

4. **Area measurement.** The outer boundary of each panel array was traced
   manually as a polygon, and the enclosed area was measured with the built-in
   geodesic area (ruler / measurement) tool in Google Earth and recorded in
   hectares.

Coordinates are reported in the WGS84 geographic coordinate system, which is the
Google Earth default.

## Temporal and spatial coverage

- **Temporal:** the compilation reflects installations that were visible or
  constructed as of 2025, based on the most recent imagery available in Google
  Earth at the time of compilation.
- **Spatial:** coastal provinces and regions of China. The 12 provinces/regions
  represented are Fujian, Guangdong, Guangxi, Hainan, Hebei, Jiangsu, Liaoning,
  Shandong, Shanghai, Taiwan, Tianjin, and Zhejiang.

## Summary statistics

- 166 installations across 12 provinces/regions.
- Longitude range: 108.11 to 122.36 degrees E.
- Latitude range: 18.52 to 40.07 degrees N.
- Footprint area: 0.91 to 4833.00 ha (median 105.00 ha).
- Total mapped footprint of the 166 installations: approximately 39,369 ha.

## Notes and limitations

- `Longitude` and `Latitude` give a representative point located on each
  installation; they are not precise geometric centroids.
- `Area_ha` values are manual estimates derived from visual delineation and carry
  interpretation and imagery-date uncertainty. Boundaries of very large or
  fragmented arrays are approximate.
- The inventory reflects imagery available at the time of compilation and may omit
  very recent, very small, partially obscured, or under-construction
  installations.
- The reported precision (coordinates to 4 decimal places, about 10 m; area to 2
  decimal places) reflects reporting precision, not measurement accuracy.

## License

To be set on deposit (for example, CC BY 4.0).
