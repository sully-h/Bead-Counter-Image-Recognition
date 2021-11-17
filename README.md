# Bead-Counter-Image-Recognition
a script using OpenCV2 to count the number of beads in the image


## Isn't there an easier way to do this?
Yes. Use a piece of string and a ruler. Lay the string out along the length of the bead-chain. Measure this length of string. Measure the width of a bead(be sure to include the string on one side only). Divide the numbers together to find the total number of beads.

## What if I don't have a string and a ruler handy?
Download ImageJ or Fiji. Using the cross-hairs, note down the x and y coordinates of the centre of the bead-chain and the coordinates for a bead on the same axis. Multiply the difference in coordinates by 2 $pi$ to get the circumference of the bead chain in pixels. Use the cross-hairs again coordinates of the start and endof a bead including the string. Use pythagoras' theorem to determine the width of the bead in pixels. Divide by the circumference.

## So what's the point of this project

To explore computer vision in Python
