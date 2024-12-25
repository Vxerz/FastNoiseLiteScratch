# FASTNOISELITE EXTENSION
*I DID NOT MAKE THE PERLIN NOISE*
i simply made it a scratch extension

for the noise i used go here:
https://github.com/Auburn/FastNoiseLite

## HOW TO USE
you need to create noise before you can use it, once created you can use the "get noise" with the ID you used in the create noise block
get noise gives the value for the noise at any coordinate
you can have as many different noises as you want, aslong as they all have unique iDs, if you use the same ID twice it will overwrite it.
### CREATE NOISE
ID: this is a label for this noise, you must include an id for you to be able to use it

TYPE: this is the type of noise you will use, im not going to describe them

OCTAVES: how much detail in the noise

FREQUENCY: the size of the noise, *KEEP A VERY LOW NUMBER (0.0001 - 0.1)*

SEED: the seed for the noise, the same seed will always give the same noise


### GET NOISE
ID: the ID of the noise you created

X: the X position

Y: the Y position

Z: the Z position
