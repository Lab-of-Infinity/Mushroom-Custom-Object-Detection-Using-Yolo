# Mushroom-Custom-Object-Detection-Using-Yolo

   **Objective: To build object Detection Model to detect Mushrooms from image using yolov3**
   
   **Dataset: Images Scrap from Google**
  
## Project Flow:
  **1. Web Scraping images and annotations using LabelImg**
  
  **2. Cloning Github Repo of Darknet**
      `!git clone 'https://github.com/AlexeyAB/darknet.git'`**
      
  **3. Setting Google colab GPU using Make file**
  
  **4. Making Changes in yolov3.config file**
  
  ![image](https://user-images.githubusercontent.com/90597433/183076476-fa24056c-793e-4fbd-8daa-51e7804a3d7e.png)
       
  **5. Generating label.data file using python script file `creating-files-data-and-name.py`**
  
  **6. Genrating train.txt and test.txt using python script file `creating-train-and-test-txt-files.py`**
  
  **7. Download pre-trained Yolov3 weights for the convolutional layers.**
  
  **8. Training Cutom Object Detector `!darknet/darknet detector train Custom_data/labelled_data.data darknet/cfg/yolov3.cfg custom_weights/darknet53.conv.74 -dont_show
`**

  **9. Testing Custom Object Detector with Test image (Applying Non-max separation)**
  
  ![image](https://user-images.githubusercontent.com/90597433/183078264-3fdcccf9-b981-407d-971a-aca767b3ee47.png)
