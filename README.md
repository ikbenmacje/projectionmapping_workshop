# projectionmapping_workshop

This is a repository with the working files for an Isadora projection mapping workshop.


## mappingServer.izz

This is the master file that will run on the computer that is connected to the projector.
The only two functions function of this file are: 

1. recieve all relevant NDI streams and project them
2. record and play back of compositions

## mappingClient_light.izz

This file is a "light" version of the client file that will run on laptops with no dedicated graphical card.
This is the patch that can be used to play with and create a projection mapping composition.

## mappingClient.izz

This file is the client file that will run on all the client laptops.
This is the patch that can be used to play with and create a projection mapping composition.

## materiaal

Here you can fond some images and videos to use as test material

## test

In this directory you can find some projection mapping test files to test various hardware conditions.

## NOTE:

- These patches are made and tested on Isadora 3.1.1 (Windows 10 & OSX 11.3.1)
- mappingClient.izz needs some Isadora add-ons in order to work. The addons are:
	- TT FFGL https://troikatronix.com/add-ons/tt-ffgl-for-isadora-2-3/
	- TT GLSL shaders https://troikatronix.com/add-ons/tt-glsl-shaders-for-isadora-2-3/ 
- mappingServer.izz needs some Isadora add-ons in order to work. The addons are:
	- NDI Watcher https://troikatronix.com/add-ons/ndi-watcher/
	
