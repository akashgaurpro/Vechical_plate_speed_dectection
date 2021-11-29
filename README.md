# Vechical_plate_speed_dectection
<h4>PROBLEM STATEMENT -</h4>
<p>
 Now a days we hear news about accidents on Highways very frequently. And in most of the cases main reason of accident is over speed. Although all highways do have signboards    indicating maximum speed limit for the sake of driver’s safety, but still people does not obey highway speed limit. Our proposed project aims to develop a system that detects vehicles driving at speeds over specified limit and inform concerned authorities immediately. Road accidents occurrences have increased recently so there needs to be a system that  allows to detect over speeding vehicles.
</p>

<p align="center"><img src="https://user-images.githubusercontent.com/66063837/143907598-aebf05f4-bd7e-489d-82d8-22bd4b375a5a.png" width="642.51" height="340.15" alt="image1"></p>


<p>
whereas this proposed system does not need any human interception and 
records car speed as well as wirelessly informs authorities of over speeding detections. Methods used include roadside speed traps set up and operated 
by the police and automated roadside 'speed camera' systems which may incorporate the use of an automatic number plate recognition system. 
</p>

<h4>REASONS :-</h4>
<p>
•	Road accidents are one of the disturbing events that constitute major loss. In India, it has become a major problem as it is claiming the lives of innocent people. Controlling the road accidents has become a crucial task.
</p>
<p>
•	One of the reason behind the project is to prevent the road accidents increases day by day due to over speed in prone areas.
</p>

<h4>OBJECTIVE & SCOPE:-</h4>
<p>
The main aim of this model is detect the speed of the vehicle then plate detection and store  the data of vehicle person and speed limit details in file considering various factors causing accidents.
</p>

<p align="center"><img src="https://user-images.githubusercontent.com/66063837/143907724-2d250592-e976-476d-bb0a-17772e6c4e57.png" width="642.51" height="491.33" alt="image3"></p>




<h4>METHODOLOGY -</h4>
<p>
<u style="color:red;">Image Processing:-</u>
</p>
<p>•	The digital image is then processed to some useful information by applying some image processing techniques. </p>
<p>•	After obtaining the image, the grayscale features take place to the input image which is to find the average color value from the three main component color which are red, green and blue (RGB).</p>
<p>•	After that, the grayscale image is further processed to the binarization and transform the grayscale image to only black and white for future use.</p>
<p>•	With the image in black and white, the system performs license plate detection by searching through rectangle made up with all four white edges in the image which possibly contains the characters within. </p>
<p>•	This step is crucial as the characters may not be detected when the license plate portion is incorrect.</p>
<p>•	After cropping out the detected license plate, the system segments the characters into individual for the recognition purpose by using Connected Component Analysis (CCA).</p>

<p>Working Steps:-</p>
<p>(1)	 Image Acquisition
<p>(2)	 License Plate Localization
<p>(3)	 Character Segmentation
<p>(4)	 Speed Detection


<p align="center"><img src="https://user-images.githubusercontent.com/66063837/143907848-eeaf3ed6-f418-423c-87e2-aa2aa191d845.png" width="604.72" height="264.56" alt="image4"></p>


<h4>FLOW CHART –</h4>
<p align="center"><img src="https://user-images.githubusercontent.com/66063837/143905210-3ea4cebe-6ad9-4150-8a23-89b233217e5c.png" width="831.49" height="831.49" alt="image6"></p>

<h4>HARDWARE TO BE USED –</h4>

<p>Hardware Requirements –</p>
 <p>•	Laptop / Mobile</p>
 <p>•	Camera</p>
  <p>•	For Speed Detection</p>
  <p>•	For Plate Recognition</p>

<p>Technologies –</p>
<p>•	PYTHON - The programming language to be used.</p>
<p>•	IMAGE PROCESSING</p>
<p>•	OpenCV – To identify objects and Number plate etc.</p>
<p>•	Machine Learning.</p>


<h4>REFERENCE AND BIBLIOGRAPHY –</h4>


<p>•	https://homepages.inf.ed.ac.uk/rbf/HIPR2/gryimage.htm</p>

<p>•	https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0029740</p>

<p>•	https://www.topcoder.com/thrive/articles/python-for-character-recognition-tesseract</p>

<p>•	https://link.springer.com/article/10.1007/s40747-021-00419-5</p>

<p>•	https://www.sciencedirect.com/science/article/pii/S1877050916311103</p>

<p>•	https://www.mygreatlearning.com/blog/opencv-tutorial-in-python/</p>

<p>•	https://www.analyticsvidhya.com/blog/2019/03/opencv-functions-computer-vision-python/</p>

















