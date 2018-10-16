# ROS_mbot_description
* 这是我修改相关代码所实现的基于ROS中的仿真机器人，其中有urdf以及xacro两个版本的，基本上模型都是一样的，只是变换了两个版本，所以通过这个例程，可以让我们更好掌握这个仿真的工具
** 其中跟之前的ROS包类似，我都会将一些现在暂时用不到的包放里面，一方面是为了给之后的包做铺垫，另一方面这样也可以给一些刚入门ROS的人一些更多的信息
* 其中launch文件当中，分了urdf以及xacro两种，是对应urdf当中的两个包
** 运行roslaunch mbot_description display_mbot_base_urdf.launch，这是一个没有添加传感器的小车模型。另外有一个display_mbot_with_kinect_urdf.launch这个文件，是添加了kinect传感器的模型，这个模型是通过加载kinect相关的纹理，来实现跟现实中的kinect传感器相同的模型
* launch中的xacro当中有比较多的包，不过基本上都与urdf的类似
** 运行方式跟上面一样，都是通过launch相关的包，就能够看到装有不同传感器小车的模型
#### 之后会提供相关的gazebo包，用于在gazebo环境下实现机器人模型的显示
