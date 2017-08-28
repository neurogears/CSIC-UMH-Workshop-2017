---
layout: default
title: Closed-Loop and Synchronization
---

<img width="10%" style="float: left;" src="{{ site.baseurl }}/assets/images/bonsai.png">
<img width="10%" style="float: right;" src="{{ site.baseurl }}/assets/images/neurogears.png">

Closed-Loop and Synchronization
===============================

Video Closed-Loop
-----------------

### Exercise 1: Measuring closed-loop latency

### Exercise 2: Triggering a line on region of interest activity

* Insert a `CameraCapture` source.
* Insert a `Crop` transform.
* Run the workflow and use the `RegionOfInterest` property to specify the desired area (hint: you can use the visual editor for an easier calibration).
* Insert a `Grayscale` and a `Threshold (Vision)` transform (or your preferred segmentation pipeline).
* Insert a `Sum (Dsp)` transform. This operator sums all the pixel values across the entire input image.
* Select the `Scalar` > `Val0` field from the right-click context menu.

**Note:** The `Sum` operator sums the pixel values across all image colour channels. However, in the case of grayscale binary images, there is only one active channel and its sum is stored in the `Val0` field.
{: .notice--info}

* Insert a `GreaterThan` transform and configure the `Value` property to an appropriate threshold.
* Insert the Arduino `DigitalOutput` sink.
* Set the `Pin` property of the `DigitalOutput` operator to 13.
* Configure the `PortName` property.
* Run the workflow and verify that entering the region of interest triggers the Arduino LED.
* **Optional:** Replace the `Crop` transform by a `CropPolygon` to use non-rectangular regions.

**Note:** The `CropPolygon` operator uses the `Regions` property to define multiple, possibly non-rectangular regions. The visual editor is similar to `Crop`, where you draw a rectangular box. However, in `CropPolygon` you can move the corners of the box by right-clicking *inside* the box and dragging the cursor to the new position. You can add new points by double-clicking with the left mouse button, and delete points by double-clicking with the right mouse button. You can delete regions by pressing the `Del` key and cycle through regions by pressing the `Tab` key.
{: .notice--info}

### Exercise 3: Triggering a line on distance between objects

### Exercise 4: Modulating stimulus intensity based on distance to a point

### Exercise 5: Centering the video on a tracked object

Data Synchronization
--------------------

### Exercise: Synchronizing behaviour events with ephys

### Exercise: Synchronizing video with ephys using an LED

### Exercise (Optional): Synchronizing video with ephys using GPIO

### Exercise: Synchronizing a visual stimulus with ephys

### Exercise (Optional): Synchronizing video acquisition to a visual stimulus
