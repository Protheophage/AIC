# AIC
Automated Image Collector - Finds and images storage devices
Finds all storage devices attached to the computer, and forensically images them to the "flag" directory "uunique_dirrr_nammme" on a destination device.

	This tool was designed to be used with a live Linux distribution. In order for this tool to function properly, the destination device must have a directory named "uunique_dirrr_nammme" located in the root directory.

	This tool was created with and tested on Kali Linux.

	This tool has been tested, and found to create images in a forensically sound manner. This means that:
	1)All devices, excluding the destination device, are mounted in a read only state.
	2)None of the files are altered from their original state.
	3)The created images are created in a raw/dd format.
4)The input device and output images are hashed for integrity.
