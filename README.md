
# introduction
## Download the turtle package and run 
# Implementation steps
First, we logged in to the system and opened the Terminal window (we have opened two terminal windows next to each other).
In one of these two windows, we have run the "roscore" command to start the ROS master. Now, the ROS master should be running on the system.
![image](https://github.com/user-attachments/assets/46ea634d-236f-4896-b666-8462f92f4c92)
In another session, we opened the rqt graph by using this command "rosrun rqt_graph" so we can utilize the ROS graph of our application.
![image](https://github.com/user-attachments/assets/ee4a3bf6-dc7c-4969-a5aa-e031ca5f7253)
Now, we will run the turtlesim package by using this command "rosrun turtlesim turtlesim_node". Once we execute this command, this will show a small window, and if we stop the node, this window will automatically close.
![image](https://github.com/user-attachments/assets/bbb56123-8ce5-4625-86ac-8cacc4f23181)
To see the list of currently running nodes, we run the command "rosnode list", and that will display all the nodes that are currently running. The same thing for the topics; we can display the currently running topics by running this command "rostopic list".
![WhatsApp Image 2024-07-20 at 1 12 52 AM (1)](https://github.com/user-attachments/assets/d9382ae4-3356-41d5-8198-30b24e16d143)
![WhatsApp Image 2024-07-20 at 1 12 53 AM](https://github.com/user-attachments/assets/f16fc5c4-5ea6-4149-9b57-fb413bcfcb8f)
Now, we opened another new Terminal window to check some other functions. We wrote the "rostopic echo /turtle/pose" command to see the published messages to the turtle.
![image](https://github.com/user-attachments/assets/21fd7422-26bd-43dd-b93e-071f64944cba)
Now, we are running the "rosrun turtlesim draw_square", which is already available in the package. Once we execute this command, the turtle will move in a square.
![image](https://github.com/user-attachments/assets/0285e953-cd63-4daa-b8b3-e2bc9ad36047)
