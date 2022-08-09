# Description

Simple script to evaluate the effects of different joint levels on the whole robot.
Publishes DisplayRobotState based on /joint_states + noise

# How to use

upload a `cfg/*.yaml` to the nodes private namespace and start the script `scripts/simulate_joint_noise`.
Subscribe a RobotState rviz display (from MoveIt) to topic `/robot_state_noisy`.
