## Assignment_2

### Step 1: Clone this repo and download the weights file(https://drive.google.com/open?id=1HvN5KueHboe9MBABA70qvbpjgoH7L_NA) and store it in the yolo-colo file.

### Step 2: For Image Processing/Object Detection- Run the 'yolo.py' file in the same directory where image file is stored and from there open up the terminal and execute the following command---
---------$python yolo.py -i "path to input image" -y yolo-coco
### Note-Here i have set the default confidence and threshold value. Also delete image(given in the repo) from Image-output to check whether the image file is stored in the Image-output file while execution of file in the terminal.

### Step 3: For Video Processing/Object Detection- Run the 'yolo_video.py' file in the same directory where video file is stored and from there open up the terminal and execute the following command---
---------$python yolo.py -i "path to input image" -o "path to output image" -y yolo-coco
### Note-For perfect execution set the path of output video in .avi format. Also delete video(given in the) from Video-output to check whether the video file is stored in the Video-output file.

*******************************************************************************************************************************************
