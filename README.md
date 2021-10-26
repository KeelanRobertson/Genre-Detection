# Genre-Detection

Using a variety of data science techniques to try and classify the genre of a song.

### Requirements

numpy:  `pip install numpy`  
scipy: `pip install scipy`  
pandas: `pip install pandas`  
matplotlib: `pip install matplotlib`  
seaborn: `pip install seaborn`  
tensorflow: `pip install tensorflow`  
sklearn: `pip install scikit-learn`  
imblearn: `pip install imbalanced-learn`  
librosa: `pip install librosa`  
pydub: `pip install pydub`  
statsmodels: `pip install statsmodels`  
ffmpeg: `pip install ffmpeg-python`  
audioread: `pip install audioread`

### Data

Data used can be found here: https://github.com/mdeff/fma

### Results

Using the data we attempted to fit 4 model types which resulted in the following accuracy scores:

**Logistic Regression** - 46% Accuracy  
**KNN** - 44% Accuracy  
**Random Forests** - 56% Accuracy  
**Neural network** - 51% Accuracy  

Following this we tried to model the main metrics that spotify uses to classify songs on their platform:  
Energy, Acousticness, Speechiness, Instrumentalness, Danceability

Using XGBoost we created models for each of these metrics. 
Our Train and Test scores are shown in the following table.

![image](https://user-images.githubusercontent.com/87439600/138870503-0fc80279-7f5e-441d-845e-dd531dc58a60.png)
