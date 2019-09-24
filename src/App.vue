<template>
	<div>
		<!--HEADER-->
		<header class="uk-box-shadow-small uk-section-secondary">
			<div class="uk-container uk-container-expand">
				<nav class="uk-navbar" id="navbar" data-uk-navbar>
					<div class="uk-navbar-center">
						Abel<a class="uk-navbar-item uk-logo" href="/"><img src="./assets/logo.png" width="25" alt="Logo"/></a>Linares
					</div>

					<div class="uk-navbar-right">
						<div class="uk-navbar-item">
							<a href="Abel Linares Web Developer Resume.pdf" class="uk-button uk-button-secondary uk-visible@m">RESUME</a>
						</div>
					</div>
				</nav>
			</div>
		</header>
		<!--/HEADER-->

		<!--AUTHOR-->
		<section class="uk-section uk-section-muted uk-padding-remove-bottom">
			<div class="uk-container uk-container-small">
				<header class="uk-text-center">
					<h1 class="uk-heading-primary">Projects</h1>
					<p class="uk-width-4-5 uk-margin-auto">
						<i>Client satisfacion is a priority.</i><br/>I've always loved making things for others. I help create and design client ideas from the ground up and turn them into fully working and customizable applications so they could do what they please with it!
					</p>
				</header>
				<div class="uk-grid uk-grid-small uk-child-width-1-3@m uk-margin-medium-top uk-grid-match" data-uk-scrollspy="cls: uk-animation-slide-bottom-small; target: > div > .uk-card; delay: 200" data-uk-grid>

					<!-- price -->
					<div>
						<div class="uk-card uk-card-default uk-card-hover uk-flex uk-flex-column" data-uk-scrollspy-class="uk-animation-slide-left-small">
							<div class="uk-card-header uk-text-center">
								<h4 class="uk-text-bold">COTES</h4>
							</div>
							<div class="uk-card-body uk-flex-1">
								<div class="uk-flex uk-flex-middle uk-flex-center">
									<span style="font-size: 4rem; font-weight: 200; line-height: 1em">
										<span style="font-size: 0.5em">Artist</span>
									</span>
								</div>
								<div class="uk-text-small uk-text-center uk-text-muted">Made With</div>
								<ul>
									<li>Node.js</li>
									<li>Shopify</li>
									<li>UIKit 3</li>
								</ul>
							</div>
							<div class="uk-card-footer">
								<a href="http://cotes.io" class="uk-button uk-button-primary uk-width-1-1">Visit Now</a>
							</div>
						</div>
					</div>
					<!-- /price -->

					<!-- price -->
					<div>
						<div class="uk-card uk-card-default uk-card-hover uk-flex uk-flex-column">
							<div class="uk-card-header uk-text-center">
								<h4 class="uk-text-bold">Darkest Dawn</h4>
							</div>
							<div class="uk-card-body uk-flex-1">
								<div class="uk-flex uk-flex-middle uk-flex-center">
									<span style="font-size: 4rem; font-weight: 200; line-height: 1em">
										<span style="font-size: 0.5em">Record Label</span>
									</span>
								</div>
								<div class="uk-text-small uk-text-center uk-text-muted">Made With</div>
								<ul>
									<li>Vue</li>
									<li>Heroku</li>
									<li>UIKit 3</li>
								</ul>
							</div>
							<div class="uk-card-footer">
								<a href="http://darkestdawnrecords.com" class="uk-button uk-button-primary uk-width-1-1">Visit Now</a>
							</div>
						</div>
					</div>
					<!-- /price -->
					<!-- price -->
					<div>
						<div class="uk-card uk-card-default uk-flex uk-card-hover uk-flex-column" data-uk-scrollspy-class="uk-animation-slide-right-small">
							<div class="uk-card-header uk-text-center">
								<h4 class="uk-text-bold">CBDeeper</h4>
							</div>
							<div class="uk-card-body uk-flex-1">
								<div class="uk-flex uk-flex-middle uk-flex-center">
									<span style="font-size: 4rem; font-weight: 200; line-height: 1em">
										<span style="font-size: 0.5em">CBD Store</span>
									</span>
								</div>
								<div class="uk-text-small uk-text-center uk-text-muted">Made With</div>
								<ul>
									<li>Node.js</li>
									<li>Nest.js</li>
									<li>Angular</li>
									<li>Snipcart</li>
									<li>UIKit 3</li>
								</ul>
							</div>
							<div class="uk-card-footer">
								<a href="http://cbdeeper-node.herokuapp.com" class="uk-button uk-button-primary uk-width-1-1">Visit Now</a>
							</div>
						</div>
					</div>
					<!-- /price -->

				</div>
				<div class="uk-text-center uk-text-small uk-text-muted uk-section uk-section-small">These are my current or ongoing projects.<br/>
					<a href="#more" title="More about Plans" data-uk-icon="arrow-down" data-uk-scroll="duration: 400" class="uk-button uk-button-secondary uk-margin-medium-top uk-button-large">More Skills</a>
				</div>
			</div>
		</section>

		<section id="more" class="uk-section uk-section-muted">
      <div class="uk-container">
        <div class="uk-grid-match uk-child-width-expand@m uk-child-width-1-1@s uk-text-center" data-uk-grid>
          <div>
            <div class="uk-card uk-card-default uk-card-body"><h3>Front-End</h3>HTML5<br/>CSS3<br/>CSS Libraries<br/>JS Frameworks (Angular, React & Vue)<br/>Content Management Systems<br/>REST APIs & GraphQL</div>
           </div>
          <div>
            <div class="uk-card uk-card-default uk-card-body"><h3>Back-End</h3>Web Server Environment (Linux)<br/>Node.js<br/>Databases (MySQL & MongoDB)</div>
          </div>
          <div>
            <div class="uk-card uk-card-default uk-card-body"><h3>Other</h3>Git<br/>Android Studio<br/>Unity<br/>Photoshop</div>
          </div>
        </div>
      </div>
    </section>
		<div class="uk-section uk-section-xsmall uk-section-secondary">
			<div class="uk-container">
				<div class="uk-text-center uk-text-muted uk-text-small">
					Download my <a href="Abel Linares Web Developer Resume.pdf">resume</a> for more information!
				</div>
			</div>
		</div>
	</div>
</template>

<script>

import axios from 'axios'

const api = '';

export default {
  name: 'app',
  data(){
    return {
      info: null
    }
  },
  created() {
    axios.get(api)
    .then(response => {
      this.info = response.data
    })
    .catch(e => {
      console.log(e)
    })
  }
}
</script>

<style>
	.uk-container-small {
		max-width: 1020px;
	}
</style>
