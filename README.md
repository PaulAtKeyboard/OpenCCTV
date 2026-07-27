# OpenCCTV
A basic Web GIS of the CCTV network owned by Auckland Transport (AT) in Auckland, New Zealand.

## Usage
View the map [here](https://cctv.scienceplus.art/) or download this repository and open `index.html` in a browser. The map data is bundled locally in `data.js`, so no network fetch of the dataset is required (map tiles still need an internet connection).

## Data
AT have made their locations of CCTV Network publicly available. Said information was found on a Radio New Zealand article.
We believe such information was released under Local Government Official Information and Meetings Act (LGOIMA) 1987 request.

The dataset is a snapshot from **August 2019** and has not been updated since — AT's camera network has likely changed. 1,817 de-duplicated camera locations (the original release contained ~925 exact duplicate rows) are provided in three formats: `data-AT-CCTV.csv`, `data-AT-CCTV.json`, and `data-AT-CCTV.geojson`.

### CCTV Specification
Any information regarding brand, model, license plate recognition, facial recognition, and camera view bearing information were not released by AT on the PDF document which this Project is based on.

### Related News Articles & Additional Information
* [CCTV-LGOIMA-CCTV-Locations.pdf](https://assets.documentcloud.org/documents/6253935/CCTV-LGOIMA-CCTV-Locations.pdf)
* [Auckland Transport's $4.5m plan could mean 8000 cameras watching the city](https://www.rnz.co.nz/news/national/396465/auckland-transport-s-4-point-5m-plan-could-mean-8000-cameras-watching-the-city)

### Speed Camera Data
`data-speed-cameras-auckland.csv` is a separate, unrelated dataset listing Auckland Transport speed camera zones (street, locality, zone start/end coordinates, and go-live date). It is not CCTV data and is not plotted on the live map, but is kept here for reference since it was sourced from the same LGOIMA release process.

## Built with
* [Leaflet](https://leafletjs.com)
* [JavaScript](https://www.javascript.com/)
* [JSON](https://www.json.org/)
* [Open Street Map](https://www.openstreetmap.org/)

## Project Status
Currently a Minimum Viable Product.

## Disclaimer
### This Project is just for fun.
* AUTHORS MAKE NO GUARANTEE OF VALIDITY
* PLEASE BE AWARE THAT ANY INFORMATION YOU MAY FIND MAY BE INACCURATE, MISLEADING, DANGEROUS, ADDICTIVE, UNETHICAL.
* DO NOT RELY UPON ANY INFORMATION FOUND WITHOUT INDEPENDENT VERIFICATION.
* Information on this website has been derived from various sources.
* All information should be considered as being illustrative and indicative only. Your use of information from this website is entirely at your own risk.
* Authors does not give and expressly disclaims any warranty as to the accuracy or completeness of the information or its fitness for any purpose.
* Auckland Council accepts no liability for any error, omission, or inaccuracy of the information or from any use of or reliance on the information provided.
* You should independently verify the accuracy of any information before taking any action in reliance upon it.
* You waive and release Authors of this Project from any claims arising from your use of this website or the information provided by it.
* You indemnify Authors of this Project against all claims, loss or damages arising in connection with your use of the information provided.
* Information from this Project may not be used for the purposes of any legal disputes.

Created and maintained by Paul and Omi
