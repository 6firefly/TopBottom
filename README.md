TopBottom
=========

A simple yii extension for quick scrolling to the top/bottom of the page.

This project uses jQuery.

You may use it like:

$this->widget('ext.topBottom.scroll');

or


$this->widget('ext.topBottom.scroll', array(
        'minDepth'=>1000, 
        'minHeight'=>500,
        'fadeInTime'=>700,
        'fadeOutTime'=>700,
        'opacity' => 0.2, // ('opacity' = 0 vs. 'opacity' != 0 => different behavior)
        'scrollTopTime'=>1000,
        'scrollBottomTime'=>1000,
    ));
    
'opacity' = 0 means that scrolling button that is no longer needed (up button when the user is at the top of the page; 
down button when the user is at the bottom of the page) just dosapear;
'opacity' != 0 means that the button just fade away, but do not disapear;

