## PyFaceCrop
A PyFaceCrop library has been developed to streamline the process of cropping faces from videos while disregarding irrelevant frames. This library offers a convenient solution for extracting facial features from video data efficiently. By leveraging advanced computer vision techniques, it identifies and isolates faces within the video frames, providing a cropped output focused solely on facial content. This tool significantly simplifies the task of processing video data for applications such as facial recognition, emotion detection, and content analysis. With its user-friendly interface and robust functionality, the Python library for face cropping enhances productivity and accuracy in various domains reliant on video analysis.

## Installation steps

```bash
pip install PyFaceCrop
``` 

## Code implementation
```
from PyFaceCrop import FaceCrop
capture = FaceCrop.FaceCrop("../Samples/test","identified_faces")
capture.generate()
```
![screenshot](./screenshots/Screenshot_Input.png)

generate() croping the faces from the present frame, if the face is above to recognize.

## Points to remember

PyFaceCrop generated crop frame faces into destination folder along with the respective folder with the name of the input the video file. So better to avoid multiple faces in the same video file to get a better dataset.

![screenshot](./screenshots/Screenshot_Sajja.png)   
![screenshot](./screenshots/Screenshot_Yogesh.png) 
![screenshot](./screenshots/Screenshot_User23.png) 


