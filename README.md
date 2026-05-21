# optical_analysis_pipeline
An optical analysis pipeline to analyze image targets sources pre/post functional tests.

The code runs the P/F crtieria following the below:

Pinhole Panel:
1. The volume under the curve of ADU (Analog-to-Digital Unit) vs. x and y. This must be within 10% of a PSF model with infinite slope.
2. The radial average of slope for our ADU plot. This must be less than or equal to 10% of our ideal PSF
3. Asymmetricness of PSF slope: The area of the subtraction between the absolute value of both sides shall be less than 10%

Colour Aberration Panel:
1. The amount of colour bleeding shall be limited to 144 pixels

Checkboard Panel:
1. The area of the greyscale of the subtraction between the ideal chalkboard and the test chalkboard shall be less than 10%

Siemens Star Panel:
1. TBD