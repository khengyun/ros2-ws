## Install

1. Prepare for ROS 2
    Please reference the [documentation](https://index.ros.org/doc/ros2/Installation/) to install ROS 2.
2. Install `Node.js`
    You can install Node.js:
    * Download from Node.js offical [website](https://nodejs.org/en/), and install it.
    * Use the Node Version Manager ([nvm](https://github.com/creationix/nvm)) to install it.
3. Clone and install dependencies
    Note that a ROS 2 installation has to be sourced before installing dependencies.
    ```bash
    $ git clone https://github.com/RobotWebTools/ros2-web-bridge.git
    $ sudo apt-get install ros-foxy-rosbridge-server
    $ cd ros2-web-bridge
    $ source /opt/ros/foxy/setup.sh  # or a source installation
    $ npm install
    ```
