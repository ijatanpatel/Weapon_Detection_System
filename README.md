# Weapon_Detection_System

We have created a weapon detection system, which can detect Gun and Knife also with its confidence score.

first, download the weapon_detection_final.py file and train the model on your dataset.
    -> while training keep in mind that, use the dataset which is YOLO-V8 model compatible.
    -> you can create your own dataset from ' Roboflow ', and save it as yolo -v8, it will automatically save the dataset on your local machine which is yolo -v8 compatible.
after finishing the training, the model will be saved in best.pt file format.

then just give the path of your best.pt in app.py file, and you are go to run the project.

when your live webcam will detect any weapon, it will save its confidence score, time, cam-no in database.
