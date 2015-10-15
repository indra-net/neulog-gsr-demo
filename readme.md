## neulog GSR demo

connect your Neulog GSR device, then `python producer/neulog.py`. 

the python script reads the numbers from the neulog GSR sensor and streams them
over the web using Pusher

then on the client side you can use a PusherClient to listen for the data

on the client side right now there is a lot of stuff about playing a song. if you just want GSR data you can ignore this and just look for the line that says 'GETTING THE GSR VALUES' and that is the code you need. we'll probably take out the audio stuff soon.
