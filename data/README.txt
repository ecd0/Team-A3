
lenovo_camera_in.xml represents the inputs to the calibration file.
	- Calibration pattern described what image would be used.
		- SIze needs to be checked.
	- Measure the size of the squares (in whatever unit you prefer, or make them up if you want. This is where they are defined)


lenovo_camera_out.xml represents what the output of the calibration is. 
	- Copy in the distance coefficients and camera matrix into the relevant matrices in BalloonFinder()