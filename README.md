# Steganography_Web_App
A web app that lets you hide/discover pictures inside other pictures. In the future I intend to make the algorithm more general and polish the interface.


- I have 2 pictures in this repo: "landscape.jpeg" and "colors.png" to provide a demonstration of the application. Just set the app up and open the html on your browser, there you can the read the instructions of the app by clicking the question mark.
- Essentially, colors.png will be hidden inside landscape.jpeg(The server does the hiding).
- Then the picture with the hidden image is downloaded to the client.
- In case the client wants to uncover the original picture, it only has to send the hidden picture back to the server, the serve will uncover the hidden picture and send it back to the client.
