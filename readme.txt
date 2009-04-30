Quartz Media Server Art-Net Specification:

DMX 1 - Video Bus A File 
	Range: 0-255
	Description: Reads the videos.xml file an gets the user specified 
			images. File 1 will be the item in the XML file with the id 
			of 1.
			
DMX 2 - Video Bus B File
	Range: 1-255
	Description: Reads the videos.xml file an gets the user specified 
			images. File 1 will be the item in the XML file with the id 
			of 1.

DMX 3 - Transition Type
	Range: 0-3
	Values:
		0) Desolve
		1) Circles
		2) Copy Machine
		3) Flash
	
DMX 4 - Cross Fade
	Range: 0-255
	Description: 0 meaning 100% Video Bus A and 255 being 100% Video Bus B
	
DMX 5 - Hue
	Range: 0-255
	Default: 127 (This is 0 hue adjustment)

DMX 6 - Saturation
	Range: 0-255
	Default: 127 (This is 0 saturation effect +/- would saturate or de-saturate respectively)
	
DMX 7 - Brightness 
	Range: 0-255
	Default: 127 (This is default files default brightness)
	
DMX 8 - Contrast
	Range: 0-255
	Default: 127 (This is default contrast)