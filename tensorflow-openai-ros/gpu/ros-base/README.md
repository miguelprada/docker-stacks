# tensorflow-openai-ros

## Usage
```
nvidia-docker run -it --security-opt label=disable --security-opt seccomp=unconfined \
    --device /dev/dri --env="DISPLAY" --env QT_X11_NO_MITSHM=1 \
    --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" \
    -p 8888:8888 \
    --name "jupyter-tensorflow" \
    jacknlliu/tensorflow-openai-ros:gpu-kinetic  bash
```