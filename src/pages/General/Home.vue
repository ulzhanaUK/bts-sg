<template>
  <div class="home">
  <Navbar />
  <div class="uk-position-relative uk-visible-toggle" uk-slideshow="animation: push">

    <ul class="uk-slideshow-items uk-width-1-1 uk-height-small">
        <li>
            <img src="https://images.unsplash.com/photo-1499377193864-82682aefed04?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=71c8f98090468daa45a13fe3e5785571&auto=format&fit=crop&w=761&q=80" alt="" uk-cover>
            <div class="uk-position-center-left uk-position-medium uk-text-center uk-light">
                <h2 class="uk-margin-remove">Social Guide</h2>
                <h4 class="uk-margin-remove">Reach The Peaks With Us</h4>
            </div>
        </li>
        <li>
            <img src="https://images.unsplash.com/photo-1502743780242-f10d2ce370f3?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=e9aa16866e220380b804609225f27e18&auto=format&fit=crop&w=1316&q=80" alt="" uk-cover>
            <div class="uk-position-center-left uk-position-medium uk-text-center uk-light">
                <h3 class="uk-margin-remove">Bottom</h3>
                <p class="uk-margin-remove">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </li>
        <li>
            <img src="https://images.unsplash.com/photo-1494253109108-2e30c049369b?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=02261b49dc587eaecb3dfae7ccfbbcaa&auto=format&fit=crop&w=750&q=80" alt="" uk-cover>
            <div class="uk-position-center-left uk-position-medium uk-text-center uk-light">
                <h3 class="uk-margin-remove">Overlay Bottom</h3>
                <p class="uk-margin-remove">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
        </li>
        <li>
            <img src="https://images.unsplash.com/photo-1449247709967-d4461a6a6103?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1053a3cdbabdd85102b762b3a05966ae&auto=format&fit=crop&w=751&q=80" alt="" uk-cover>
            <div class="uk-position-center-left uk-position-medium uk-text-center uk-light">
                <h3 class="uk-margin-remove">Overlay Bottom Right</h3>
                <p class="uk-margin-remove">Lorem ipsum dolor sit amet.</p>
            </div>
        </li>
    </ul>

    <div class="uk-light">
        <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slideshow-item="previous"></a>
        <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slideshow-item="next"></a>
    </div>

</div>
  <div uk-spinner></div>
  <h3>Urraaa</h3>
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
	},
    name: 'HelloWorld',
    data () {
    	return {
    		msg: 'Welcome to Your Vue.js App'
    	}
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
</style>
