#Animate.css (converted to SCSS)
*Just-add-water SCSS animation*

This is basically an scss version of http://daneden.me/animate except I added some much cooler shit so you can just go:

    <div class="ani fadeIn thing">foo</div>

and in SCSS go like this:

    .ani.fadeIn.thing {
    	@include ani-delay(.5s);

        // this overrides the default 0s delay
        // and works for all browsers
    	// and defaults to 1s if no parameter provided
    }