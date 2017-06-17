# Kinect & TouchDesigner point cloud #

Recreating point cloud based on the tutorial "TouchDesigner Kinect TOP Tutorial 1" by CutMod https://www.youtube.com/watch?v=r-EOtQhdJxg.
The Kinect sensors were positioned in front of the projection for the silhouettes and on the ceiling for room scanning. This queue point is part of a further researching for VR implementation, such as point cloud visualization over headsets and RTLS of multiple objects inside a room.

TD Version: 099 build: 2017.3580

See it in action [here](https://vimeo.com/222030937)

### How to use ###

There are three current files available:

1. Kinect3DPlayerGrid-PointCloudFX
2. Kinect3DPlayerGrid.PointCloudLuma
3. Kinect3DPlayerGrid

The first has the final setup for room reconstruction. The second one has some tweeks for the luma threshold. The third one has some little differences between the others but any of the three will do.

### Basic components ###

In order to replicate the same process to generate geometries based on the controllers position, you may only need the following components:

* Kinect [TOP] with depth image mode
* Threshold [TOP]
* Level [TOP]
* TOP to [CHOP]
* Shuffle [CHOP]
* Grid [SOP]
* Merge [CHOP]
* Geometry [COMP]

### Colaborative Virtual Reality ###

I'm currently working on a couple of researchs about changing the isolation paradigm on VR. You can check more about it on my [Medium channel](https://medium.com/@ElPepe).

