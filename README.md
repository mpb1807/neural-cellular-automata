# neural-cellular-automata
My code for training a neural cellular automaton to form a target image.

<p>Here is the target image:</p>
<img src="cat-face-emoji-2048x1821-x3kf878r.png" width=200 height=200>

<p>Here is the result of my trained model:</p>
<video src="https://github.com/user-attachments/assets/8e0264af-2ea6-4efb-a876-0e6af5183fc8" width=400 height=400>

The 'state' begins as a 200x200 black image with the central pixel being white.

To step the state, the model is called on the image, then the output of the model is added to the image. The image is then clipped to the \[0, 1\] range.

