Context:
This dataset contains tree observations from four areas of the Roosevelt National Forest in Colorado. All observations are cartographic variables (no remote sensing) from 30 meter x 30 meter sections of forest. There are over half a million measurements total!

Content:
This dataset includes information on tree type, shadow coverage, distance to nearby landmarks (roads etcetera), soil type, and local topography. And the Project objective is to build a model that predicts what types of trees grow in an area based on the surrounding characteristics

Acknowledgement:
This dataset is part of the UCI Machine Learning Repository, and the original source can be found here. The original database owners are Jock A. Blackard, Dr. Denis J. Dean, and Dr. Charles W. Anderson of the Remote Sensing and GIS Program at Colorado State University.

Data_Dictionary

Elevation = Elevation in meters.         
Aspect = Aspect in degrees azimuth.                 
Slope = Slope in degrees.                                
Horizontal_Distance_To_Hydrology = Horizontal distance to nearest surface water features.                  
Vertical_Distance_To_Hydrology = Vertical distance to nearest surface water features.                 
Horizontal_Distance_To_Roadways = Horizontal distance to nearest roadway.                   
Hillshade_9am = Hill shade index at 9am, summer solstice. Value out of 255.                  
Hillshade_Noon = Hill shade index at noon, summer solstice. Value out of 255.                  
Hillshade_3pm = Hill shade index at 3pm, summer solstice. Value out of 255.                  
Horizontal_Distance_To_Fire_Point = sHorizontal distance to nearest wildfire ignition points.                 
Wilderness_Area1 = Rawah Wilderness Area                   
Wilderness_Area2 = Neota Wilderness Area                
Wilderness_Area3 = Comanche Peak Wilderness Area           
Wilderness_Area4 = Cache la Poudre Wilderness Area                    
Soil_Type1 to Soil_Type39         

Cover_Type - Forest Cover Type designation(Target Variable), with the following key:

Spruce/Fir                   
Lodgepole Pine                          
Ponderosa Pine               
Cottonwood/Willow              
Aspen                   
Douglas-fir                   
Krummholz     

##### Reference: https://www.kaggle.com/uciml/forest-cover-type-dataset
