<script lang="ts">
	import favicon from '$lib/assets/rs logo.jpeg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}




<main>
  <section class="Contact" id="form">
		<form class="form" action="">
			<h2>Talk to us!</h2>
			<p >We'd Love to Hear from You! At Robotspace, we're dedicated to open communication and building strong connections with our community, clients, and partners. Whether you have a question, a partnership proposal, or simply want to learn more about our innovative robotics and automation solutions, we're here to help. Feel free to reach out to us !</p>
			
			<input class="input" type="text" placeholder="Your Name" required>
			<input class="input" type="email" placeholder="Your Email" required>
			<input class="input" type="text" placeholder="Subject" required>
			<textarea class="input" rows="5" placeholder="Your Message" required></textarea>

			<button class="btn btn-accent" type="submit" style="margin-top:12px; width:100%; height:100%">Send Message</button>
		</form>
	</section>

<br>

    <section class="section" id="socials">
      <div class="wrapper">
        <div class="section-header">
          <span class="pill-label"></span>
          <div class="section-visual">
            <a href="#top"><img src="/images/sonK02g1HhQpYMD96kBANE5hEYY.png" alt="Socials"></a></div>
          <p class="section-subtitle">
            With a core mission to streamline manufacturing complexities, Robotspace continues to be a driving force in making the manufacturing process simpler, more efficient, and innovative.
          </p>
        </div>

		<div class="socials" style="display:flex;gap:12px;justify-content:left;margin-top:14px">
			
			<a class="pill" 
  			 href="https://www.google.com/maps/place/Hyderabad,+Telangana" 
   				target="_blank" 
  			 rel="noopener noreferrer">
  			<svg xmlns="http://www.w3.org/2000/svg" 
       		width="20" height="20" viewBox="0 0 24 24" 
       		fill="none" stroke="orangered" stroke-width="2" 
       		stroke-linecap="round" stroke-linejoin="round" 
       			aria-hidden="true">
    		<path d="M21 10c0 7-9 13-9 13S3 17 3 10a9 9 0 1 1 18 0z"/>
   	 		<circle cx="12" cy="10" r="3"/>
  			</svg>
  				Scoobylabs Robotics Pvt. Ltd.
				Hitech City, Hyderabad, Telangana 500055, India
			</a>


            <a class="pill" href="mailto:info@robotspace.in" target="_blank" rel="noopener noreferrer">

              
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 122.88 92.12" width="20" height="20" aria-hidden="true">
                <style type="text/css">
                  .st0{fill:#EA4335;}
                  .st1{fill:#C5221F;}
                  .st2{fill:orangered;}
                  .st3{fill:orangered;}
                  .st4{fill:orangered;}
                </style>
                <g>
                  <path class="st4" d="M8.36,92.12h19.54V44.67L0,23.76v60.08C0,88.42,3.78,92.12,8.36,92.12L8.36,92.12z"/>
                  <path class="st3" d="M94.97,92.12h19.54c4.67,0,8.36-3.78,8.36-8.36v-60L94.97,44.67V92.12L94.97,92.12z"/>
                  <path class="st2" d="M94.97,8.4v36.27l27.91-20.91V12.58c0-10.37-11.82-16.25-20.11-10.05L94.97,8.4L94.97,8.4z"/>
                  <polygon class="st0" points="27.9,44.67 27.9,8.4 61.44,33.57 94.97,8.4 94.97,44.67 61.44,69.76 27.9,44.67"/>
                  <path class="st1" d="M0,12.58v11.18l27.91,20.91V8.4l-7.8-5.87C11.82-3.66,0,2.29,0,12.58L0,12.58z"/>
                </g>
              </svg>
              Email
            </a>
		 	<a class="pill" href="https://www.linkedin.com/company/robotspace" target="_blank" rel="noopener noreferrer">
         	     <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 122.88 122.31" width="20" height="20" aria-hidden="true">
                <defs>
                  <style>
                    .cls-1{fill:orangered;fill-rule:evenodd;}
                    .cls-2{fill:#fff;fill-rule:evenodd;}
                  </style>
                </defs>
                <path class="cls-1" d="M27.75,0H95.13a27.83,27.83,0,0,1,27.75,27.75V94.57a27.83,27.83,0,0,1-27.75,27.74H27.75A27.83,27.83,0,0,1,0,94.57V27.75A27.83,27.83,0,0,1,27.75,0Z"/>
                <path class="cls-2" d="M49.19,47.41H64.72v8h.22c2.17-3.88,7.45-8,15.34-8,16.39,0,19.42,10.2,19.42,23.47V98.94H83.51V74c0-5.71-.12-13.06-8.42-13.06s-9.72,6.21-9.72,12.65v25.4H49.19V47.41ZM40,31.79a8.42,8.42,0,1,1-8.42-8.42A8.43,8.43,0,0,1,40,31.79ZM23.18,47.41H40V98.94H23.18V47.41Z"/>
              </svg>
              LinkedIn
            </a>

			<a class="pill" href="tel:+918121380696">
 			 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20"
       			viewBox="0 0 24 24" fill="none" stroke="orangered" stroke-width="2"
       			stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
    			<path d="M22 16.92v3a2 2 0 0 1-2.18 2
             19.79 19.79 0 0 1-8.63-3.07
             19.5 19.5 0 0 1-6-6
             19.79 19.79 0 0 1-3.07-8.67
             A2 2 0 0 1 4.1 2h3
             a2 2 0 0 1 2 1.72
             13 13 0 0 0 .7 2.81
             2 2 0 0 1-.45 2.11L8.09 9.91
             a16 16 0 0 0 6 6l1.27-1.27
             a2 2 0 0 1 2.11-.45
             13 13 0 0 0 2.81.7
             2 2 0 0 1 1.72 2z"/>
 			 </svg>
  				Phone
			</a>
		</div>

        <footer>
          <div class="footer-inner">
            <div>
              © 2022 - Robotspace India · Scoobylabs Robotics Pvt. Ltd.
            </div>
            <div class="footer-links">
              <a href="#top">Privacy policy</a>
              <a href="#top">Terms of service</a>
            </div>
          </div>
        </footer>
      </div>
    </section>
</main>