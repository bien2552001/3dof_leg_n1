# leg_3dof
Mo ta: Hien tai da mo phong duoc tren gazebo va riviz , du lieu cho phan chuyen dong cho cac khop dung file "csv" (xuat tu matlab)

# Run
## B1: Tim den thu muc leg_3dof dung lenh: cd ~/leg_3dof
  + Chay cac lenh sau de tao moi truong va build goi ROS1 Noetic : 
  + source /opt/ros/noetic/setup.bash
  + catkin_make
  + source devel/setup.bash
## B2: Chay cac goi pkg sau:
- Mo terminal moi, Run cac lenh B1 va run: roslaunch leg_gazebo leg_robot.launch  (Lenh nay khoi tao moi truong mo phong gazebo)
  (Chu y: Nhan nut Realtime o goc trai duoi cung) <ins>Đây là phần chú ý được gạch chân.</ins>
- Mo terminal moi, Run cac lenh B1 va run: roslaunch leg_gazebo leg_control.launch (Them phan dieu khien cac khop )
- Mo terminal moi, Run cac lenh B1 va run: roslaunch leg_rviz1 leg_rviz.launch ( Khoi chay moi truong mo phong rviz1)
