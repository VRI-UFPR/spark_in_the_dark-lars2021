<h1>Spark in the Dark: Evaluating Encoder-Decoder Pairs for COVID-19 CT's Semantic Segmentation</h1>

<img src='images/img1.jpg' style="width:50%;">
<img src='images/img2.jpg' style="width:50%;">
<img src='images/img3.jpg' style="width:50%;">
<img src='images/img4.jpg' style="width:50%;">

<h2>See the implementation and the available networks in: <a href="https://github.com/qubvel/segmentation_models.pytorch">Segmentation Models</a></h2>

<h2>Installation:</h2>

<p>pip install -r requirements.txt</p>

<p>Copy the files inside the scripts to the utils folders inside the lib/python3.6/site-packages/segmentation_models_pytorch folder</p>

<h2>Dataset></h2>

<p>Setup a txt file with the images paths as follows for training and validation:</p>

<p>path/to/image1.jpg path/to/mask1.png <br>
path/to/image2.jpg path/to/mask2.png <br>
path/to/image3.jpg path/to/mask3.png</p>

<p>or just the images path for tests</p>
<p>path/to/image1.jpg<br>
path/to/image2.jpg<br>
path/to/image3.jpg</p>

<p>Setup the config file following the examples in the config folder</p>

<h2>Execute:</h2>
<p>python main.py --configs config_file.yml</p>