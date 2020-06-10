# Velodeny

Simuluate the Velodeny in Gazebo

xxxxxx.config 
Create the xxxxxx.config file. Each model requires some meta information that describes the model, the author, and any dependencies.

xxxxxx.sdf  
This xxxxxx.sdf file will contain the description of the Velodyne laser.

xxxxxx.dae   .dae is the <mesh> of the model, which means it contents the appearance of the model.
eg:
<mesh> 
<!-- The URI should refer to the 3D mesh. The "model:" URI scheme indicates that the we are referencing a Gazebomodel. -->
    <uri>model://velodyne_hdl32/meshes/velodyne_top.dae</uri>
</mesh>
