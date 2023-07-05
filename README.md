<p align="center">
</a>
	<h1 align="left"> Motion Matrix Evaluation </h1>
	<h4 align="left"> State of the art for estimation of motion matrix involving pose estimation using mediapipe and dynamic time warping.
</h4>
	
</p>


__DEMO__



## Functionalities

- [ ]  Draw posture on frames using media pipe  
- [ ]  motion comparison and scoring using Dynamic Time Warping  


## Tech Stack
* Mediapipe:
* opencv
* fastdtw

	

## Introduction
Bodytracking to compare two 5-second dance videos and generate a score.

## Working
This model is used to score motion and action using Dynamic Time Warping and posture dectection. It can be used in various applications like dance training, gym tutor. 

## Running Instruction
Firstly download Anaconda using https://docs.anaconda.com/free/anaconda/install/ and then open the terminal to type the following commands
```
$ git clone https://github.com/Ayush152/motion-matrix-evaluation.git
$ cd motion-matrix-evaluation/
$ conda env create -f environment.yml
$ conda activate motion-env
$ python3 main.py
```
output
```
Final Similarity Percentage : <percentage>
```
