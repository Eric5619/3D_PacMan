## Project Overview
This repository contains the implementation for the `3D_PacMan` project. This project was developed as part of a course assignment.

## Usage Notice
This project is intended for educational and academic purposes only. If you use or reference any part of this work, please give appropriate credit and cite the repository as follows:

**Citation Format**:  
Wang Yixin, "3D_PacMan", GitHub Repository, https://github.com/Eric5619/3D_PacMan, October, 2024.

## License and Acknowledgements
This project is under an academic license. For any inquiries or permission requests, please contact wyx5619@gmail.com.

Project name: 3D Pac-Man

Introduction:

You may need to install some packages, for example:
!pip install albumentations

For the advance Solution, a new dataset was created. Using the functions provided in the PacMan_Helper.py to capture the images of red balls in the 3D environment. In order to easily obtain the images, I manually redefined the position of the red balls in a straight line and captured images of it at different angles. After obtaining the images, I restored the position of the red ball to its original position.

Code instruction:

To run the code, you can directly use the newly created dataset(annotated_images) to train the DNN based detector. Place the code file(PacMan.ipynb) in the same directory as the annotated_images folder and the training_images folder.

The code to create new datasets from the 3D environment has been commented and can be used if needed.
