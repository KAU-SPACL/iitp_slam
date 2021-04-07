# iitp_Exploration


- - -
## Empty Space Detection + A*

### waypoint_generation_ptHCloud_mapdata_filtering_final    
Subscribe pointcloud data, position and publish 3D A* path   
Main ROS topic : /rtabmap/cloud_map, /rtabmap/odom => /optimal_path_x, y, z 
![waypoint_generation_ptCloud_mapdata_filtering_final](https://user-images.githubusercontent.com/41814103/113669415-b354e400-96ee-11eb-987f-e9fd88967925.png)


### depth_multiview_image_200917_r4
Subscribe pointcloud data, position and publish image of projected pointcloud.
Main ROS topic : /rtabmap/cloud_map, /rtabmap/odom => /image_front, /image_back, /image_right, /image_left

![depth_multiview_image_200917_r4](https://user-images.githubusercontent.com/41814103/113669414-b2bc4d80-96ee-11eb-9179-aefee032d8f0.png)

### ai_optimal_path_depth_201009_5_2
Subscribe pointcloud data, position, empty space image and publish 3D A* pah.
Main ROS topic : /rtabmap/odom, /octomap_point_cloud_centers, /bboxes_front, /bboxes_front, /bboxes_right, /bboxes_left
![ai_optimal_path_depth_201009_5_2](https://user-images.githubusercontent.com/41814103/113669409-b0f28a00-96ee-11eb-9719-59acbab58a91.png)


