# achrails-dev-Dockerfiles

These are settings for creating development environment for Achrails inside Layers Box.

This will create 2 containers, where one is postgres and the other is a stub of achrails -- Ruby on Rails and all necessary gems prebuilt, but no code to run. In the container the code is linked to ../achrails, relative to Layers Box instance's location in host machine.

Instructions for using this are in https://github.com/learning-layers/achrails#installing-for-development-with-layers-box 

The environment configuration should come from common.env (from LayersBox, not here) and achrails.env (here). 

Created by Jukka Purma, based on https://github.com/learning-layers/achrails-Dockerfiles
