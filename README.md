# ROS2Learning
Introductory ROS2 projects (basically from ros.org)
## Create a Workspace
## Create Packages
## Publisher and Subscriber
## Service and Client
## Custome .msg and .srv Files
### Included Packages
- <code>py_srvcli</code> and <code>tutorial_interfaces</code>: a service-client to add 3 integers and return the sum
- <code>py_srvcli_addfive</code> and <code>tutorial_interfaces_addfive</code>: a service-client to add 5 integers and return the sum
### Attention
When creating new packages from existing ones, **DO NOT** use <code>mkdir</code> to directly create an empty folder, but should use <code>ros2 pkg create</code> to create a new package, and then do the copy and paste and modification.
