# vrc_resources

### Repository Overview 
In this repo you can find my old notes and python notebooks on odometry, move to reference point/path, and pure pursuit,
which are some of the algorithms I used the most when competing in the VEX Robotics Competition.
You can find pdf notes in the `notes` folder and Jupyter (Google Colab) notebooks in the `python_animation_notebooks` folder.

------------------

### Jupyter Notebooks
I like testing out new algorithms in Python as the easy visualization/animation allows me to see how the algorithms should behave under ideal conditions. 
You can run the Jupyter notebooks in this repo in your browser if you upload them to [Google Colab](https://colab.research.google.com/).

`Move_to_Reference_Pose_with_Intermediate_Direction.ipynb` and `X_Drive_Move_to_Pose.ipynb` has an `initialization` section at the top of the second cell. 
You can change the parameters in this section and run the animation code again to see how the algorithms perform under different conditions. 
For example, below is a robot trajectory comparison between `Kp_turn = 1.2` and `Kp_turn = 1.7` (from `Move_to_Reference_Pose_with_Intermediate_Direction.ipynb`):

<img src = "https://user-images.githubusercontent.com/97369518/210098308-1b628766-5717-414a-9d64-4f848b1d0414.png" width = 400> <img src = "https://user-images.githubusercontent.com/97369518/210098311-da3e62d3-b422-4d71-b871-f91158f31418.png" width = 400>

Jupyter Notebook tips:
1. To run a cell, press `shift`+`enter`.
2. The cells need to be executed sequentially to work. For example, you need to run the first cell before running the second cell for the second cell to work.
