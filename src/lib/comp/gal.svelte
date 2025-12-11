 <script >
 
 const Gallery =[
     "/images/sjzmUuiZ8xLdyaHD949ggKP3gWE.png",
    "/images/rvYty1Uf18i6T8NUCr9w8SCHA.png",
    "/images/OFoN25NEyVC3p32LubBtJdCglc.png",
    "/images/omvNToe2rhbApFwUxRmHTl049M.png",
    "/images/MTlvH83IKsTObYcuDYvO1JTeE0.png",
	"/images/0MfU6Io7y5Rfch8cQuTyvxsRIk.png"]

</script>

   <section class="section" id="careers">
    <div class="wrapper">
        <div class="section-header">
          <span class="pill-label">Careers</span>
          <h2 class="section-title">We’re hiring</h2>
          <p class="section-subtitle">
            Join a team that is rethinking how factories are designed, run and scaled.
          </p>
        </div>

        <div class="careers-card">
          <div>
            <p>
              If you love building things that touch the real world — robots, software, control
              systems, data tools — Robotspace is a place to do that at scale. We work at the
              intersection of manufacturing, hardware and cloud.
            </p>
            <p>
              We’re always looking for people who are curious, hands-on and comfortable working
              close to customers on the shop floor.
            </p>
          </div>
          <div>
            <div class="badge">
              <span class="badge-dot"></span>
              Open roles across engineering, product &amp; operations
            </div>
            <p style="margin-top:10px;">
              Share your profile and interests with us and we’ll get in touch when a matching
              opportunity opens up.
            </p>
            <a href="mailto:info@robotspace.in" class="btn btn-accent" style="margin-top:6px; display:inline-flex;">
              See open roles
            </a>
          </div>
        </div>
    </div>
	<br>


    <!-- Gallery -->
<section class="section" id="gallery">
      <div class="wrapper">
    

        <div class="photo" style="display:flex;gap:12px;justify-content:center;margin-top:14px; flex-wrap:wrap">
            {#each Gallery as imgSrc}
                <div class="photo" style="width:calc(33% - 8px); min-width:200px;">
                    <img src={imgSrc} alt="Gallery Image" style="width:100%; height:auto; border-radius:12px;">
                </div>
            {/each}
        </div>
      </div>
    </section>

  </section>

