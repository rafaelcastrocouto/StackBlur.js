StackBlur.js
=======
This is a demo for a Javascript/Canvas based implementation of the [StackBlur algorithm](http://incubator.quasimondo.com/processing/fast_blur_deluxe.php).

###[Source](http://www.quasimondo.com/StackBlurForCanvas/StackBlurDemo.html)

Usage: 

    stackBlurImage( sourceImageID, targetCanvasID, radius, blurAlphaChannel );
    
    stackBlurCanvasRGBA( targetCanvasID, top_x, top_y, width, height, radius );
    
    stackBlurCanvasRGB( targetCanvasID, top_x, top_y, width, height, radius );