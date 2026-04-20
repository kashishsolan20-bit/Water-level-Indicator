# Introduction

A water level indicator is a simple yet effective system used to monitor the level of water in a storage tank. It helps in preventing water overflow and ensures efficient water management by providing real-time indication of the water level. These systems are widely used in households, industries, and agricultural applications due to their reliability, low cost, and ease of installation. The working principle is based on the conductivity of water, which allows the system to detect different levels using sensors and display them through indicators such as LEDs.

## Circuit Working

This circuit not only indicates the amount of water present in an overhead tank but also provides an indication when the tank becomes full. It makes use of the CD4066, a widely available integrated circuit, to control the indication of water levels through LEDs.

When there is no water in the tank, the sensor wires remain open-circuited. Due to this, the 180K resistors pull the switches to a low state, keeping them open, and as a result, all the LEDs remain turned OFF. As the water starts filling the tank, it begins to act as a conductive medium. When the water reaches the first sensor level, it connects the probe associated with switch S1 to the positive supply, thereby closing the switch and turning ON LED1.

As the water level continues to rise, it sequentially connects the remaining probes placed at higher levels inside the tank. This results in the gradual activation of switches S2, S3, and S4, which in turn causes LED1, LED2, LED3, and LED4 to glow one after another. When the water reaches the highest level, all the LEDs are turned ON, indicating that the tank is completely full.

