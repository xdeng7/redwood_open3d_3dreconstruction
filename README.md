# Redwood Open3D 3D Reconstruction
An example project using Open3d for 3d reconstruction with RGB-D images
This is implemented by using the open-sourced tools [Open3D](http://www.open3d.org/). Souce code is available at (https://github.com/intel-isl/Open3D)


**System requirements:**

* Ubuntu 16.04 (not support 16.04+)
* Anaconda 4.7.11
* Python 3.6
* OpenCV
* Open3D 0.9.0 (not support 0.9.0+)

## Set up environment

```bash
# Clone the project to local machine
$ git clone https://github.com/xdeng7/redwood_open3d_3dreconstruction.git

# Set up dependency, need to install Anaconda first
$ sh requirements/install.sh

```
## Download data
Any RGB-D dataset should work. In this repo, the open-sourced dataset Redwood is used.
Data can be download at (http://redwood-data.org/3dscan/dataset.html).
