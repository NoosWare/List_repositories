<img src="images/Noos.png" width="200" height="120" />

# List of repositories
-------------
List of all the repositories of NoosWare

- [Noos API](#noos-api)
- [Noos API tutorials](#noos-api-tutorials)
- [Noos ROS tutorials](#noos-ros-tutorials)
- [Noos Python tutorials](#noos-python-tutorials)
- [Noos Web APP](#innovate-app)
- [SLAM using Noos and ROS](#ros-slam-example)
- [MARIO robot APP](#ericsson-public-app)
- [NAO APP](#nao-vision-example)
- [S2T Tool](#ericsson-hri)

_NOTE: The repositories not finished are not included in this list_

## Noos-API

**URL:** [https://github.com/NoosWare/noos-api-cpp](https://github.com/NoosWare/noos-api-cpp)

**Language:** C++

**Description:**

C++ API which gives you access to the Noos platform services. It requires a previous registration in the [noos](noos.cloud) webpage. 

Services availables in the platform:


| Human-Robot Interaction | Robot autonomy  | Robot autonomy    |
| ----------------------- | --------------- | ----------------- |
|                         | **Navigation**    | **Computer Vision**   |
|      |    |     |
| Human Detection         | SLAM with LIDAR    | Object Recognition |
| Face Detection          | Create Map         | QR Recognition |
| Face Recognition        | Get Map            | ORB Features |
| Age Detection           | Path Planning      |    |
| Gender Detection        |                    |    |  
| Face Expressions        |                    |    | 
| NLP - Dialogue Systems  |                    |    |    


**Dependencies:**

The following dependencies are required to build the C++ API:

- gcc/g++ >= 4.9
- boost >= 1.58
- cmake >= 2.8
- libssl-dev >= 1.0.1

## Noos-API-tutorials

**URL:** [https://github.com/NoosWare/noos_api_tutorials](https://github.com/NoosWare/noos_api_tutorials)

**Language:** C++

**Description:**

Tutorials for using the Noos Cloud API in C++ from scratch.

**Dependencies:**

- Noos API
- gcc/g++ >= 4.9
- boost >= 1.58
- cmake >= 2.8
- libssl-dev >= 1.0.1

## Noos-ROS-tutorials

**URL:** [https://github.com/NoosWare/noos_ros_tutorials](https://github.com/NoosWare/noos_ros_tutorials)

**Language:** C++

**Description:**

Tutorials using Noos API with ROS to show the compatibility. It includes examples like `SLAM` using a rover with the `rplidar v2`, how to do a simple `loop` or use a `vision batch` service.

**Dependencies:**

- ROS (Robot Operative System)
- Noos API
- gcc/g++ >= 4.9
- boost >= 1.58
- cmake >= 2.8
- libssl-dev >= 1.0.1

## Noos-Python-tutorials

**URL:** [https://github.com/NoosWare/noos-python-tutorials](https://github.com/NoosWare/noos-python-tutorials) 

**Language:** Python

**Description:**

Tutorials for using the Noos Cloud in case the user is not familiar with C++ language. It is well explained how to configure your environment for using python with this repository.

**Dependencies:**

- pip
- pyenv
- python >= 3.6.5
- opencv-python

## Innovate-APP

**URL:** [https://github.com/NoosWare/innovate_app](https://github.com/NoosWare/innovate_app)

**Language:** Javascript

**Description:**

Application to use computer vision algorithms on noos (face detection, emotion, age, gender). It is using a NodeJS with a simple web interface using JQuery.

**Dependencies:**

- npm
- node js

## Ros-SLAM-example

**URL:** [https://github.com/NoosWare/ros_slam_example](https://github.com/NoosWare/ros_slam_example)

**Language:** C++

**Description:**

It is and example using the rover with the `rplidar v2` and ROS. It is included in the repository [Noos ROS tutorials](#noos-ros-tutorials)
![Rover](images/rover.jpg)

**Dependencies:**

- ROS (Robot Operative System)
- Noos API
- gcc/g++ >= 4.9
- boost >= 1.58
- cmake >= 2.8
- libssl-dev >= 1.0.1

## Ericsson-public-APP

**URL:** [https://github.com/NoosWare/ericsson_public_app](https://github.com/NoosWare/ericsson_public_app)

**Language:** Javascript

**Description:**

Public application working with the Mario project which illustrates the chatbot with dialogue interactions
and SLAM using waypoints.
[Video demostration](https://www.youtube.com/watch?v=iCGpHmbJnOY)


**Dependencies:**

- ROS (Robot Operative System)
- npm
- node js
- python
- Google Cloud SDK
- repository S2T_win32 (private repository)
- repository ericsson_hri
- repository MARIO (private repository)


## NAO-vision-example

**URL:** [https://github.com/NoosWare/nao_vision_example.git](https://github.com/NoosWare/nao_vision_example.git)

**Language:** C++

**Description:**

Application to show NAO robot moving and looking for faces to recognize it and tell the age, gender and expression. 
[Video demostration](https://www.youtube.com/watch?v=P5v-DuxDO68&t=49s)

**Dependencies:**

- Noos API
- naoqi C++ SDK
- gcc/g++ >= 4.9
- boost >= 1.58
- cmake >= 2.8
- libssl-dev >= 1.0.1

## Ericsson-hri

**URL:** [https://github.com/NoosWare/ericsson_hri](https://github.com/NoosWare/ericsson_hri)

**Language:** Python

**Description:**

It connects the Linux PC of MARIO with the Windows PC for doing Speech to Text service through `Google Cloud` or 
`Dragon Natural Speaking` software. It is required to have an account or the license of the software mentioned.
This repository is used for running the [MARIO APP](#ericsson-public-app)

**Dependencies:**

- python
- Google Cloud SDK or Dragon NaturalSpeaking
- MARIO repository (private)
