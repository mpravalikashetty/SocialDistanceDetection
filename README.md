# Social-distance-detection
The ongoing COVID-19 corona virus outbreak has caused a global disaster with its deadly spreading. Due to the absence of effective remedial agents and the shortage of immunizations against the virus, population vulnerability increases. In the current situation, as there are no vaccines available; therefore, social distancing is thought to be an adequate precaution (norm) against the spread of the pandemic virus. The risks of virus spread can be minimized by avoiding physical contact among people. The purpose of this work is, therefore, to provide a deep learning platform for social distance tracking using an overhead perspective. The framework uses the YOLOv3 object recognition paradigm to identify humans in video sequences. The transfer learning methodology is also implemented to increase the accuracy of the model. In this way, the detection algorithm uses a pre-trained algorithm that is connected to an extra trained layer using an overhead human data set. The detection model identifies peoples using detected bounding box information. Using the Euclidean distance, the detected bounding box centroid's pairwise distances of people are determined. To estimate social distance violations between people, we used an approximation of physical distance to pixel and set a threshold. A violation threshold is established to evaluate whether or not the distance value breaches the minimum social distance threshold. In addition, a tracking algorithm is used to detect individuals in video sequences such that the person who violates/crosses the social distance threshold is also being tracked. Experiments are carried out on different video sequences to test the efficiency of the model. Findings indicate that the developed framework successfully distinguishes individuals who walk too near and breaches/violates social distances; also, the transfer learning approach boosts the overall efficiency of the model. The accuracy of 92% and 98% achieved by the detection model without and with transfer learning, respectively. The tracking accuracy of the model is 95%.

Keywords: Deep learning, Social distancing, COVID-19, Transfer learning, Overhead view, Person detection, YOLOv3
# Now Let's start The Project

#### Github usually doesn't support files larger than 25 Mb.You can find the yolo weights in [My google drive](https://drive.google.com/file/d/1QrGGrZl-K2z9IH410o9oeGvbKdIDjGIS/view?usp=sharing) 
* Download it & move to yolo-coco folder

# For CPU:

## To run this code in your terminal:
* ***Open your terminal**
* ***Change directory to where you have downloaded this code***
* ***Install python3 if you have not, if installed already then it's ok!***
* **Run**  `  python3 -m venv venv  ` ***to create a virtual environment named venv.***
* **Run**   `  source venv/bin/activate  ` 
***to activate your environment!***
* **Write**   `  pip install -r requirements.txt  ` 
***to install the python dependencies related to this project like opencv,numpy,scipy etc.***
* **Run the command** `time python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1
` ***to run your social distance detection project***

#### After you run the last line of command,a window eill pop up and after execution of the file a `output.avi` file will be showing up in your directory like this:
![Output avi gif](https://github.com/abd-shoumik/Social-distance-detection/blob/master/social%20distance%20detection.gif)

# For GPU:
You can find my google colab file here. [Social distance detector colab](https://colab.research.google.com/drive/13IzdPCsAo4L613cmBEmrtM-NgSvMukb-?usp=sharing)

## Contacts:
* **Created by:[M Pravalika](https://github.com/mpravalikashetty)**
* **Email:[abd.shoumik@gmail.com](https://mpravalikashetty@gmail.com)**
* **LinkedIn: [Pravalika M](https://www.linkedin.com/in/itsmepravalikam)**
