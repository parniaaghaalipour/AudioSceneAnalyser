
## Audio Scene Analysis

This repository contains the source code for our project on audio scene analysis. The goal of the project was to develop a system capable of accurately analyzing and interpreting real-life audio scenes, using machine learning and signal processing techniques.

![Alt text](/logo.png)

### Dataset

The data used for this project was the TUT Acoustic Scenes 2017 Development Dataset. It consists of 10-second audio segments from 15 different acoustic scenes, covering both indoor and outdoor environments, as well as vehicular scenes.

### Project Structure

This repository is organized as follows:

```
- data/
  - TUT Acoustic scenes 2017/
- src/
  - preprocessing/
    - script_1.py
    - script_2.py
  - model/
    - script_3.py
- notebooks/
  - EDA.ipynb
  - Model_Training_Evaluation.ipynb
- results/
- README.md
```

### Dependencies

This project was implemented in Python. The main dependencies are:
- NumPy
- SciPy
- Librosa (for audio processing)
- Scikit-learn (for machine learning)
- Matplotlib and Seaborn (for visualization)


### How To Run The Code

To run the code, perform the following steps:

1. Clone the repository
```
$ git clone https://github.com/<your_username>/audio_scene_analysis.git
```
2. Navigate to the project directory 
```
$ cd audio_scene_analysis
```
3. Install the necessary dependencies 
``` 
$ pip install -r requirements.txt
```
4. Execute the preprocessing script to process the audio data
```
$ python src/preprocessing/script_1.py
```
5. Run the machine learning model script
``` 
$ python src/model/script_3.py
```

### Results

### Future Work


### Contributors


### License 

This project is licensed under the terms of the <MIT Liecence> license. You can check out the full license in the `LICENSE` file.

### Acknowledgments

