# Grid score repository
<img src="https://user-images.githubusercontent.com/16649631/85288620-ef83c480-b48d-11ea-9904-d9dacfb3c110.jpg" width="300">

## Motivation
Different research groups use different algorithms to identify grid cells, which leads to different classifications and overall results.

- I would like to collect and implement different published grid scores to be able to compare them and decide which one to use.
- I'm very interested in why different labs use different grid scores and the reasons for choosing a given implementation so I would like to collect opinions.

## Ways to contribute

- Add a grid score implementation. Please try not to add duplicates, but anything that is slightly different (or is implemented in a different programming language / much faster) is great. If your code doesn't work on the example data frame I added then please either add an example cell or simulate data if possible.
- Convert an implementation from this repo to an ipython (or some other kind of) notebook where you plot some of the intermediate steps and add some text to explain what is happening.
- Add some sort of visualization that compares two or more implemented grid scores.
- Anything else that you think could be useful for someone trying to decide which grid score to use!

Thank you!



## Links to other repositories with grid scores

### Spike level grid score [10.1371/journal.pcbi.1006804]
https://gitlab.tubit.tu-berlin.de/simonweber/gridscore

some files missing from the above that are needed for it to run:
https://simonweber@gitlab.tubit.tu-berlin.de/simonweber/general_utils

### Fourier based grid-tuning index
https://senselab.med.yale.edu/ModelDB/showmodel.cshtml?model=262356#tabs-1

## List of papers with different types of grid detection
Bootstrap ratemaps by resampling spikes with replacement instead of more standard shift in time:
Savelli, Francesco, J. D. Luck, and James J. Knierim. 2017. “Framing of Grid Cells within and beyond Navigation Boundaries.” eLife 6 (January). https://doi.org/10.7554/eLife.21354.

Comparison of shuffling procedures:
Barry, C., and N. Burgess. 2017. “To Be a Grid Cell: Shuffling Procedures for Determining ‘Gridness.’” https://doi.org/10.1101/230250.

Compute grid scores at multiple radii from autocorrelogram:
Langston, Rosamund F., James A. Ainge, Jonathan J. Couey, Cathrin B. Canto, Tale L. Bjerknes, Menno P. Witter, Edvard I. Moser, and May-Britt Moser. 2010. “Development of the Spatial Representation System in the Rat.” Science 328 (5985): 1576–80.

Fourier‐based measure—the grid‐tuning index:
D’Albis, Tiziano, and Richard Kempter. 2020. “Recurrent Amplification of Grid‐cell Activity.” Hippocampus 13 (October): e1005782.



