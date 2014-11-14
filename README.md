##Working session 
*version 1.1, last Updated: 11/02/14*

----------------

### In this live programming example, the interviewee will be asked to complete the following, given the markup and CSS in this directory.

1.	The call to action in the text widget needs some visual improvements. Update it with the following UX requirements:
	*	The "Learn more" call-to-action should be styled like a button:
		*	It should have 10px rounded corners
		*	The button will be a solid green color (#1d5b2d)
		*	The button text should be white with a size of 16px
	*	On hover, the button should change:
		*	To a darker shade of green (#103e1b)

2.	The demo page is not responsive. Make it responsive with the following:
	*	Your breakpoints are:
		*	Phones: 320px - 767px
		*	Tablets: 768px - 979px
	*	The two widgets should stack on phones, but remain side-by-side on tablets
	*	The two columns of links in the link widget should collapse into one column on both phones and tablets

3.	Add some interactivity to the links in the link widget
	*	Use jQuery (provided) to add efficient click event listeners for each link
	*	Stop the default behavior from happening, and instead send an ajax request to the resource contained in each links `href` attribute
	*	You'll get a response to your ajax request that contains information about each resource. Without knowing the data contract, inspect the response and show the user the user-friendly message contained in each response.