<div align ='center'>
  
# AI
### Domain : Machine Learning / AI
  
  </div>
  


### Problem Statement 
Build Mathematical model using ML and signal processing concept to process the skin issues into dryness and oiliness.

### Description
Patients face a lot of problems with their skin. The main issue remains with the type of skin they have. Depending on the type of skin various skin diseases can occur. So if the skin is too dry it may start to peel and lead to various skin diseases like Psoriasis, Eczema etc. likewise too oily skin can lead to pimples which in turn can lead to scars. So the identification of skin type is of utmost need.

## Classes of Skin Diseases

![alt text](102730903-a-set-of-human-skin-conditions-illustration.webp)

## Frontend

![alt text](https://github.com/mbig-in/Skin-Disease-Detection/blob/main/Images/WhatsApp%20Image%202022-01-23%20at%2012.55.42%20PM.jpeg)

![alt text](https://github.com/mbig-in/Skin-Disease-Detection/blob/main/Images/WhatsApp%20Image%202022-01-23%20at%2012.55.42%20PM%20(1).jpeg)

![alt text](https://github.com/mbig-in/Skin-Disease-Detection/blob/main/Images/WhatsApp%20Image%202022-01-23%20at%2012.55.43%20PM.jpeg)

![alt text](https://github.com/mbig-in/Skin-Disease-Detection/blob/main/Images/result.jpeg)

![alt text](https://github.com/mbig-in/Skin-Disease-Detection/blob/main/Images/WhatsApp%20Image%202022-01-23%20at%2012.55.43%20PM%20(2).jpeg)



## Tech Stacks

+ Pytorch
+ torchvision
+ Pillow
+ HTML
+ CSS
+ Bootstrap
+ Javascript
+ Flask
+ Werkzeug


## Model Used

### EfficientNet-B0
The EfficientNet-B0 architecture wasn’t developed by engineers but by the neural network itself. This model was developed using a multi-objective neural architecture search that optimizes both accuracy and floating-point operations.

Taking B0 as a baseline model, the authors developed a full family of EfficientNets from B1 to B7 which achieved state of the art accuracy on ImageNet while being very efficient to its competitors.
Below is a table showing the performance of EfficientNets family on ImageNet dataset.

![alt text](https://github.com/mbig-in/Skin-Disease-Detection/blob/main/Images/fam.png)

The Efficient-B0 is mobile sized architecture having 11M trainable parameters. This is what the architecture looks like:

![alt text](https://github.com/mbig-in/Skin-Disease-Detection/blob/main/Images/b0.png)

The pre-trained imagenet weights were loaded into the model. The first seven layers of the model architecture were frozen and the rest of the layers were trained on the data. The Stochastic Gradient Descent optimizer was used with a learning rate of 0.01 and a momentum of 0.9 . The loss function used was categorical cross entropy. The model achieved an accuracy of <strong>95.5%</strong> on the test data set.


## Running Instructions
Open the terminal and type the following 
```
$ git clone https://github.com/mbig-in/Skin-Disease-Detection.git
$ cd Skin-Disease-Detection
$ python3 -m venv skin-class-env
$ source skin-class-env/bin/activate
$ pip3 install -r requirements.txt
$ python3 predict.py -m "Path to torch model" -i "Path to image"
```

## Developers

<table>
<tr align="center">


<td>

Mr. Shubham Parkhedkar 

<p align="center">
<img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS072GHoLgEqAsewUF91RfD8LaNuUKaUa21jw&s"  height="120"
alt="Shubham Parkhedkar">
</p>
<p align="center">
<a href = "https://github.com/mbig-in" target="_blank"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://in.linkedin.com/in/shubham-parkhedkar/" target="_blank">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>



<td>

Mahima Khatri

<p align="center">
<img src = "https://avatars.githubusercontent.com/u/77387745?v=4"  height="120"
alt="Mahima Khatri">
</p>
<p align="center">
<a href = "https://github.com/MahimaKhatri" target="_blank"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/mahima-khatri-434a3b193/" target="_blank">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>
  
  <td>

Charvy Gugalia

<p align="center">
<img src = "https://avatars.githubusercontent.com/u/77278889?v=4"  height="120"
alt="Charvy">
</p>
<p align="center">
<a href = "https://github.com/winee165" target="_blank"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/charvygugalia/" target="_blank">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>
</tr>
</table>

