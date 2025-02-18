# AI-Tasks
Image Enhancer writeup

# PyQt5 Photo Editor<br>
<br>
This is a simple yet powerful photo editor application built using PyQt5 and OpenCV. The application allows users to adjust the brightness, apply a blur filter, and sharpen images. The project demonstrates how to create a graphical user interface (GUI) for image processing tasks using PyQt5, along with integrating OpenCV for real-time image manipulation.

Features<br>
<br>
•	Brightness Adjustment: Users can increase or decrease the brightness of an image using a vertical slider.<br>
•	Blur Filter: Users can apply a blur filter to an image with adjustable intensity using a vertical slider.<br>
•	Sharpen Filter: Users can sharpen an image using a vertical slider.<br>

Implementation Details -<br>
<br>
Brightness Adjustment<br>
<br>
•	Utilizes the changeBrightness function to adjust the brightness of the image.<br>
•	Converts the image to the HSV color space and modifies the V (value) channel.<br>
•	Re-converts the image back to the BGR color space for display.<br>
<br>
Blur Filter<br>
<br>
•	Utilizes the changeBlur function to apply a blur effect to the image.<br>
•	Uses OpenCV's cv2.blur function with an adjustable kernel size.<br>
<br>
Sharpen Filter<br>
<br>
•	Utilizes the changeSharpness function to sharpen the image.<br>
•	Applies a custom kernel to enhance the edges and details in the image.<br>

<br>
<br>
Only the above three features are added to the application.<br>
The code for the features BLUR and BRIGHTNESS was referred to the YouTube channel 'PyShine'.<br>
The code for SHARPNESS was then implemented from the knowledge and idea gained from doing the previous codes.<br>
Initially when the the code had only two features, it worked perfectly. But after adding the third feature it didn't gave the result properly. I am still trying to figure it out.<br>
I am attaching the photos of the working of the code for BLUR and BRIGHTNESS as the code for SHARPNESS is not working properly.<br>

