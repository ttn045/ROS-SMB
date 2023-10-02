# Exercice 1 : 

#### Voici les notions que nous allons voir ensemble dans cette exercice : 

- ROS architecture
- ROS master, nodes, and topics
- Console commands
- Catkin workspace and build system
- Launch-files 


## 🛠️ Installations
       

#### 1 - Dans un premier temps il faut telecharger le fichier [smb_common.zip](https://github.com/Elmootez-Belleh/ROS-SMB/blob/main/smb_common.zip)
#### 2 - Se positionner dans le workspace : `cd ~/catkin_ws/src`
#### 3 - `unzip smb_common.zip`
#### 4 - `cd ..`
#### 5 - `catkin_make`
#### 6 - `source ~/catkin_ws/devel/setup.bash`


## 🧐 Simulation 

#### Nous allons lancer notre simulation avec roslaunch :

#### `roslaunch smb_gazebo smb_gazebo.launch` 

![Image](https://github.com/Elmootez-Belleh/ROS-SMB/blob/main/screens/rostopicList.png]

#### Ensuite, ouvrir un vouveau terminal et tapper les commandes suivantes : 

#### `rosnode list`
![Image](screens/rosnodeList.png)
#### `rostopic list`
![Image](screens/rostopicList.png)
#### `rostopic echo clock`
![Image](screens/rostopicEcho.png)
#### `rostopic hz clock`
![Image](screens/rostopicHz.png)        
