# KXR_Irec_2023
Knights Experimental Rocketry payloads resources for IREC 2023


## Structure
The payloads system of the UCF KXR 2023 IREC Hybrid Rocket will only be used for experiments, video recording/transmission, and data recording/transmission. All recovery hardware will be commercial. 

The payloads system consists of three main PCBs, each with a specialized purpose to allow for modularity. The PCBs will communicate over a CAN bus. The three PCBs are as follows:
1. Power Board: Regulate 4s Lipo to 12v, measure current and voltage and different points, control and distribute power to different systems. 
2. Main Avionics Board: Gather sensor data, record sensor data, manage data between different boards.
3. Nosecone Board: Receive GPS data, transmit/receive telemetry, control power to video RF amp. 

This repository contains the Nosecone and Power PCBs as those were the two that I designed. 
