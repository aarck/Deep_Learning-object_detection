# Deep_Learning-object_detection
object detection using Python and OpenCV
To run the code make a seperate folder for clarity ,named images or anything you like and put as much images you like which are included in CLASSES

then go to the directory where you have cloned the repository and run following command

python deep_learning_object_detection.py \
	--prototxt MobileNetSSD_deploy.prototxt.txt \
	--model MobileNetSSD_deploy.caffemodel --image image_folder_name/image.jpg 
