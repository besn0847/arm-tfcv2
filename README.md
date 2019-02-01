# arm-tfcv2
A container for Raspberry PI with Tensorflow and OpenCV 

To start the container with default config :
```bash
docker run -ti --name tfcv2 arm-tfcv2
```

Alternatively you can specify a data diretory so you can change model weights easily :
```bash
docker run -ti --name tfcv2 -v <data_dir>:/data arm-tfcv2 
```

Based on Raspbian Linux Stretch, Python 3.5, Tensorflow 1.11.0 and OpenCV 3.4.4

#### Dockerhub : https://cloud.docker.com/repository/registry-1.docker.io/besn0847/arm-tfcv2
x86 : https://cloud.docker.com/repository/registry-1.docker.io/besn0847/x86-tfcv2

#### Tributes
1. https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/
