# IoT and Ambient Intelligence for realtime background music: experiments with gym athletes

## Master's degree Thesis

In this repository, you will find the slides that I used to present the project and all the related links to the different parts.

Repositories:

- [Server Tesi](https://github.com/claudiocavallaro/serverTesi)
- [Raspi Tesi](https://github.com/claudiocavallaro/raspitesi)
- [Android Tesi](https://github.com/claudiocavallaro/AndroidTesi)
- [Tesi extractor](https://github.com/claudiocavallaro/tesi.extractor)

## Server Tesi

Server part of my Master's degree thesis. It's a machine learning project that suggests the right background music depends on the effort made by an athlete.

## Raspi Tesi
This project was deployed on my Raspberry Pi 3B+. On the same Raspberry I installed an MQTT broker. Sensors based on ESP8266 publish the data on a certain topic, the springboot application on this repository subscrive to the same topic and for every payload make an http request to the server.

## Android Tesi
Android application for my master's degree thesis. It's used by people for giving preference on a certain track listened during workout.
It is basically my training set for the machine learning project.

## Tesi Extractor
Test repository which I used to try to extract the data in the right way, give to the machine learning logic and study the predict value.
