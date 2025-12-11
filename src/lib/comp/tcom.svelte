<script>

      let tl1=  "/images/6TqkNbC2bsn982MEgpymuGFM2U.png";
      let tl2="/images/aomhh5RRErsILtXaiXRo6ID92qI.png" ; 
    let tl3="/images/axWQrtYmlYf1vZdq2PcjIVAnY0U.png" ;
    let tl4="/images/hgADtPAnZfYtKa2KaxlBnX8QVvs.png";
    let tl5="/images/HTS2KZtUAzAmMkksg6FZZgDf1fM.png";
    let tl6="/images/mI8qTECrxBNTlGpSFHDaOZGK1SI.png" ;
</script>



<section class="section">
      <div class="wrapper">
        <div class="section-header">
          <h2 class="section-title">Trusted by manufacturing leaders</h2>
          <p class="section-subtitle">
            Robotics, automation and software deployed across plants in automotive, building materials,
            electronics, and more.
          </p>
        </div>

        <div class="trusted-logos" aria-hidden="true">
          <div class="marquee-track">
            <div class="marquee-item"><img src={tl1} alt="Client 1"></div>
            <div class="marquee-item"><img src={tl2} alt="Client 2"></div>
            <div class="marquee-item"><img src={tl3} alt="Client 3"></div>
            <div class="marquee-item"><img src={tl4} alt="Client 4"></div>
            <div class="marquee-item"><img src={tl5} alt="Client 5"></div>
            <div class="marquee-item"><img src={tl6} alt="Client 6"></div>

            
            <div class="marquee-item"><img src={tl1} alt="Client 1"></div>
            <div class="marquee-item"><img src={tl2} alt="Client 2"></div>
            <div class="marquee-item"><img src={tl3} alt="Client 3"></div>
            <div class="marquee-item"><img src={tl4} alt="Client 4"></div>
            <div class="marquee-item"><img src={tl5} alt="Client 5"></div>
            <div class="marquee-item"><img src={tl6} alt="Client 6"></div>

            <div class="marquee-item"><img src={tl1} alt="Client 1"></div>
            <div class="marquee-item"><img src={tl2} alt="Client 2"></div>
            <div class="marquee-item"><img src={tl3} alt="Client 3"></div>
            <div class="marquee-item"><img src={tl4} alt="Client 4"></div>
            <div class="marquee-item"><img src={tl5} alt="Client 5"></div>
            <div class="marquee-item"><img src={tl6} alt="Client 6"></div>


          </div>
        </div>
      </div>
    </section> 

<style>
/* container masks edges */
.trusted-logos {
  width: 100%;
  overflow: hidden;
  mask-image: linear-gradient(to right, rgba(0,0,0,0) 0%, rgb(0,0,0) 8%, rgb(0,0,0) 92%, rgba(0,0,0,0) 100%);
}

/* marquee track: duplicated items create seamless loop */
.marquee-track {
  display: flex;
  gap: 28px;
  align-items: center;
  will-change: transform;
  animation: marquee 25s linear infinite;
}

.marquee-item {
  flex: 0 0 auto;
  width: 140px;
  height: 70px;
  display:flex;
  align-items:center;
  justify-content:center;
  padding: 10px;
}

.marquee-item img { max-width:100%; max-height:100%; display:block; }

/* seamless scroll: move left by exactly half the track (we duplicated content)
   0% -> 0, 100% -> translateX(-50%) so the second copy aligns with the start */
   
@keyframes marquee {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}

/* pause on hover for accessibility */
.trusted-logos:hover .marquee-track { animation-play-state: paused; }

/* reduced-motion users */
@media (prefers-reduced-motion: reduce) {
  .marquee-track { animation: none; }
}
</style>