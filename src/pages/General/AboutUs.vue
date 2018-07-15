<template>
<div class="aboutus">
	<Navbar />
	<h3>About us</h3>
</Navbar>
<div class="uk-position-relative uk-visible-toggle" uk-slideshow="animation: push">

    <ul class="uk-slideshow-items uk-width-1-1 uk-height-small">
        <li>
            <img src="@/assets/SG1.jpg" alt="" uk-cover>
            <div class="uk-position-center-left uk-position-medium uk-text-center uk-light">
                <h2 class="uk-margin-remove">Social Guide</h2>
                <h4 class="uk-margin-remove">Reach The Peaks With Us</h4>
            </div>
        </li>
        <li>
            <img src="@/assets/SG2.jpg" alt="" uk-cover>
            <div class="uk-position-center-left uk-position-medium uk-text-center uk-light">
                <h3 class="uk-margin-remove">Bottom</h3>
                <p class="uk-margin-remove">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </li>
        <li>
            <img src="@/assets/SG3.jpg" alt="" uk-cover>
            <div class="uk-position-center-left uk-position-medium uk-text-center uk-light">
                <h3 class="uk-margin-remove">Overlay Bottom</h3>
                <p class="uk-margin-remove">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </li>
    </ul>

    <div class="uk-light">
        <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slideshow-item="previous"></a>
        <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slideshow-item="next"></a>
    </div>

</div>
<Footer />
</div>
</template>

<script>
import Navbar from "@/components/partials/Navbar"
import Footer from "@/components/partials/Footer"
export default {
	components: {
		Navbar,
		Footer
	}
}
</script>

<style> 

</style>
