* 更改雷达的ip： 192.168.1.19
  * 可以通过windows下的专用软件，进行更改
  * 
* 如果缺少依赖， 可以通过sudo apt-get install ros-melodic-urg-node， 安装依赖
* tf变换  
`<node pkg="tf" type="static_transform_publisher" name="laser_basefootprint_broadcaster" args="0.2918 0.0 0.2333 0 0 0  base_footprint  laser 100" />`