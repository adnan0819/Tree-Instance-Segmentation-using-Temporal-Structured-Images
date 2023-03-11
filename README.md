# # Tree Instance Segmentation using Temporal Structured Image (CVPR 2023)

## Dataset contibutions, annotations and supporting material
This repo has all dataset and train/validation annotations for our paper **Tree Instance Segmentation using Temporal Structured Image** in **CVPR 2023**. The annotated frames and data are available in this repository. The full uncompressed UAV flight videos are hyperlinked as they are in the magnitudes of 50 GB. We hope this helps anyone and everyone in computer vision, forestry, or any area of research. 

# Full Uncompressed UAV Videos 

Please visit/download all our uncompressed flight videos (detailed in the table below) hosted on our institutional domain [HERE](http://handlebarsjs.com/).

# Files and Directories

## List of flight paths

* `Waypoint1.kml` - Path over Martell 4D Forest Area in Martell Forest
* `Martell_1962RedOak_LineMission.kml` - Path over Martell 1962 Plantation
* `TentativePathStraightLine.kml` - Secondary path over Martell 4D Area
* Each flight path has autonomous and manual flights (for comprehensive configuration detail like FOV, angles, focal lengths etc. please see the table below)

## List of dataset directories and files

* `./annotated_dataset/` contains the details and link to frames with crowns labeled by forestry collaborators 
* `./datasets/` contains the details and link to videos and frames with crowns annotated 
* `./datasets/video_dataset/` contains the details and link to 24 uncompressed UAV flight videos including some shorter demos (full list is in the table below)
* `./datasets/annotated_dataset/` contains the details and frames with crowns annotated 
* `Flight_List.csv` contains the list of all flight videos including meta data comprising of dates and camera configurations. 


## Annotation Details

All annotations are in Labelme JSON format


# Flight List of UAV Video Dataset Contribution
|Flight Date|Flight Location     |Forest Type|Flight Mission                    |Curved/Straight|Flight Length|Flight Speed         |Altitude|Sensor Angle|Camera Used|FOV  |Aperture|Focal Length|Sensor Size       |
|-----------|--------------------|-----------|----------------------------------|---------------|-------------|---------------------|--------|------------|-----------|-----|--------|------------|------------------|
|4/23/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |60m     |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|4/23/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |80m     |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|4/23/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |100m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|4/23/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |120m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|4/23/22    |Martell Plot 4d     |Natural    |Manual Control                    |Both           |Varied       |Varied (3m/s to 9m/s)|60m     |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|4/23/22    |Martell Plot 4d     |Natural    |Manual Control                    |Both           |Varied       |Varied (3m/s to 9m/s)|80m     |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|4/23/22    |Martell Plot 4d     |Natural    |Manual Control                    |Both           |Varied       |Varied (3m/s to 9m/s)|100m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|4/23/22    |Martell Plot 4d     |Natural    |Manual Control                    |Both           |Varied       |Varied (3m/s to 9m/s)|120m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|5/17/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |80m     |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|5/17/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |120m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|5/24/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |120m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|9/15/22    |Martell 1962 Red Oak|Plantation |Martell_1962RedOak_LineMission.kml|Curved         |210m         |5m/s                 |120m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|9/15/22    |Martell 1962 Red Oak|Plantation |Martell_1962RedOak_LineMission.kml|Straight       |210m         |5m/s                 |120m    |Nadir       |DJI P1     |63.5°|f/2.8   |35mm        |34x19mm, 45MP     |
|9/23/22    |Martell 1962 Red Oak|Plantation |Martell_1962RedOak_LineMission.kml|Curved         |210m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|9/23/22    |Martell 1962 Red Oak|Plantation |Martell_1962RedOak_LineMission.kml|Straight       |210m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|9/23/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|9/23/22    |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Straight       |805m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|9/23/22    |Martell Plot 4d     |Natural    |TentativePathStraightLine.kml     |Straight       |843m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|10/28/22   |Martell 1962 Red Oak|Plantation |Martell_1962RedOak_LineMission.kml|Curved         |210m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|10/28/22   |Martell 1962 Red Oak|Plantation |Martell_1962RedOak_LineMission.kml|Straight       |210m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|10/28/22   |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Curved         |805m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|10/28/22   |Martell Plot 4d     |Natural    |Waypoint1.kml                     |Straight       |805m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|
|10/28/22   |Martell Plot 4d     |Natural    |TentativePathStraightLine.kml     |Straight       |843m         |5m/s                 |120m    |Nadir       |DJI H20T   |82.9°|f/2.8   |24mm        |1/2.3" CMOS, 12 MP|


