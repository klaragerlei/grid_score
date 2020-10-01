I'm currently trying to decide which grid score to use. 
I previously used the grid score implemented based on:
Krupic et al. Grid cell symmetry is shaped by environmental geometry. (doi:10.1038/nature14153)

My implementation for this is in https://github.com/klaragerlei/grid_score/blob/master/grid_score.py

To identify grid cells I set a conservative threshold (0.4) and did not do any shuffling. With this method, I found
several cells that look like they might be grid cells, but had low scores.