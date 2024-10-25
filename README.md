# Lissajous Figures

![Screenshot of Lissajous Figures](https://github.com/yeri63-hp48g/Lissajous-Figures/blob/main/Lissajous.png)

Lissajous figures can be generated using an oscilliscope, an electrical instrument for viewing electrical signals using images instead of numerically, as I was accustomed to using a voltmeter. Oscilliscopes are extremely useful for studying signals, displaying straight lines for D.C. (Direct Current), sinusoidial curves for A.C. (Alternating Current), and short bursts of square waves (Digital 1's and 0's). Sinusoidial, or sine waves are the signals needed for generating Lissajous images, supplying one for the x-axis, and the other for the y-axis, after placing the oscilliscope in X-Y mode.

The basic premise is generating these images using 2 sinusodial waves, both with frequencies matching a fixed ratio, which in turn determines which Lissajous figure will be produced. Each ratio produces a different figure. For example, a 1:1 frequency ratio produces a diagonal line. Shifting one of the signals by 90 deg produces a circle. The number of degrees shifted determines the state of the image as it changes from a diagonal line to circle, and then back again. This shift gives the illusion of a figure being rotated about an axis.

To give depth to these normally static images, this program slowly shifts the position of one signal, making the image rotate clockwise and counterclockwise, updwards and downwards, all at the same time. The direction of movement is determined entirely by the observer, and which part of the figure is being tracked by the eyes.

The application begins by displaying an initial a:b ratio, with a menu to add or delete either value. Pressing the Draw button then creates the Lissajous Figure created by this ratio, and slowly rotates it. This continues until any key is pressed, to return back to the ratio screen, where a new value can be entered. 

Here's an example from Wikimedia.org showing some of the possible Lissajous Figures you'll be able to observe within the app based on ratio and degrees shifted between the signals. They used radians to indicate shift where 180 deg = pi radians.

![Lissajous Relations](https://github.com/yeri63-hp48g/Lissajous-Figures/blob/main/Lissajous_relaciones.png)
