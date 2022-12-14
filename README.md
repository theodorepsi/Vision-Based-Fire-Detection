# Vision-Based Fire Detection - Detecting Fire using a Variety of 2D & 3D CNNs
This page contains all the various Jupyter notebooks that were used in the thesis paper for the EEE4022S course at the University of Cape Town (UCT). A variety of 2D and 3D Convolutional Neural Network (CNN) models were experimented with and performance evaluated using two unseen videos from the limited High Performance Wireless Research and Education Network (HPWREN). 

The models implemented are as follows:
  1. 2D CNN 
  2. 3D CNN implemented as a 2D CNN
  3. 3D CNN with depths 2, 4 and 6
  4. 3D Frame Referencing CNN
  5. 3D Frame Differencing CNN
  
Each of these models followed a basic general CNN structure that included convolutional layers, pooling layers, batch normalisation, a flatten layer and dense layers. This structure is shown in the diagram below.

<p align="center">
  <img src = "https://user-images.githubusercontent.com/88879534/201475182-e787e768-eb1d-4760-a2ae-9229a1d30845.png">
</p>

Each model's structure, such as kernel size, input dimensions etc is shown in the pictures that follow.


### 2D CNN
<p align="center">
  <img width = "600" height = "400" src = "https://user-images.githubusercontent.com/88879534/201475444-0adc6e5c-d208-4318-822d-b36194fc2271.png">
</p>

### 3D CNN implemented as a 2D CNN & 3D Frame Differencing CNN
<p align="center">
  <img width = "600" height = "400" src = "https://user-images.githubusercontent.com/88879534/201475476-8107b213-0855-4e47-a513-baf71bbe214c.png">
</p>

### 3D CNN with depth 4
<p align="center">
  <img width = "600" height = "400" src = "https://user-images.githubusercontent.com/88879534/201475566-8082d461-52bb-498e-b4c4-f722ff9577d5.png">
</p>

### 3D Frame Referencing CNN
<p align="center">
  <img width = "600" height = "400" src="https://user-images.githubusercontent.com/88879534/201475782-f308cef9-ce0f-4d21-be45-60538519f5e3.png">
</p>

## HPWREN Unseen Videos
The images of the two unseen videos are shown in the images below.

<h3 align="center">Unseen Video 1</h3>
<p align="center">
  <img src = "https://user-images.githubusercontent.com/88879534/201475974-eada8a48-a3ff-4492-9562-e8ef2f91dc1e.png">
</p>

<h3 align="center">Unseen Video 2</h3>
<p align="center">
  <img src = "https://user-images.githubusercontent.com/88879534/201475978-6739b211-6d96-4491-9561-9ea8f5632442.png">
</p>

