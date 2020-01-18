# imageconverter

Convert images to different formats completely on the client [Convert png to jpg here](https://png-jpg.com)

## motivation

There are already tools like this online, but I noticed they all upload your files to an external server to convert them. This means:

⋅⋅*There will always be a limit on the size of the files you can convert

⋅⋅*If not secured properly, people could intercept whatever images you where sending

⋅⋅*It takes longer for most opperations since they have to be uploaded to the server first, then converted, then sent back to the client.

## building

This runs entirely on the client using canvas to draw and then save. 

just use any static file web server or even just drag the file into your browser to view.

## special thanks

The code is based off of [this](https://medium.com/@aeshghi/convert-jpg-images-to-png-using-html5-url-and-canvas-45b14ee853c9) medium post

This uses [jszip](https://github.com/Stuk/jszip) to zip the files in the zip option
