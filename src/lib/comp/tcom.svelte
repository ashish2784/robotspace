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

      .section {
      padding: 40px 0 60px;
    }

    .section-header {
      text-align: center;
      margin-bottom: 30px;
    }

    .section-title {
      font-size: 1.5rem;
      margin-bottom: 6px;
    }

    .section-subtitle {
      color: var(--text-muted);
      font-size: 0.92rem;
      max-width: 520px;
      margin: 0 auto;
    }

    .trusted-logos {
      display: flex;
      flex-wrap: wrap;
      gap: 24px;
      justify-content: center;
    }

    .trusted-logo {
      width: 120px;
      height: 50px;
      border-radius: 999px;
      background: rgb(13, 13, 13);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.8rem;
      color: var(--text-muted);
    }

  .trusted-logo img{
    object-fit: contain;
  }

  #about.section::before {
  content: "";
  position: absolute;
  top: 0;
  left: 10%;
  width: 80%;
  border-top: 2px solid rgba(235, 45, 45, 0.6);
}


.trusted-logos {
  width: 100%;
  overflow: hidden;
  mask-image: linear-gradient(to right, rgba(0,0,0,0) 0%, rgb(0,0,0) 8%, rgb(0,0,0) 92%, rgba(0,0,0,0) 100%);
}

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

@keyframes marquee {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}

.trusted-logos:hover .marquee-track { animation-play-state: paused; }

@media (prefers-reduced-motion: reduce) {
  .marquee-track { animation: none; }
}
</style>
