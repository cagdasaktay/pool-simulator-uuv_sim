
# Pool Simulator

It is designed for underwater robots (ROV, AUV etc.). The model was created with olympic pool dimensions.

[Click](https://github.com/cagdasaktay/pool-simulator) to use the simulator on ROS Noetic. (This version does not include uuv simulator packages.)

## Requirements for use

- [ROS Melodic](http://wiki.ros.org/melodic/Installation/Ubuntu)
    
    `Ubuntu 18.04`
- [uuv_simulator](https://uuvsimulator.github.io/)

    ```sh
  sudo apt install ros-melodic-uuv-simulator
  ```
## Installation

```bash 
cd ~/catkin_ws/src
```

```bash 
git clone https://github.com/cagdasaktay/pool-simulator-uuv_sim.git
```
```bash 
cd ~/catkin_ws
```
```bash 
catkin_make
```
```bash 
source devel/setup.bash
```
  
## Launch Simulation in Gazebo

You can run the simulation with the following command.

```bash 
 roslaunch pool_simulator gazebo.launch
```
    
## Screenshot

![Ekran görüntüsü 2021-09-10 145356](https://user-images.githubusercontent.com/71928699/132852496-ca685674-91b4-4e05-bd31-76b5c657f639.jpg)


  
## Contact
- Çağdaş Aktay - cgdsaktay@gmail.com


  
