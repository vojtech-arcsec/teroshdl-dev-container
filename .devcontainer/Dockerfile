FROM mcr.microsoft.com/devcontainers/base:ubuntu
# Following packages were installed based on following docs:
# https://terostechnology.github.io/terosHDLdoc/docs/installation_checklist/installation/
#
# A package version probably shall be specified as well - TBD
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
    

