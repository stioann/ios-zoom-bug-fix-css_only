ios-zoom-bug-fix-css_only
=========================
It's taken from: http://stackoverflow.com/a/8727440


/*
    I began with the goal to prevent font scaling in Landscape orientation.
    To do this, see: http://stackoverflow.com/questions/2710764/

    Later, I just wanted to magnify font-size for the iPad, leaving
    the iPhone rendering to the css code.  So ...

    (max-device-width:480px) = iphone.css
    (min-device-width:481px) and
        (max-device-width:1024px) and
            (orientation:portrait) = ipad-portrait.css
    (min-device-width:481px) and
        (max-device-width:1024px) and
            (orientation:landscape) = ipad-landscape.css
    (min-device-width:1025px) = ipad-landscape.css

*/
