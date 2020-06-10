# Velodeny

Simuluate the Velodeny in Gazebo

xxxxxx.config 
Create the xxxxxx.config file. Each model requires some meta information that describes the model, the author, and any dependencies.

xxxxxx.sdf  
This xxxxxx.sdf file will contain the description of the Velodyne laser.

xxxxxx.dae   .dae is the <mesh> of the model, which means it contents the appearance of the model.
    
0.Download the data into /home/username/

1. Access to the folder 

cd ~/.gazebo/models

2. creat one folder "velodyne_hdl32"

mkdir ~/.gazebo/models/velodyne_hdl32

3.copy the all the file about Velodeny into folder 

cp -r Velodyne_hdl32./ ~/.gazebo/models/velodyne_hdl32
