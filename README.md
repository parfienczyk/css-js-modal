Modal
==================================

## Description
Modals are based on Bootstrap http://getbootstrap.com/javascript/#modals


## See
	
	/app/scss/_modal.scss
	/app/js/_modal.js


## Example

![Alt text](/app/images/modal.png "Modal")

	<!-- Modal -->
	<div class="modal fade" tabindex="-1" role="dialog">
	  <div class="modal-dialog">
	    <div class="modal-content">
	      <div class="modal-header">
	        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
	        <h4 class="modal-title">Modal title</h4>
	      </div>
	      <div class="modal-body">
	        <p>One fine body...</p>
	      </div>
	      <div class="modal-footer">
	        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
	        <button type="button" class="btn btn-primary">Save changes</button>
	      </div>
	    </div>
	  </div>
	</div>
	
	<!-- Button trigger modal -->
    <button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">
      Launch demo modal
    </button>
    
    
###.modal('show')
Manually opens a modal. Returns to the caller before the modal has actually been shown (i.e. before the shown.bs.modal event occurs).    
	
	$('#myModal').modal('show')
	
###.modal('hide')
Manually hides a modal. Returns to the caller before the modal has actually been hidden (i.e. before the hidden.bs.modal event occurs).

	$('#myModal').modal('hide')	
	    

## Author

Karol Parfienczyk <parfienczyk@gmail.com>
 
