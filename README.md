# KinectFusion_remake
Course Project from 3D Scanning and Motion Capture at TUM
# Latex report
[https://sharelatex.tum.de/project/639468018f773b1b855819e5](https://drive.google.com/file/d/1aVfujOK9xV2C0_E1jritoWver82ducJa/view)
# presentation file
[https://drive.google.com/file/d/1coC4pdaIsz4nukc0047swDoNcP3pVauH/view](https://drive.google.com/file/d/1coC4pdaIsz4nukc0047swDoNcP3pVauH/view)

# Project Structure

└── ProjectKinectFusion\
   ├── KinectFusionRemake\
   The git cloned folder
   │   ├── main.cpp\
   │   └─── CMakeLists.txt  
   ├── Libs 
   │   ├── Ceres
   │   ├── Eigen
   │   ├── FreeImage
   │   ├── Glog
   │   └── Flann  
   ├── Data
   └── build
You also need to have CUDA installed. The main entry point is the main.cpp file which calls the necessary methods. There is only one option now, it being the reconstruct room function. Then in this function the pose estimation and TSDF updating function will be called for every frame. Raycasting part is not finished that it is commented out.

If you do not want or think we are not going to need any file feel free to change CMakelist.txt as you wish.
