$(document).ready(function() {
	
	/* scroll */
	
	$("a[href^='#']").click(function(){
		var target = $(this).attr("href");
		var product = $(this).parent().find("h3").text();
        $("#order_form select[name='type'] option[value='"+product+"']").prop("selected", true);
		$("html, body").animate({scrollTop: $(target).offset().top+"px"});
		return false;
	});

});

$(window).on("load", function(){
	$(".owl-carousel").owlCarousel({
		items: 1,
		loop: true,
		autoHeight: true,
		smartSpeed: 300,
		mouseDrag: false,
		pullDrag: false,
		nav: true,
		navText: ""
	});
});