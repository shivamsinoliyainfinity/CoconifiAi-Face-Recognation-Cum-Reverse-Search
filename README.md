<h1>About the project</h1>
<!-- <br></br> -->
<p>This is a facial recognition model. This model detects faces and extract features from that detected faces and use that features to recognise them in data set</p>
<h2><u>Salient feature of this model:</u></h2>
<ul>
    <li><strong>This model can work on small datasets:-</strong>In general CNN model about 50-100 images are required to recognise a face whereas this model requires only 1-2 image in dataset to recognise a face. This saves lot of space on system.</li>
    <li><strong>This model can gather information of unknown faces:-</strong>The object is captured automatically by cam. Image get converted into a link and this link is used for reverse image search on web browser, a technique used in web scraping for gathering information. We can get information/metadata in form of JSON. </li>
    <li><strong>This model can work on multiple faces:-</strong>Facial detection in this model can generate n no. of faces which can be recognised by <a href="https://towardsdatascience.com/hashes-power-probabilistic-data-structures-d1398d1335c6" >probalistic hashing</a> </li>
    <li><strong>This model can work on any lightning condition:-</strong>For this feature we used haar's cascade model. First it convert an RGB image into a low light binary image and constructs arrow from one bright spot to another bright spot which makes it independent of lightning condition.</li>
</ul>

<!-- <br></br> -->
<!-- <h2>Tech Stacks used</h2> -->
![face-recognition](https://user-images.githubusercontent.com/106926948/199243922-c4cd82f2-a69d-4d74-98a4-4b81745ded93.gif)

![image_processing20210912-26750-1vwerka](https://user-images.githubusercontent.com/106926948/199243774-e17cf55b-0150-4458-a0e4-bcaf9a281726.gif)


<h3>Demo video (when there is low lightning conditions)</h3>


<h3>Demo video (when there is mid lightning conditions)</h3>
![](https://github.com/shivamsinoliyainfinity/CoconifiAi-Face-Recognation-Cum-Reverse-Search/blob/84e1a9653de244973ed2ddeae5f37567ca943f36/demo/mid_light.mp4)

<h3>Demo video (for multiple face detection)</h3>

![multiple_detection_AdobeExpress_AdobeExpress](https://user-images.githubusercontent.com/106926948/199248477-988b4a3f-f1ba-4414-b742-17185a5330fa.gif)

<h3>Demo video (for unknown faces)</h3>
![](https://github.com/shivamsinoliyainfinity/CoconifiAi-Face-Recognation-Cum-Reverse-Search/blob/84e1a9653de244973ed2ddeae5f37567ca943f36/demo/unknown_meta_data.mp4)
