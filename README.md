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

