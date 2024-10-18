# ros2-intro-task

## 1. Setup

In the root folder, run the following commands:

```rosdep install -i --from-path src --rosdistro humble -y```

```colcon build```

## 2. Run the talker
On a new terminal, in the root project folder, run the following commands:

```. install/setup.bash```

```ros2 run cpp_pubsub talker```

## 3. Start listening
On a new terminal, in the root project folder, run the following commands:

```. install/setup.bash```

```ros2 run py_pubsub listener```
