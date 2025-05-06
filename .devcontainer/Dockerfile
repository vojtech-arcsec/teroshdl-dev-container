FROM mcr.microsoft.com/devcontainers/base:ubuntu
RUN \
    apt-get update && apt-get upgrade -y \
    && apt-get -y install \ 
        make \
        ghdl \
        gtkwave \
        python3-pip \
    && pip3 install \
        vunit-hdl \
        edalize \
        yowasp-yosys \
        cocotb
    

