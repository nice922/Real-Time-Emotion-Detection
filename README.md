# Real-Time-Emotion-Detection

<h2>Packages need to be installed</h2><br>
pip install numpy<br>
pip install opencv-python <br>
pip install keras <br>
pip3 install --upgrade tensorflow <br>
pip install pillow<br>
install scipy <br>
install matlibplot <br>

<h3>download FER2013 dataset</h3><br>
from below link and put in data folder under your project directory<br>
https://www.kaggle.com/msambare/fer2013<br>

<h3>Train Emotion detector</h3><br>
with all face expression images in the FER2013 Dataset<br>
train your data use main.py<br>
It will take several hours depends on your processor. (On i5 processor with 8 GB RAM it took me around 4 hours) after Training , you will find the trained model structure and weights are stored in your project directory. emotion_model.json emotion_model.h5

copy these two files create model folder in your project directory and paste it.

<h3>run your emotion detection test file</h3><br>
python Videotester.py
