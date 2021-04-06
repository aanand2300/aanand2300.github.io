---
title: "A secure inter-domain communication for IoT devices"
collection: publications
permalink: /publications/ASCIoT
venue: '2019 IEEE International Conference on Cloud Engineering'
date: 2019-06-24
citation: '<b>Anand, A.</b>, Galletta, A., Celesti, A., Fazio, M., & Villari, M. <i>2019 IEEE International Conference on Cloud Engineering (IC2E)</i> (pp. 235-240). IEEE'
---

[[PDF]](https://ieeexplore.ieee.org/iel7/8785949/8789886/08790098.pdf?casa_token=4VXgeMjuXvoAAAAA:Ox_GAAqMtXHqLmXof9yYYtIgSXX0zSWlygcnavQWxqHSGmu1xPjBBgOo8bd_vxJQF9-t1VvSIbNt)

## Abstract
Nowadays, a multitude of sensors are used to gather data in several fields from smart buildings, to industries, to cars, etc.. These sensor data are instrumental in making smart decisions. In order to send data to end users, these sensors are connected to the Internet of Things (IoT devices. Usually, the intra-domain data transmission is secure, indeed sensors and consumers of data can belong to the same Virtual Private Network (VPN). Security problems can be raised in the interdomain data transmission because the transmitting channel is not ciphered nor is the identity of devices certain. Therefore, in case of attack, for consumers of data is not possible to recognize real data gathered from devices from fake data sent by attackers. In order to address this challenge, in this paper we present a novel method to secure data acquired from sensors connected to IoT devices. In particular, utilizing a Public Key Infrastructure (PKI) and the ESP32 microcontroller, we can send data privately to each recipient. In order to validate the system, we performed specific analysis considering different levels of security (512, 1024, 2048 bits key length) and increasing number of connected sensors (0, 1, 5, 10, 20). In particular, we considered the time to set up the IoT device and to cipher packets. Experiments have shown that the time required for the setup increases with the increase of the key length. Considering the 512 and 1024 bits keys, the time required to cipher data coming from sensors increase with the increasing of sensors. Instead, for the 2048 bits key length the ciphering time is almost constant, this because packet size and key length are comparable.