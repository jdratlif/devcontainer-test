FROM oraclelinux:8

RUN dnf install -y sudo
RUN useradd -m -s /bin/bash docker
RUN echo 'docker ALL=(ALL) NOPASSWD: ALL' > /etc/sudoers.d/docker

RUN dnf install -y python3.11
