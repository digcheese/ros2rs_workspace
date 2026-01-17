# Usage
A [ros2_rust](https://github.com/ros2-rust/ros2_rust) VScode devcontainer template.

# Notes
- Currently the devcontainr runs as root. After copying this template make sure to add another user into the devcontainer Dockerfile to fix file permissions.
- For more information about creating, building, and running packages, refer to the https://github.com/ros2-rust/ros2_rust repository.
## Building
Before building your pacakges with `colcon` make sure to run `source /opt/ros/humble/setup.bash`
