jQuery(document).ready(function($){
	//open PopUp
	$('.PopUp-trigger').on('click', function(event){
		event.preventDefault();
		$('.PopUp').addClass('is-visible');
	});
	
	//close PopUp
	$('.PopUp').on('click', function(event){
		if( $(event.target).is('.PopUp-close, .PopUp-buttons a') || $(event.target).is('.PopUp') ) {
			event.preventDefault();
			$(this).removeClass('is-visible');
		}   
	});
	//close PopUp when clicking the esc keyboard button
  //accessibility mode
	$(document).keyup(function(event){
    	if(event.which=='27'){
    		$('.PopUp').removeClass('is-visible');
	    }
    });
});
