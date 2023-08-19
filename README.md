# leg_3dof
_**Mo ta**:_ 
+ _Hien tai da mo phong duoc tren gazebo va riviz , du lieu chuyen dong cho cac khop dung file "csv" (xuat tu matlab)_  
+ _Phan chuyen dong chua duoc muot ma, can chinh them cac thong so_
# Video Demo
https://github.com/bien2552001/leg_3dof/assets/128835452/3cef4f38-40c2-4f5e-bb86-40f7a14c5977

# Run
### B1: Tim den thu muc leg_3dof dung lenh: ```cd ~/leg_3dof``` 
  + Chay cac lenh sau de tao moi truong va build goi ROS1 Noetic : 
  + ```source /opt/ros/noetic/setup.bash ``` 
  + ```catkin_make ``` 
  + ```source devel/setup.bash ``` 
### B2: Run cac goi pkg sau:
- New terminal, Run cac **B1** va run: ```roslaunch leg_gazebo leg_robot.launch ```  (Lenh nay khoi tao moi truong mo phong gazebo)  
_<ins><font color="red">*Chu y: Nhan nut Realtime o goc trai duoi cung*</font></ins>_
- New terminal, Run cac lenh **B1** va run: ```roslaunch leg_gazebo leg_control.launch ``` (Them phan dieu khien cac khop )
- New terminal, Run cac lenh **B1** va run: ```roslaunch leg_rviz1 leg_rviz.launch ``` ( Khoi chay moi truong mo phong rviz1)
### B3: Chuyen dong voi du lieu tu file csv
- New terminal : ```cd ~/leg_3dof/src/demo/leg_gazebo/scripts ```==> Run: ```python3 leg_read_csv.py ```
