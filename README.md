# CloudRobotics-Service
the src of the Engineering part of my guaduation design   
这个是本人毕业设计做云机器人的服务的时候所用到的pkg   
c_s_cloudrobot是最主要的文件 负责agent端口和cloud的交互的，调用了其他的程序   
costmap_prohibition_layer是禁止行驶区域的pkg   
detecting_test是中间的测试工程   
my_ground_filter是用来去除地面点云的工程   
navigation-kinetic-devel我在其中做了许多关于加载我自己模型的修改   
pcl_op是对PCL的操作的工程，不是我写的。   
prohibition_msgs是用来node之间传输禁止形式区域xml文件的工程   
ros_exploring-master也不是我的，貌似是用来随机探索的控制node   
rplidar_ros，rplidar的ROS驱动文件   
xfei_asr讯飞的语音服务   
我记得我貌似还用到了turtlebot_apps中的很多东西，这个是个好东西。   
不过ORK在另一个catkin_workspace，以及二维码识别ar_avlar啥的都是通过aptget的形式得到的。   
所以只有这些文件比较难去说明其之间的关系，二进制的代码包在这里是缺省的。   
