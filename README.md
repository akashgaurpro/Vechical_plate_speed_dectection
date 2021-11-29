# Vechical_plate_speed_dectection
<h4>PROBLEM STATEMENT -</h4>
<p>
 Now a days we hear news about accidents on Highways very frequently. And in most of the cases main reason of accident is over speed. Although all highways do have signboards    indicating maximum speed limit for the sake of driver’s safety, but still people does not obey highway speed limit. Our proposed project aims to develop a system that detects vehicles driving at speeds over specified limit and inform concerned authorities immediately. Road accidents occurrences have increased recently so there needs to be a system that  allows to detect over speeding vehicles.
</p>

<img src="https://user-images.githubusercontent.com/66063837/143902601-b0437260-7190-4078-9d27-2940158d279b.png" width="302.36" height="264.56" alt="image1">
<img src="https://user-images.githubusercontent.com/66063837/143903247-0ac571d1-8f2c-4b90-bc00-6852793f7126.png" width="302.36" height="264.56" alt="image2">

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

<img src="https://user-images.githubusercontent.com/66063837/143903746-0e5dcac6-f219-4036-ba8b-c958452258f2.png" width="302.36" height="415.74" alt="image3">
<img src="https://user-images.githubusercontent.com/66063837/143903924-3c5da624-a8d3-43cc-b1cf-94dc347de145.png" width="302.36" height="415.74" alt="image4">

<h4>METHODOLOGY -</h4>
<p>
<u>Image Processing:-</u>
</p>
<p>•	The digital image is then processed to some useful information by applying some image processing techniques. </p>
<p>•	After obtaining the image, the grayscale features take place to the input image which is to find the average color value from the three main component color which are red, green and blue (RGB).</p>
<p>•	After that, the grayscale image is further processed to the binarization and transform the grayscale image to only black and white for future use.</p>
<p>•	With the image in black and white, the system performs license plate detection by searching through rectangle made up with all four white edges in the image which possibly contains the characters within. </p>
<p>•	This step is crucial as the characters may not be detected when the license plate portion is incorrect.</p>
<p>•	After cropping out the detected license plate, the system segments the characters into individual for the recognition purpose by using Connected Component Analysis (CCA).</p>

<p><u>Working Steps:-</u></p>
<p>(1)	 Image Acquisition </p>
<p>(2)	 License Plate Localization</p>
<p>(3)	 Character Segmentation</p>
<p>(4)	 Speed Detection</p>


<img src="https://user-images.githubusercontent.com/66063837/143904736-4b9c1c8e-de32-430a-8a0e-5c53e7f37108.png" width="264.5" height="264.5" alt="image4">
<img src="https://user-images.githubusercontent.com/66063837/143904875-e7e618ec-f024-43eb-a2f2-0f14c5d8a3f8.png" width="37.5" height="38.5" alt="image44">
<img src="https://user-images.githubusercontent.com/66063837/143904885-065b283f-adb4-4108-aeac-e6601bfb1e9e.png" width="302.36" height="264.5" alt="image5">

<h4>FLOW CHART –</h4>
<img src="https://user-images.githubusercontent.com/66063837/143905210-3ea4cebe-6ad9-4150-8a23-89b233217e5c.png" width="755.9" height="793.7" alt="image6">

<h4>HARDWARE TO BE USED –</h4>

<p>Hardware Requirements –</p>
<p>•	Laptop / Mobile</p>
<p>•	Camera</p>
<p>•	For Speed Detection</p>
<p>•	For Plate Recognition</p>

<p>Technologies –</p>
<p>•	PYTHON - The programming language to be used.</p>
<p>•	IMAGE PROCESSING</p>
<p>•	OpenCV – To identify objects and Number plate etc. </p>
<p>•	Machine Learning.</p>


<h4>REFERENCE AND BIBLIOGRAPHY –</h4>


<p>•	https://homepages.inf.ed.ac.uk/rbf/HIPR2/gryimage.htm</p>

<p>•	https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0029740</p>

<p>•	https://www.topcoder.com/thrive/articles/python-for-character-recognition-tesseract</p>

<p>•	https://link.springer.com/article/10.1007/s40747-021-00419-5</p>

<p>•	https://www.sciencedirect.com/science/article/pii/S1877050916311103</p>

<p>•	https://www.mygreatlearning.com/blog/opencv-tutorial-in-python/</p>

<p>•	https://www.analyticsvidhya.com/blog/2019/03/opencv-functions-computer-vision-python/</p>

















