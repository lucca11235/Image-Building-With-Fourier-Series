## Project Name & Pitch

Image-Building-With-Fourier-Series

Fourier Series is a technique used to decompose a periodic signal into complex exponentials. Complex exponentials are essentially a combination of cosine and sine functions, which can be thought of as rotating vectors. When applied correctly, this technique can be used to create beautiful and artistic images. The idea is to 'connect' many rotating vectors, tip to tip, and let each vector rotate at its own frequency. If the last vector has a 'pen' that is drawing a line, this line can create any image you desire.

In summary, Fourier Series decomposes a signal (such as an image) into complex exponentials (rotating vectors) that, when summed together, recreate the original signal. The goal of this project is to implement this idea using python. The code I wrote takes an SVG image as input, understands it as a signal, applies the Fourier Series technique, and creates a visualization using Matplotlib.


## Project Preview


![Screen Recording 2023-01-27 at 14 03 56](https://user-images.githubusercontent.com/91396656/215154634-e7140b66-378f-4eae-b1ee-04af31368604.gif)


## Reflections


My intent with this project was to understand the concepts behind Fourier Series and Fourier Transform in greater depth. These techniques are incredibly important in signal processing, and I found the idea both challenging and beautiful.

While Fourier Series and Fourier Transform are different, the formulas are similar and the underlying idea of decomposing a signal into the frequency domain is the same.

Interestingly, the most difficult part of the project was not the implementation of the Fourier Series itself, but rather acquiring the data I needed from the SVG files. The choice of using the SVG files is natural once you know they represent the image as a collection of curves defined by mathematical functions. So getting the function that describes the path that draws the image comes basically predefined.
