# Urban Parks Explorer

## Project Overview
The Urban Parks Explorer is an innovative project designed to leverage spatial computing, OpenStreetMap data, and augmented reality (AR) to enhance the exploration and appreciation of urban green spaces. By integrating detailed geographic information, Elasticsearch for efficient data querying, and AR for immersive experiences, this project aims to provide users with unique insights into their city's parks.

## Features
- **Interactive Maps**: Utilizing OpenStreetMap data to visualize urban parks and green spaces within a specified city or neighborhood.
- **Search Functionality**: Elasticsearch backend to quickly search and filter parks based on user criteria such as location, size, and amenities.
- **Augmented Reality Experience**: An AR app component that overlays digital information about parks onto the real-world environment, enriching the user's exploration experience.

## Trends Observed
Throughout the development and analysis phase of the project, several interesting trends and observations were made regarding urban parks:
- **Concentration in Manhattan**: A significant concentration of parks was observed in Manhattan compared to other boroughs such as Brooklyn, Queens, and areas outside of New York City, indicating potential disparities in green space distribution.
- **Park Types**: The majority of parks analyzed were categorized as "multipolygon," suggesting complex shapes and potentially diverse uses within urban environments.
- **Geographic Disparities**: The distribution of parks across different areas highlighted geographic disparities in access to green spaces, raising questions about urban planning and social equity.

## Potential Areas for Further Investigation
- **Accessibility and Social Equity**: Further analysis could investigate the correlation between park accessibility and various demographic factors to address social equity concerns.
- **Impact on Community Health**: Exploring the relationship between the availability of green spaces and community health outcomes could provide valuable insights for public health initiatives.
- **Urban Heat Island Effect**: Examining the role of parks in mitigating the urban heat island effect could inform urban planning and sustainability efforts.

## Technologies Used
- **OpenStreetMap**: For extracting detailed geographic data on urban parks.
- **Elasticsearch**: To index and query park data efficiently.
- **ARKit/ARCore/Unity**: For developing the augmented reality experience.
- **Folium/Leaflet**: For interactive web map visualizations.

## Getting Started
1. **Setup Elasticsearch**: Ensure you have an Elasticsearch cluster set up and index the processed OpenStreetMap data.
2. **Data Preparation**: Use the Overpass API to extract and process park data from OpenStreetMap.
3. **AR App Development**: Choose an AR development kit and start building the AR experience based on the project objectives.
4. **Web Mapping**: Implement interactive maps using Folium or Leaflet for web-based exploration.

## Contributing
We welcome contributions from the community, whether it's in the form of feature suggestions, bug reports, or pull requests. Please refer to the CONTRIBUTING.md file for more information.

## License
This project is licensed under the [MIT License](LICENSE).

