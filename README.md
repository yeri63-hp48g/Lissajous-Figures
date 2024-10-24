# Lissajous-Figures

![Screenshot of Lissajous Figures](https://github.com/yeri63-hp48g/Lissajous-Figures/blob/main/Lissajous.png)

Lissajous figures can be generated using an oscilliscope, an electrical instrument for viewing electrical signals using images instead of numerically, as I was accustomed to using a voltmeter. Oscilliscopes are extremely useful for studying electrical signals, straight lines for D.C. (Direct Current), sinusoidial lines for A.C. (Alternating Current), and short bursts of square waves (Digital 1's and 0's). Sinusoidial, or sine waves were the signals needed for generating Lissajous images, one for the x-axis, and another on the y-axis, after placing the oscilliscope in X-Y mode.

The basic premise is generating images using 2 sinusodial waves, where their frequencies are maitained at a fixed ratio, which in turn determines which Lissajouse image will be generated. Each ratio produces a different figure. For example, a 1:1 ratio of frequencies will produce a diagonal line. Shifting the time of one of the signals by 180 deg produces a circle. The number of degrees shifted determines the position in space between the images resemebling a diagonal line and circle, as if being rotated about an axis, from the observers viewpoint.

To give depth to these normally static images, this program slowly shifts the time position of one of the signals, making the image rotate clockwise and counterclockwise, all while rotating updwards and downwards. The direction of movement is determined entirely by the observer, and which part of the figure is being tracked by the eyes.

The application begins by displaying an initial a:b ratio, with a menu to add or delete either value. Pressing the Draw button then creates the Lissajouse Figure created by this ratio, and slowly rotates it. This continues until any key is pressed, to return back to the ratio screen, where a new value can be entered.
