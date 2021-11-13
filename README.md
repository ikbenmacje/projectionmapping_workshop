# projectionmapping_workshop

This is a repository with the working files for an Isadora projeciton mapping workshop.

## materiaal

Here you can fond some images and videos to use as test material

## mappingServer.izz

This is the master file that will run on the computer that is connected to the projector.
The only two functions function of this file are: 

1. recieve all relevant NDI streams and project them
2. record and play back of compositions

## mappingClinet.izz

This file is the client file that will run on all the vclient laptops.
This is the patch that can be used to play with and create a projection mapping composition.

## NOTE:

Some of these patches use the NDI wathcer which is an Isadora ddon that you can find here: https://troikatronix.com/add-ons/
