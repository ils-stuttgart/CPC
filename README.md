# CPC: Cabin Pressure Controler model

## Purpose
This application was one of the first as the criticality level can be seen as quiet low and the data can be generated using simulations. For this reason a Simulink simulation was created to generate the data for the model development but also to include the final Version of the model to perform in the loop tests.



## Data
The Data, generated in a simulation, was splitted in two parts. 80 flights for training and validation and 20 flights for testing later on.


## Goal
The Cabin Pressure Controler ML model is supposed to controll the pressure within the cabine just like a normal cpc would do.
For the flight tests the cpc (GT) and the ml cpc (ML) are supposed to behave the same way as shown within the Figure.
![grafik](https://github.com/user-attachments/assets/0cd2fee9-cb1c-4396-be6f-18adceedd616)


## License
This project is licensed under the MIT License. See the LICENSE file for details.

