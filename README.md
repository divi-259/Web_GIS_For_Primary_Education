# Web_GIS_For_Primary_Education
This work is about the practical implementation of an Open Source web GIS Application using open source application software
## Overview
This project is a **Web GIS (Geographic Information System) Application** developed as part of my MTech thesis. The primary objective of this project was to map and visualize spatial data using a **PostGIS database**. While the website's UI is functional, the primary focus of the project was on backend data management and mapping capabilities.

## Features
- **Spatial Data Mapping**: Displays geographic and demographic data, such as student and teacher distribution, facilities, and resources.
- **Interactive Navigation**: Organized information for different categories like OBC, SC, and ST students, as well as staff and facilities.
- **PostGIS Integration**: Utilized **PostGIS**, a spatial database extender for PostgreSQL, to store and query spatial data efficiently.
- **Dynamic Image Gallery**: A gallery showcasing various mapping visualizations and graphs.

## Core Objectives
1. **Data Mapping**:
   - Visualize and present demographic and spatial data effectively.
   - Provide users with an easy-to-navigate interface to explore the mapped data.
2. **Database Design**:
   - Use **PostGIS** to handle geographic data types and perform spatial queries.
   - Leverage the power of spatial indexing for performance optimization.
3. **Research Contribution**:
   - Aimed to showcase how Web GIS can be utilized to represent institutional data, making it accessible and actionable.

## Technologies Used
- **Database**: PostgreSQL with PostGIS extension.
- **Frontend**: HTML, CSS, JavaScript.
- **Backend Mapping**: Spatial data processed and queried using PostGIS.
- **Tools for Mapping**: QGIS for generating visualizations used in the application.

## Project Structure
- **`index.html`**: The homepage providing an overview of the application.
- **`gallery.html`**: A gallery showcasing maps and visualizations of various datasets.
- **`about.html`**: A brief description of the application and its purpose.
- **`contact.html`**: Contact information for further queries.
- **Styles**: Custom CSS for basic styling and layout of the application.

## Data Visualization
- **Student Demographics**:
  - Data categorized by caste (OBC, SC, ST) and gender.
  - Visualized for two different academic years.
- **Teacher Demographics**:
  - Gender-based categorization for teaching staff.
- **Facility Data**:
  - Availability of facilities such as electricity, water, toilets, and computers.

## Challenges Addressed
- Designing efficient queries for spatial data using **PostGIS**.
- Handling large datasets while ensuring smooth performance.
- Mapping multiple datasets to create meaningful visualizations.


