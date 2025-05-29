# Drone-Data-Visualisation
🚀 Project Workflow: Drone Data Visualization
This project involves capturing aerial data using drones and visualizing it through various geospatial and 3D modeling techniques.

📸 1. Drone Data Collection
Use UAVs equipped with RGB, LiDAR, thermal, or multispectral sensors.
Plan flight paths with 70–80% image overlap.
Collect high-resolution images/videos of the target area.

![Aligning image](https://github.com/user-attachments/assets/d8d2b1b0-3911-4c75-b537-69988bb7cc0f)

🖥️ 2. Image Processing (Using Agisoft Metashape)
Import Images: Load drone-captured images into the software.
Align Photos: Generate sparse point cloud using Structure from Motion (SfM).
Build Dense Cloud: Create a detailed point cloud.

![constructing image and texturing](https://github.com/user-attachments/assets/01d18764-3794-4e02-b24a-83f27efd81af)

Generate DEM & Orthomosaic:
Create Digital Elevation Model (DEM).

![Screenshot 2025-05-04 202200](https://github.com/user-attachments/assets/616c3deb-7307-4776-a87f-c0c0171dd480)

Build and export orthomosaic (GeoTIFF format).

🌍 3. Digitization and GIS Analysis (Using QGIS)
Load Orthomosaic: Add the GeoTIFF file to a new QGIS project.
Create Vector Layers: Define shapefiles for points, lines, and polygons.
Digitize Features: Mark trees, roads, buildings, etc.
Enable Snapping: Improve accuracy of digitization.
Calculate Attributes: Use field calculator for area/length.

![Screenshot 2025-05-08 233255](https://github.com/user-attachments/assets/ca106bad-6dbe-47dc-baf9-9c551542dc91)

📊 4. Data Visualization Techniques
Orthomosaic Mapping – 2D map visualization.
Point Cloud Visualization – 3D data point rendering.
NDVI Analysis – Evaluate vegetation health.
Thermal Imaging – Detect temperature anomalies.
Volumetric Visualization – Calculate stockpile volumes.

![Screenshot 2025-05-04 002444](https://github.com/user-attachments/assets/9b4778e5-11ca-426e-8063-0cfe3dd289fc)


📤 5. Export & Share
Export layers in Shapefile, GeoJSON, or CSV format.

Share orthomosaics and models through interactive web viewers (e.g., CesiumJS, Potree).





