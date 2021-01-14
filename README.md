# JS Drum Kit

JS Drum Kit is an interactive drum kit that uses reactive events, color animations, and HTML audio elements to allow users to make their own funky beats from their keyboard presses.

Visit the deployed site here: https://jsdrumkit.vercel.app/

<p align="center"><img src="https://i.imgur.com/66EE9i8.png" alt="drum_kit"></p>

## Getting Started

Once the site loads, a popup should appear asking for access to your webcam (there may be a slight delay due to facecam loading speeds);

<p align="center"><img src="https://i.imgur.com/8yLBUDZ.png" alt="webcam_ask"></p>

Look directly at your camera and start making some facial expressions!

The program will first search the webcam screen for your face using its face landmark detection. It then displays its certainty of the higlighted object being a human face in decimal form above your face.

<p align="center"><img src="https://i.imgur.com/56GJMYo.png" alt="blue_text"></p>

Lastly, it will detect what emotion you are feeling (happy, sad, surprised, etc.) relative to your facial features and display its certainty in its assumption in decimal form below your face.

<p align="center"><img src="https://i.imgur.com/FHsCUGU.png" alt="white_text"></p>

## Acknowledgements

- face-api.js library ( https://github.com/justadudewhohacks/face-api.js ), wrapper around TensorFlow (machine-learning library).
