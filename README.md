# Draw Anything using Fourier Series

Fourier series named after the French mathematician and physicist Joseph Fourier (1768-1830) is a technique to approximate/reconstruct any signal using combinations of sine waves and cosine waves and on the basis of superposition principle. For any periodic function $f(x)$ defined in interval $(-L, L)$ the Fourier series is calculated as - 

$$ f_{approx}(x) = \frac{a_0}{2} + \sum_{n=1}^{\infty} \left( a_n \cos \left( \frac{n \pi x}{L} \right) + b_n \sin \left( \frac{n \pi x}{L} \right) \right) $$

Where 

$$ a_n = \frac{1}{L} \int_{-L}^{L} f(x) \cos \left( \frac{n \pi x}{L} \right) dx$$
$$ b_n = \frac{1}{L} \int_{-L}^{L} f(x) \sin \left( \frac{n \pi x}{L} \right)   $$

The Fourier series is more convenient to write using imaginary numbers. If $f(x)$ is the function that we are trying to reconstruct then the Complex Fouries Series is -

$$ f_{approx}(x) = \sum_{n= -\infty}^{\infty}  c_n e^{i n \pi x/L} $$

Where $i = \sqrt{-1} $ and $$c_n = \frac{1}{2L} \int_{-L}^{L} f(x) e^{- i n \pi x /L}$$

This concept can be used to make epicycles to draw anything. Here you can upload an svg file, modify the code and see the animation drawing you the image you gave.
