# Calibration_of_two_cameras ( artificial vision )
Calibration of two Cameras using a projection model center (pinhole model). 

# The objective
The objective is to calibrate a camera using a projection model center (pinhole model). The calibration will be done with the linear model allowing the representation of the camera
# calibration.ipynb
This calibration technique will make it possible to calculate the matrix M from a set of points given in (mypoints.csv) The data file contains the 3D/2D correspondence list, the 3D point of the world real and its 2D projection on the image plane. The first three values are the coordinates (X, Y, Z) of the 3D point in the image and the next two are the coordinates (u, v) of the 2D point in the image.

# calibration2cam.ipynb
Now that the calibration of a camera is already done (calibration.ipynb). It is possible to calibrate a second camera in the same way. The calibration of each camera is done by relation to the same object whose acquisition is made simultaneously by the two cameras
