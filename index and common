<div class="loader">
		<div class="loader_inner"></div>
	</div>
	
	и в common.js
	
		function heightDetect() {
		$(".main_head").css("height", $(window).height());
};
		heightDetect();
		$(window).resize(function()	{
			heightDetect();
});

});
$(window).load(function() {
$(".loader_Inner").fadeOut();
$(".loader").delay(400).fadeOut("slow");
});
