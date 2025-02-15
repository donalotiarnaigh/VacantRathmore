# Visibly Vacant Properties - Rathmore

An interactive web map showing vacant and derelict properties in Rathmore, County Kerry. This survey was conducted in February 2025 to identify potential properties for renovation and reuse.

## Features

- Interactive map interface built with Leaflet.js
- Property information including:
  - Location details
  - Former use
  - Building type
  - Number of storeys
  - Current condition
  - Property photos
- Mobile-responsive design
- Accessibility features for screen readers
- Layer controls for map customization

## Technology Stack

- Leaflet.js for map rendering
- OpenStreetMap as the base layer
- QGIS for initial data processing
- Modern HTML5 and CSS3
- Vanilla JavaScript

## Local Development

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/donalotiarnaigh/VacantRathmore.git
```

2. Navigate to the project directory:
```bash
cd VacantRathmore
```

3. Serve the files using a local web server. For example, using Python:
```bash
# Python 3
python -m http.server 8000
```

4. Open your browser and visit `http://localhost:8000`

## Live Demo

Visit the live map at: [Visibly Vacant Properties - Rathmore](https://donalotiarnaigh.github.io/VacantRathmore/)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenStreetMap contributors for the base map data
- QGIS and qgis2web for the initial map export
- Leaflet.js for the mapping library