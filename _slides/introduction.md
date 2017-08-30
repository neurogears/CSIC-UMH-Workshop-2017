---
layout: slides
title: Introduction to Bonsai
permalink: /slides/introduction/
---

<!-- .element: data-background="#000000" -->
# Bonsai
### A visual language for reactive programming

---

<!-- .element: data-background="#000000" -->
[http://bonsai-rx.org](http://bonsai-rx.org)

---

<!-- .element: data-background="#000000" -->
## Course Outline

<table class="reveal">
    <thead>
        <tr>
            <th></th>
            <th><small style="color:white">Monday</small></th>
            <th><small style="color:white">Tuesday</small></th>
            <th><small style="color:white">Wednesday</small></th>
            <th><small style="color:white">Thursday</small></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><small style="color:white">Morning</small></td>
            <td><small style="color:cornflowerblue">Introduction to Bonsai</small></td>
            <td><small style="color:darkgoldenrod">Acquisition and Tracking</small></td>
            <td><small style="color:darkgoldenrod">Closed-Loop and Synching</small></td>
            <td><small style="color:darkgoldenrod">Final Projects</small></td>
        </tr>
        <tr>
            <td><small style="color:white">Afternoon</small></td>
            <td><small style="color:chocolate">Acquisition and Tracking</small></td>
            <td><small style="color:chocolate">Closed-Loop and Synching</small></td>
            <td><small style="color:cornflowerblue">Advanced Concepts</small></td>
            <td><small style="color:chocolate">Final Projects</small></td>
        </tr>
    </tbody>
</table>

---

<!-- .element: data-background="#000000" -->
![Devices in systems neuroscience](../../assets/images/devices.jpg)

--

<!-- .element: data-background="#000000" -->
<iframe width="854" height="480" src="https://www.youtube.com/embed/4q9mFkZ3J_g?controls=0&amp;autoplay=1&amp;loop=1&amp;playlist=4q9mFkZ3J_g&amp;showinfo=0&amp;rel=0&amp;html5=1" frameborder="0" allowfullscreen/>

--

<!-- .element: data-background="#000000" -->
<iframe width="854" height="480" src="https://www.youtube.com/embed/qXqAXgXJPmo?controls=0&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1" frameborder="0" allowfullscreen/>

--

<!-- .element: data-background="#000000" -->
<iframe width="854" height="480" src="https://www.youtube.com/embed/mJDV07ptQFk?start=40&amp;controls=0&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1" frameborder="0" allowfullscreen/>

---

<!-- .element: data-background="#000000" -->
![Bonsai workflow editor](../../assets/images/editor.jpg)

---

<!-- .element: data-transition="default none" -->
#### A metaphor for observable sequences

<img alt="Nasa twitter account" src="../../assets/images/nasatwitter.jpg" width="400"/>

--

<!-- .element: data-transition="none" -->
#### A metaphor for observable sequences

<img alt="Webcam twitter account" src="../../assets/images/webcamtwitter.jpg" width="400"/>

---

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/cameracapture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/graycam-marble.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/framepicker-capture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/filecapture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscalefile.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscaletransform.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimagesink.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/conditionkey.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

---

##### Operator Categories

![Operator categories](../../assets/images/categories.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

---

###### Skip

![Skip](../../assets/images/skip.svg)

---

###### Take

![Take](../../assets/images/take.svg)

---

###### SkipUntil

![SkipUntil](../../assets/images/skipuntil.svg)

---

###### TakeUntil

![TakeUntil](../../assets/images/takeuntil.svg)

---

###### Zip

![Zip](../../assets/images/zip.svg)

---

###### CombineLatest

![CombineLatest](../../assets/images/combinelatest.svg)