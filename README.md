# omni_bot_model
This is the URDF Model for Omni-bot - Dr. Paul Rad's lab

To setup the package, in terminal, follow the steps below:

(1) cd ~/catkin_ws/src
(2) git clone https://github.com/asibarr2/omni_bot_model.git
(3) cd ~/catkin_ws
(4) catkin_make
(5) source devel/setup.bash
(6) roslaunch omni_bot_model omni_bot.launch

If the roslaunch is not working, make sure that the package name is "omni_bot_model" without the quotations. Also check if you sourced your workspace using "source devel/setup.bash"
