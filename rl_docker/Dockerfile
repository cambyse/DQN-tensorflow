FROM nvcr.io/nvidia/tensorflow:17.10
RUN apt-get update && apt install -y libsm6 libxext6
RUN apt-get install -y cmake
RUN pip install gym[atari]
RUN pip install tqdm
RUN pip install opencv-python
