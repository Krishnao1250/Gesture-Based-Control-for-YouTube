# Gesture-Based-Control-for-YouTube
Summary: Developed a Python-based gesture recognition system using mediapipe to control YouTube playback. Hand landmarks were detected in real-time, enabling gestures for pause, play, and speed adjustment. Implemented data logging to store landmarks, gestures, and timestamps in a CSV file for analysis.

A project called GestureTube aims to improve YouTube’s user experience by incorporating gesture-based controls. Users are constantly looking for fresh ways to engage with YouTube due to its rising popularity. Users may navigate through videos, change the volume, and carry out other actions on YouTube with the help of gesture-based controls rather than using physical buttons or voice instructions.
In this research, user gestures are detected and recognized using computer vision and machine learning Techniques. The system uses a webcam to record photos of the user’s hand movements, and computer vision techniques are then used to process the images to find and identify the gestures. The actions in YouTube that correspond to the identified movements are play, pause, skip, and rewind. Regardless of physical limitations, anyone can use the GestureTube system because it is simple to operate. Users can operate YouTube without a keyboard or mouse thanks to GestureTube, which does away with the requirement for physical buttons or voice commands. Users are able to set their own motions and actions thanks to the system’s customization features. GestureTube is an original method of controlling YouTube that has the ability to enhance the platform’s user interface and make it more user-friendly and open to all users.
The input data must be cleaned up as part of the preparation procedures in Mediapipe hand landmark recognition before being fed into the neural network for inference. Using a camera or another imaging equipment, the input data is extracted from the video feed or image source. Evaluation can be done using the proportion of gestures that were accurately categorized. Accuracy can be calculated as the proportion of correctly classified gestures to all gestures in the dataset. Among all positive classifications, the proportion of real positive classifications. Precision can be calculated as the proportion of true positive classifications to all positive classifications. 
The proportion of authentically positive categorization out of all authentic gestures. Recall can be calculated as the proportion of true positive classifications to all true gestures. Overall, we can learn more about the system’s performance and pinpoint areas for development by assessing the gesture detection system using the dataset gathered using the Mediapipe framework. The accuracy and robustness of the gesture detection system can be enhanced by tweaking the system and adding further capabilities, making it more advantageous for controlling programs like YouTube video players.
Using the preprocessed data, a machine learning model will be trained to identify various hand gestures Given their effectiveness in picture identification tasks, deep learning methods like convolutional neural networks (CNNs) will be investigated for this purpose.
During the course of this project, the system will be trained to identify the four hand motions play, pause, speed at 1x, and speed at 2x. An assortment of training data is gathered for every motion, including demonstrations of the gesture in action. The system then examines this data to determine which hand landmarks are crucial for correctly identifying each move. The system has been trained to recognize a hand signal that features four fingers outstretched and a thumb drawn back toward the wrist as the ”play” gesture. The system has been trained to recognize a hand signal that features all five fingers outstretched and drawn back toward the wrist as the ”pause” motion.
The system has been trained to recognize a hand signal that features the thumb, fingernail, and middle finger extended as the ”speed at 1x” gesture. The system has been trained to recognize a hand gesture in which the thumb and fingernail are extended as the ”speed at 2x” motion. When watching YouTube videos, the system may be used to recognize these motions in real-time once it has been educated on them.
Gestures will be translated into specific YouTube actions, such as play, pause, skip, or rewind, once they have been identified. Using the YouTube video player, you may employ the following strategy to recognize hand gestures like play, pause, speed 1x, and speed 2x. Using a webcam or another video input device to record the video feed. Track the location of the hand in each frame of the video using the Mediapipe Hand Landmarks model. Once the hand landmarks have been found, you can identify particular hand motions using a machine learning model or rule-based approach. For instance, you can search for a certain hand configuration (such as an open palm with fingers spread wide) or motion pattern to identify a play gesture. To identify pause, speed 1x, and speed 2x gestures, you can define hand configurations and motion patterns. Once a gesture is identified, you may give the YouTube video player the appropriate command to change the playback speed or pause/play the video. With further machine learning or rule-based systems, you may utilize these hand movements to recognize particular motions and operate a YouTube video player Overall, the Mediapipe Hand Landmarks model offers a strong tool for recognizing and tracking hand movements in real-time video.
