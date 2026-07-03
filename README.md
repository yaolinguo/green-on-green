## Overview

This dataset provides the geographic locations and mapped footprint areas of
intertidal and nearshore solar photovoltaic (PV) installations along the coast
of China. Each record corresponds to one PV installation. The dataset was
compiled by the authors through manual visual interpretation of high-resolution
satellite imagery in Google Earth.

## Associated publication

This dataset supports the following manuscript:

Youzheng Zhang, Yaolin Guo, Sen Yang, Steven C. Pennings. Green-on-green conflicts between ecological and energy engineering along China's coast.

*Communications Sustainability*

Corresponding author: Yaolin Guo (yaolinguo22@gmail.com)

## File

- File name: `Raw data - 0703.xlsx`

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
