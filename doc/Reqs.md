## General requirements

1.  The plugin should be available only after running the Debug mode;

2.  Must include 2 viewing modes: 

	* Mode 1 - values ​​of matrix elements of each channel (for 2, 3, 4 channel images); 
	* Mode 2 - viewing of the actual image (i.e. picture).

3.  Ability to switch between modes;

4. Since there is not enough space in the *Debug Toolbar* to sweep large images, it is necessary to display them in a separate window with the necessary number of buttons for switching modes.

5.  Can use *QImage* and *QTable* widgets to output *cv::Mat*;

	* *QTable* - output image matrix in the form of several tables for each of the channels; 
	* *GImage* - the output of the actual image;
	
6. Since it is impossible to directly display *cuda::GpuMat* on the screen, it is necessary to unload the matrix from the *GPU* to the *CPU*, and then output to the *QImage* or *QTable*.