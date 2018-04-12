# Projects

## Sports Video Summarization Based On Audience Reaction

[Code](https://github.com/DebasmitaGhose/Highlight-Detection-in-Sports-Videos-using-Audience-Reaction/blob/master/action.py) | [Report](https://github.com/DebasmitaGhose/Highlight-Detection-in-Sports-Videos-using-Audience-Reaction/blob/master/automated-sports-highlight.pdf) | [Video](https://www.youtube.com/watch?v=y4Wt10KcIe8&feature=youtu.be)


Highlights in a sports video are the key exciting moments in the match which attract attention of the spectators in the match. A considerable amount effort is spent in extracting such highlights from the match requiring a lot of investment in terms of time and cost where the domain experts decide which frames must be included in the highlight, thus making it an expensive process, so there should be ways of generating automated highlights. We use audience reactions to classify frames in the game as ”highlights” and ”standard play”, because this method can be generalized to detect highlights in any sport. For this purpose, we have used the S-HOCK dataset which contains videos of spectators watching an ice-hockey match. In order to do so, we experiment
with different methods to generate automatic highlights, using
3D Convolutional networks, HOG-SVM and pre-trained
models on similar sports datasets. We obtained an accuracy of 26% using HOG-SVM,
67% using pre-trained models and 74% using 3D-CNN.

Link to the Dataset: [S-HOCK Dataset](http://vips.sci.univr.it/dataset/shock/)

## Determining the Mode of Transportation using Mobile Phones

[Code](https://github.com/DebasmitaGhose/TransportModeDetection/blob/master/Code-GeoLife%2BOwnData.py) | [Report](https://github.com/DebasmitaGhose/TransportModeDetection/blob/master/Final%20Report%20Format-2017%20-%20Debasmita%20Ghose%20-1.pdf)

The public transportation system is a crucial part of the solution to the nation’s economic, energy and environmental challenges. This transportation system can be made more efficient, by studying the mobility of the users, from the sensor data collected by them. The current project have been developed to compare two methods of identifying the mode of transportation being used by a person using the location data collected from one’s cell phone. 
The transportation modes, such as walking, driving, etc., that a user takes, can enrich the user’s mobility with informative knowledge and provide pervasive computing systems with more context information.  
The raw data is time sequenced location data retrieved from the GPS in the cell phones of the users. This data was pre-processed in order to extract relevant features like velocity, acceleration and heading change and to filter out datasets with huge gaps and redundancy. A change point segmentation algorithm was applied where, the data was first broken down into segments using a loose bound of velocity and acceleration, segments smaller than a certain threshold were merged into the backward segment and consecutive segments of length smaller than another threshold were merged to form one segment was implemented using a Python Script. For every segment retrieved from the change point segmentation algorithm, the average velocity, the average acceleration and the average heading change has been calculated, and have been used as a feature for classification. The current work, uses selected trajectories of the GeoLife dataset, to train a decision tree based model, and uses GPS trajectory data collected from a user taking multimodal trips across Singapore, in order to test the model, using a Python script. 
A comparative study of the two algorithms i.e. Decision Tree and Random Forest was performed on some trajectories of the GeoLife Dataset  and the Random Forest algorithm was found to be more accurate than the Decision Tree algorithm with an overall accuracy of 81.2%.
Therefore, the change point segmentation and classification algorithms are highly suited to build a solution to the problem of discerning between motorised and non-motorised modes of transport, using a series of time-stamped GPS locations. In the real world, this project can not only help the land transport authorities make the public transportation system more efficient, but can also help the police in law enforcement, if a system which collects real time GPS logs of people is put in place. 
In order to achieve these results, Weka Machine Learning Toolkit, ArcGIS, MS Excel and Scikit Learn Library of Python is being used.

Link to the Dataset: [GeoLife Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=52367&from=https%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fdownloads%2Fb16d359d-d164-469e-9fd4-daa38f2b2e13%2F)

## Drone Assisted Parking System

[Report](https://github.com/DebasmitaGhose/Projects/blob/master/Final%20Report%20Drone%20(Recovered).pdf)

The aim of this project was to develop a system that can assist drivers in finding a suitable parking spot in an open parking lot and can help him assess the traffic conditions on the road ahead of him. For this, I proposed an idea of developing a drone, which can take off and land from a moving car at the discretion of the driver, and send live video feed to the driver. The drone should identify the right car while landing and the battery used for the drone should be charged wirelessly from the car.

In a period of 3 months, I was able to successfully build an octocopter using the Pixhawk V4 flight controller. The drone has a flight time of about 20 min at the current weight and has a maximum payload capacity of 8kg. The drone is capable of taking off and landing autonomously from a surface and is GPS enabled. All the safety features provided by the Pixhawk V4 controller are enabled and tested. I have also designed a suitable landing gear for the drone using Plexi Glass. I also designed a circuit for a wireless charger for a single cell Lithium Polymer battery using EAGLE CAD.

This was done as an individual project as a part of an internship at the School of Vehicle
Mechatronics, Techniche Universitat, Dresden, Germany

## Road Accident Prevention System

[Paper](https://github.com/DebasmitaGhose/Projects/blob/master/Cost%20Effective%20Road%20Accident%20Prevention%20System.pdf)

The aim of this project was to develop a system that can minimize road accidents. Our team
of 3 designed a system that chalks out the major causes of road accidents and attempts to
prevent them. The system has a driver drowsiness detection system, to check the state of
the driver. This uses the Intel Real Sense camera to measure the percentage closure of
eyes and to detect if the person is yawning. This is connected to the Intel NUC, which alerts
the driver using audio stimulus, if he is found to be drowsy.

It also detects if the driver is under the influence of alcohol and if he has fastened the seat
belt. The sensors for these are connected to the Atmel SAM D21 microcontroller which is in
turn connected to the Intel NUC. If the driver is found to violate any rules, the NUC alerts the
driver. The system also checks if the driver is tailgating or if somebody is tailgating from
behind. If the driver is found to be tailgating repeatedly, the driver is warned and if needed,
the details of the car are sent to the nearest police station using Wi-Fi for further action.

My role in this project was to realise face detection and eye detection using the Intel Real
Sense camera and to integrate all the modules of the project using a C# program running
on the Intel NUC.

Our team of 3 was selected among the top 10 teams of Atmel Embedded Design Challenge
2014 for this project. A research paper on this project has been selected for the 2nd
International Conference on Contemporary Computing and Informatics, 2016.
