# Touchdesigner and Mediapiper

## Hands

---

Simple example using [mediapipe](https://mediapipe.dev/) to extract finger position.
Using OSC to send all the marks from python script to touchdesigner toe.

At TD, only one finger selected, but you can use all the marks.

The marks transform a metaball position and interact with lines.

To see better the finger in TD, put the same video in at the scene.

---

Mediapipe split the hand wit this marks:

![imagen de las marcas](image/hand_landmarks.png)

I use only 8 landmark (index_finger_tip)

---

![gif funcionando](image/hand.gif)

---

## Credits

[Touchdesigner](https://derivative.ca)

[Mediapipe script](https://google.github.io/mediapipe/solutions/hands.html)

[Mediapipe tutorial](https://learnopencv.com/introduction-to-mediapipe/)

[@Tolch.AV lines toe](https://www.youtube.com/watch?v=QUBSNq1JT2c&ab_channel=Tolch)

[OSC python library](https://pypi.org/project/python-osc/)