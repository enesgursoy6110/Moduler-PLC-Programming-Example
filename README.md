# Moduler_PLC_Programming
Advenced Moduler PLC Programming

[Linkedin Trailer Video Link](https://www.linkedin.com/feed/update/urn:li:activity:6822566829710417920/)

I am sharing the PLC software and Factory IO scene of the project I realized as an example of PLC Programming techniques in my GITHUB account.

Modular and Structure Text(ST) Programming techniques make large projects more comfortable and readable, with the ease they provide during development and subsequent expansion as well as debugging.

In this video, I first showed Soft Stop and then Pick and Place's sensor failure status in software design and reset process.

In order to add stations to the beginning or end of the project I shared, you should create your own Devices under the Units title using the Generic Feedback class, and then call them in the GenericDevices section under the PLC Main Program and make the Input Output assignments. Here, the device's fault status is followed. Then you can check the running or stopping status of Generic Devices here by typing scenarios under Station. You also need to call the Station FBs under Stations under PLC Main Program.
