# Udacity Robotics Software Engineer Nanodegree -- Robot SLAM Project
#### Sebastian Castro, 2019

Please refer to the PDF in this repository for more details and background.

## Installation Instructions
Clone this repository to the `src` directory of a valid Catkin workspace. Then, use `catkin_make`.

## Launch Instructions
On 3 separate terminals, enter the following commands.

* `roslaunch slam_project world.launch`
* `roslaunch slam_project mapping.launch`
* `roslaunch slam_project teleop.launch`

To launch the benchmark (kitchen/dining) vs. custom worlds

* `roslaunch slam_project world.launch world:=kitchen_dining` (default)
* `roslaunch slam_project world.launch world:=custom`

## Accessing Map Database Files
Due to file size limits, the map database files are hosted externally. You can download them from Google Drive below.

* Benchmark world: https://drive.google.com/open?id=1yxHkAzZsgNnkfRmw5SnJwho7OqMgZv8B
* Custom world: https://drive.google.com/open?id=1JTdgdLm_fOl43zWnRZ2j6fRALyB3PUz6
