# Face Mask Detection
This Facial Mask Detector is purely based on OpenCV and Python.
<h4>There are two steps to implement a Facial Mask Detector:</h4>
<ol>
  <li>Identifying the mouth and the entire face</li>
  <li>Identifying whether the person in front of the camera is wearing a mask or not</li>
</ol>

<h4>Identifying the face and mouth:</h4>
<ol>
  <li>HAAR Cascade object --> CascadeClassifier()</li>
  <li>Camera input</li>
  <li>Gray scale conversion of the image</li>
  <li>detectMultiScale()</li>
</ol>

<h4>Mask, yes or no:</h4>
<ol>
  <li>Gray image face box</li>
  <li>Black & white image face box</li>
  <li>Gray image mouth rectangle/li>
</ol>

<img src="truth_table.png">

