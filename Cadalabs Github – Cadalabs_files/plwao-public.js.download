(function($) {

	"use strict";

	/* Preloader is active */
	if( $('.plwao-loader-wrap').length > 0 ) {

		jQuery('html').addClass('plwao-overflow');
		jQuery('body').addClass('plwao-overflow');

		/* On Window Load */
		$(window).on('load', function() {
			jQuery(".plwao-loader-wrap").fadeOut('slow', function() {
				jQuery('html').removeClass('plwao-overflow');
				jQuery('body').removeClass('plwao-overflow');
			});
		});
	}
})(jQuery);