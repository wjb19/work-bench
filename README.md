# work-bench
This is a collection of software/hardware experiments, especially benchmarks

## docs/jetson_bench.pdf

An article I created a couple of years ago where I detail device features and benchmark various key tasks eg., video encoding, machine learning / computer vision using camera input, BLAS/LAPACK options etc etc on Nvidia Jetson Nano. The source code including performing CUDA accelerated computer vision is available here : https://drive.google.com/file/d/1g2wXc7HHEcVpkRvioKmYJ_jsnm4Fjh7t/view?usp=sharing.

## docs/lora_swarm.pdf

Here I examined developing with a LoRa IoT device based on Wio-E5 Wireless Module (STM32WLE5JC) equipped with ARM Cortex-M4 and SX126x RF transceiver, connected with a variety of sensors whose analog response is digitized using TI ADS1115 ADCs before communication  over I2C to nodes, and subsequently via LoRa WAN to host hub (based on SX1302), before transmission to cloud using SWARM. SWARM has since been acquired by Space-X and iirc the VHF uplink is no more and replaced by cellular, but the telnet interface may still exist and the source code especially server side (for reception at bumblebee.hive) still potentially useful.

## docs/k8sKnative.pdf

Details on creating your own k8s + Knative cluster, to provide serverless support for your bursty computational workflows, with some results from testing using Google Cloud Run.

WJB 04/25
