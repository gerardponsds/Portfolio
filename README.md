# PORTFOLIO

I'm Gerard Pons Recasens, an **Engineering Physics** graduate and **Data Science Master's** sudent. Here is my portfolio, where I showcase some recent work and small projects.

# [PROJECT 1: END-TO-END GESTURE RECOGNITION CONTROL SYSTEM](https://github.com/gesturesAidl/video_processor)

In this project a **Linuox OS** was controlled by the user's gestures, which were recorded by the webcam and classified using a Deep Learing model based on a **I3D Inflated network**.

* We deployed a **Deep Learning model** to predict the gestures made by the user, using **Transfer Learning** from **state-of-the-art models**.
* Worked with **large volumes** of data, performed **data cleaning** , **feature engineering** and **data augmentation**.
* Performed scheduled **hyperparameter tuning** with the **RayTune** library.
* Created a pipline brokered with **RabbitMQ**, where the user recorded videos were sent to our **Google Cloud** machine, were processed and predicted there, and the action to perform was sent back to the user's device.
* Worked collabaratively in **GitHub**, and used **Python** with the ML library **PyTorch**.
* A **demo** of the full process working can be seen [here](https://www.youtube.com/watch?v=G59jl27JF2A&ab_channel=GesturesAidl).

<div class="row">
  <img class="pull-left" src="Images/confusion.png"  width="430">
  <img class="pull-left" src="Images/demo_gif.gif"  width="530">
</div>


# [PROJECT 2: NBA: 3-POINT SHOTS INSIGHTS](https://github.com/gerardponsds/NBA_Shot_Analysis)

As a basketball enthisiast I wanted to explore why there was an **increasing trend on attempting 3-point shots** and the impact those had on the game. 

* **Data visualization** and **storytelling** with data about NBA shot statistics from seasons 97'-98' to 19'-20'.
* **Played and explored** with the data using different approches. 
* Posed and answered questions and **drew conclusions** from them.
* Used **Python**, with the library **Pandas** for data manipulation and **MatPlotLib** for visualization.


<div class="row">
  <img class="pull-left" src="Images/heat_gif.gif"  width="480">
  <img class="pull-left" src="Images/shots_distribution.png"  width="400">
</div>

# [PROJECT 3: METEORITE IDENTIFICATION FROM DRONE IMAGES](https://github.com/gerardponsds/Meteorite-Identification)

In this project a classifier was created using **Deep Learning** in order to identify meteorites from drone obtained images. It was done to help researchers who spend weeks in the Atacama Desert looking for meteorties in order to study and analize them, as the conditions there are harsh.

* Created **own Dataset** from scratch.
* Perfored and explored extensively **Data Augmentation** methods,  as the dataset was not large enough.
* Explored different **architectures** selecting them by monitoring various metrics.
* **Fine tuned** different architecture parameters in order to get the best model possible.
* Used **Python** with the **PyTorch** library.

<p align="center">
  <img src="Images/all.jpg"  alt="drawing" width="700"/>
</p>
