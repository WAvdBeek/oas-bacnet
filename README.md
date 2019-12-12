# oas-bacnet


# intent of the models

The models described are BACnet models, using the Open API Specification.
https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md

The models described are intended for small end devices, e.g. sensors and actuators.

The set a subset of Basic Device Object Types and Simple Value Object Types that represent actual values in the system.

note that set of models is subject to change, depending on demand.

# usage of the models 
These models can be used to create an OCF secure server with BACnet as modeling language.
The tool chain for doing so is available at: https://github.com/openconnectivity/IOTivity-Lite-setup

To generate code for these resources (after installing the tool chain):

Place the files in /IOTDataModels folder
Adapt the example.json file to include the resource rt that you want to use.
Generate the code