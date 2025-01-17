# Model Overview

## Introduction

The Light Plate Apparatus (LPA) is a device that we built to measure parameters for the model. The LPA would be used to measure single cell fluorescence and its response to different intensities of red light and different on/off times by controlling the experiments.

## Building and Calibrating the LPA

To run experiments to gather data for the model, we built a device that can precisely control the intensities of red LEDs shone on 24-well plates, with each LED corresponding to a single well. Based on the Tabor Lab’s Light Plate Apparatus, it is simpler, cheaper, and more tailored for our needs. We built the LPA using extenders, LEDs, light meter, a 3D printed LPA chassis, and a soldered 24 pin board for LEDs. To measure LED light values for the model, we created code and set up a light sensor using Raspberry Pi. Unfortunately, the Raspberry Pi stopped working, so we used an Arduino to set up the LPA. Using the Arduino, we set up the LPA with working LEDs. By measuring the light values, we determined that our LEDs fit LED #14 K values from the paper, so we decided to run a model with those values. 

## Code

We went through Tabor’s code and changed some variable names, commenting the code accordingly. We ran the code from the Tabor paper to create a model from the parameters they used on Tellurium. If we had the data from Wetlab, we could have essentially created a model to reflect our system. 
