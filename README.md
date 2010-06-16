MutliBox
===========

A lightbox that supports a wide range of media, including html pages. It can also be created and called dynamically, eg. from within a flash movie.


How to use
----------
 
create your links with a title if you want a title to be shown, and add a class:

	<a href="/myBigImage.jpg" class="mb" title="example title a"><img src="/mySmallImage.jpg" border="0"></a>

initialise the script like this:

	window.addEvent('domready', function(){ 
	    var overlay = new overlay(); 
	    var box = new multiBox('mb', { 
	        overlay: overlay
	    }); 
	});
