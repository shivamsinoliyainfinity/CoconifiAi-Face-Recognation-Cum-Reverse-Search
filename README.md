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
<h2>Tech Stacks used</h2>
<img src="https://raw.githubusercontent.com/serengil/deepface/master/icon/deepface-icon-labeled.png" width="200" height="200" /><img src="https://user-images.githubusercontent.com/67586773/105040771-43887300-5a88-11eb-9f01-bee100b9ef22.png" width="200" height="200"/><img src="https://camo.githubusercontent.com/981d48e57e23a4907cebc4eb481799b5882595ea978261f22a3e131dcd6ebee6/68747470733a2f2f70616e6461732e7079646174612e6f72672f7374617469632f696d672f70616e6461732e737667" width="200" height="200"/><img src="https://opencv.org/wp-content/uploads/2022/05/logo.png" width="200" height="200"/><img src="https://camo.githubusercontent.com/30cdd34ec996c7ef9ad50fa02379e02738d27979e5aa7839899fb9e03fe65a4d/68747470733a2f2f6d65646961706970652e6465762f696d616765732f6d65646961706970655f736d616c6c2e706e67" height="200" width="200" />
<h3>Demo video (when there is low lightning conditions)</h3>
![](https://github.com/shivamsinoliyainfinity/CoconifiAi-Face-Recognation-Cum-Reverse-Search/blob/84e1a9653de244973ed2ddeae5f37567ca943f36/demo/low_light.mov)

<h3>Demo video (when there is mid lightning conditions)</h3>
![](https://github.com/shivamsinoliyainfinity/CoconifiAi-Face-Recognation-Cum-Reverse-Search/blob/84e1a9653de244973ed2ddeae5f37567ca943f36/demo/mid_light.mp4)

<h3>Demo video (for multiple face detection)</h3>
![](https://github.com/shivamsinoliyainfinity/CoconifiAi-Face-Recognation-Cum-Reverse-Search/blob/84e1a9653de244973ed2ddeae5f37567ca943f36/demo/multiple_detection.mov)


<h3>Demo video (for unknown faces)</h3>
![](https://github.com/shivamsinoliyainfinity/CoconifiAi-Face-Recognation-Cum-Reverse-Search/blob/84e1a9653de244973ed2ddeae5f37567ca943f36/demo/unknown_meta_data.mp4)
