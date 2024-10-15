# VoronoiConverter

It simulates a pointillistic effect by using a mathematical construct known as a Voronoi Diagram, generated from randomly selected points within the photograph. The image is partitioned using a technique akin to the classic Flood Fill algorithm, but initiated from multiple points at once. The fill from each center halts when it encounters an area of the image that has already been filled.

Note that you must have ImageMagick installed if you’re developing on your personal machine.
