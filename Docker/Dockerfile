FROM osrf/ros:humble-desktop

RUN apt-get update
RUN apt-get install -y git && apt-get install python3-pip

RUN mkdir -p ~catkin_ws/src && cd ~/catkin_ws/src

RUN git clone https://github.com/gsupreeta/Master-Thesis---3516

RUN echo "All done"