This project was originally made for my spring 2025 senior design class
Updated by Ethics Mom 2025/3/25

The code takes in a TIF file, the source used is VIIRS Nighttime Lights data
units: nW/cm2/sr

run code block 1 & 2

settings are in code block 3
check lifespan, samples, and res as those contribute to calculation time greatly
be sure to keep res in a 1:4 ratio

code block 4
set imagein to your desired ground map
set coordinates within the image

code block 5
once settings are in place let it run, depending on setting it may take a long time so start small

code block 6
exports
It outputs a png, the gain is just so that you can see the image, since night is dark
it also saves a file of the sum of the RGB wavelengths in Cd/m2, though this can be easily changed by some code manipulation
