# Feature generation (Part #2)
This repository contains the second part for generating features of the challenge "KDD BR Competition 2022" of the team Artificial Psycho Killer.
## Requirements
    numpy==1.21.6
    pandas==1.3.5
    keras==2.6.0
    opencv-contrib-python==4.5.4.60
    opencv-python==4.5.4.60
    opencv-python-headless==4.5.4.60
   Can be found in `requirements.txt` file.
## Running
The input data needed to generate the features are the same distributed by the competition:
 - `public.csv`
 - train images
 - test images
 
Running notebooks `kddbr22 Img Shift.ipynb` and `kddbr20 FLANN based Matcher.ipynb` will output the following files:

 - `mario_train_vec_v1.csv`
 - `mario_train_vec_v1.csv`
 - `vecs_v3_fe.csv`

These three files are inputs for the next steps of the team's solution.

Before running the notebooks you may want to change the input/output paths to match your directories structure.
