 Background Subtraction from Image using GMM
 • We extract the background image from a given set of training frames.
 • We then use the extracted background to display foreground objects in the test frames by subtracting that back
ground image and then thresholding it accordingly.
 • We use per pixel GMMs of 2 components to perform the above task, one for foreground and the other for back
ground.
 • Technologies used: Python.
