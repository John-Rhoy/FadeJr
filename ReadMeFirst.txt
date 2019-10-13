FadeJr is a simple JQuery library that fades an element when windown is scrolled.
*************************************
This library is powered by Jquery.
Developer: John Rhoy Gadot
Website: jrgadot.ml
Email: gadotjohnrhoy@gmail.com
*************************************
How to use:
1. Include the FadeJr.min.css and the FadeJr.min.js and the jQuery file.
	a.In the FadeJr.min.css there is variable named --fade-time and it is set to .5s, You can the value at 
	  any value you want specified in seconds. This variable specifies the time for fading.
	b. In the FadeJr.min.js there is a variable named elementOffset. This variable will be the reference to specify
          in what point the element should start fading. Example the elementhas an offset of 1000. The elementOffset
	  will then be subtracted to 1000. Then an event will check if the scroll offset is equals to the subtacted value.
	  if it is, then the element will start to fade.
2. Add the .fade-jr class to any element that you want to fade. Simple as that.
NOTE: Please see sample.html to see technical example., The sample.jpg is used in sample.html, don't be bothered by that