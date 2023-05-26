# **Traffic Light Detector**

### Objective
Detect the traffic lights with TensorFlow Obeject Detection Api, and then
use image processing technique to classifer the state of the traffic lights.
If the lights are "red" or "yellow", it outputs command "stop"; If the
 lights are "green", the it outputs "go".


#### 1. How to install Dependence:


* [environment-gpu.yml](environment-gpu.yml) environment file with GPU


#### 2. How to run the code

```sh

python main.py

```

```sh
# where commands = [True, False...], and True: go, False: stop

commands = detect_traffic_lights(PATH_TO_TEST_IMAGES_DIR, MODEL_NAME, Num_images, plot_flag=False)

```

#### 4. An example

A very simple network is used here:

![][image1]

[image1]: ./example/img_5.jpg

##### Output command:

```sh

stop

```
