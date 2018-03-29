CodeLou_FrontEnd

# St_James_Tour

Description: The tour is designed to give users information about each of the homes on historic St James Court.  Introductory pages provide basic informnation about the coourt, its' history and the annual art show that occurs on the grounds. Research  will be completed to provide specific information for each address. Place holder text is included for reference.

The "Tour" page includes basic information and also details for each structure via a pop up modal.  The tour lists two columns for structures on either side of the street when viewed on a larger desk top computer.  In mobile and tablet views, addresses are listed in order so the use can start down one side of the street and continue up the other side of the street with addresses in location order.


Java Script was used to activate the opening and closing of the pop up modals.


Custom CSS Classes

1. Several Classes were employed for basic CSS functions. Specific classes I created for the "Tour" Page. Each class required specific CSS characteristics. The class(es) I created are:

div class=page - contains page for shift to two colums in large viewports.
		
div class=section - separates addresses to sides of the streeet.
		
div class=address - container for image and basic information.

div class=imageBox - to properly proportion building images.

div class=quickFacts - contains basic facts about the address
				
div class=modal	- allows for the selection of the modal.	
		
div class=modal-content - contains details about selected property.



2. Custom JavaScript Functions were used to activate the modals:

// Get the modal
var modal = document.getElementsByClassName('modal');


// Get the button that opens the modal
var btn = document.getElementsByClassName("btn");


// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close");


// When the user clicks the button, open the modal 
	btn[0].onclick = function() {
    		modal[0].style.display = "block";
}

// When the user clicks on <span> (x), close the modal
	span[0].onclick = function() {
    		modal[0].style.display = "none";
}
