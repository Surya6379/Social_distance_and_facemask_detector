# Social_distance_and_facemask_detector


This is a project which uses tensorflow object detection api and a self_trained model for face_mask detection . This is a project which helps the community helpers to avoid further spread of covid-19 by detecting distance between each person in a frame . If the minimum distance in a frame is below a threshold value then it classifies as unsafe . For  better classification the camera is placed in a fixed and higher place , so that it covers the full body of the person for calculating the distance .

# Requirments

1. Please download the tensoflow object detection api for the fucntioning of the project as it has more utilities .
youtube tutorial link for downloading and setuping tensorflow object detection api : https://www.youtube.com/watch?v=COlbP62-B-U&list=PLQVvvaa0QuDcNK5GeCQnxYnSSaar2tpku&index=1

2. Please download the prototxt file , the resnet model and the mask_detector model from the repository as it contains the architecture and weights of the model . And also provide the path in the code after downloading it 




