<h1>Fourier Transformation</h1>

<h2>Description</h2>
In this project, the Fourier Transform is utilized to reconstruct an image using only sine functions via python and data modelling. The Fourier transform (FT) is a transform that converts a function into a form that describes the frequencies present in the original function. The output of the transform is a complex-valued function of frequency. When, run a series of images are output and saved that, when viewed in quick succession, visualize this reconstruction.
<br />
<p align="center">
<img src="https://github.com/andrew-disario/fourier-transformation/blob/main/generated-animation.gif?raw=true" height="40%" width="40%" alt="Fourier Transformation"/>
<h2>Languages and Libraries:</h2>

- <b>Python</b> 
- <b>Pandas</b>
- <b>Matplotlib</b>

<h2>Environments</h2>

- <b>Windows 11</b> 

<h2>Files and Links</h2>

- <b>[fourier-transformation.ipynb](https://github.com/andrew-disario/fourier-transformation/blob/main/fourier-transformation.ipynb)</b> 
- <b>[target_image.png](https://github.com/andrew-disario/fourier-transformation/blob/main/target_image.png)</b> 

<h2>Walkthrough</h2>
<p align="center">
A series of sine functions with different parameters can be used to construct any image using what's known as the Fourier Transformation. The Fourier Transformation is a method by which sine functions can model other, different functions. <br/>
<br/>
<img src="https://miro.medium.com/v2/resize:fit:1400/1*Cu-HbskjoCNXepb5tT2t7A.png" height="40%" width="40%" alt="Fourier Transformation"/>
<br />
<br />
We can use sinusoidal gratings which have grayscale values that vary according to the sine function to capture similar frequencies in a given image. <br/>
<br/>
<img src="https://github.com/andrew-disario/archive/blob/main/sinusoidal-gradient.png?raw=true" height="40%" width="40%" alt="Sinusoidal Gradient"/>
<br />
<br />
Each of these sinusoidal gratings are added together and the result is the reconstructed image. <br/>
<br/>
<img src="https://github.com/andrew-disario/fourier-transformation/blob/main/generated-animation.gif?raw=true" height="40%" width="40%" alt="Fourier Transformation Animation"/>
<br />
