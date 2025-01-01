


# A* Algorithm Implementation for Shortest Path ENPM661 PROJECT3 
### 
    Author 1: Abraruddin Syed UID: 120109997
    Author 2: Vijay Chevireddi UID: 119491485
    Author 3: Chandhan Saai Katuri UID: 120387364



This repository contains an implementation of the A* (A-star) search algorithm, written by Vijay Abraruddin Chandhan. The A* algorithm is a popular choice for pathfinding and graph traversal, which is the process of finding a path between multiple points, called "nodes"

## Prerequisites for part-1

- Python 3.x
- OpenCV (cv2) library
- NumPy library
- Math library
- PriorityQueue library

## Prerequisites for part-2

- Python 3.x
- OpenCV (cv2) library
- NumPy library
- Math library
- PriorityQueue library
- rclpy
- geometry_msgs.msg
- time
- nav_msgs.msg
  

## Usage

1. Clone the repository or download the `proj3p2_vijay_abraruddin_chandhan_PART1.py` file for part-1.
2. Clone the repository or download the `proj3p2_vijay_chandhan_abrar_PART2.py ` file for part-2.
3. Install the required libraries using pip:
   ```
   pip install opencv-python numpy
   ```
4. Run the script part-1:
    ```
   proj3p2_vijay_abraruddin_chandhan_PART1.py
   ```
5. Run the script part-2:
   ```
    # Replace ".bash" with your shell if you're not using bash
    # Possible values are: setup.bash, setup.sh, setup.zsh
    source /opt/ros/galactic/setup.bash
    export TURTLEBOT3_MODEL=waffle
    # colcon build
    colcon build
    # source setup
    source install/setup.bash
    # launch competition_world
    ros2 launch turtlebot3_project3 competition_world.launch.py
    # run executable
    ros2 run turtlebot3_project3 proj3p2_vijay_chandhan_abrar_PART2.py 
   
   ```
6. Follow the prompts to input the start and goal points.

### Example Input

After running the script, you will be prompted to input the start and goal points. Here's an example of how you might provide this input:

```

Click ENTER for entering default value 
Enter clearance in mm:  (default: 75):
Enter start point (x, y,theta):  (default: 500,1000,0):
Enter goal point (x, y,theta):  (default: 5700,1200):
Enter RPM1 and RPM2 separated by comma:  (default: 50,100):
Goal Threshold reached orientation: (1128.732,1038.74,103.48500000000001)

```

In this example, the start point is at coordinates (500, 1000, 0) and the goal point is at coordinates (5700, 1200). Please note that the coordinates should be within the dimensions of your obstacle map.



5. The script will display the obstacle map and explored nodes with the shortest path highlighted in blue.


## Customization

- You can modify the obstacle map by changing the dimensions, adding or removing obstacles, or adjusting their properties (shape, color, thickness, transparency).



## Acknowledgements

- The script is based on A* algorithm for pathfinding.
- The visualization is done using the OpenCV library.

## Results
#### Link for video files.
https://drive.google.com/drive/folders/12rcPQtiTVsFDIriFuLqxBYC4OJSL4Bi6?usp=sharing

![Video Demo](https://github.com/vijaydevmasters/ENPM661-PRJ3_PHASE2/blob/main/shortest_path_gif.gif)




