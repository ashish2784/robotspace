<main>
<section class="hero" id="top">
      <div class="wrapper hero-inner">
        <div>
          <div class="eyebrow">Industrial robotics &amp; software</div>
          <h1 class="hero-title">Simplify your Manufacturing</h1>
          <p class="hero-subtitle">
            Discover Reliable, Cost-Effective, and Fully Integrated Robotic Automation, Advanced Monitoring, Planning, MES, and IIoT Solutions for All Kinds of Factory.
          </p>

          <div class="hero-actions">
            <a href="#products" class="btn btn-accent">Explore products</a>
            <a href="#about" class="btn btn-accent">Learn more</a>
          </div>

          <div class="hero-metrics">
            <div class="metric">
              <span>Product families across robotics, automation and IIoT</span>
            </div>
            <div class="metric">
              <span>Building solutions for factories since</span>
			  <strong>2013</strong>
            </div>
          </div>
        </div>

      </div>
    </section>

</main>


<style>
     .hero {
      padding: 72px 0 80px;
    }

	.hero {
  position: relative;
  padding: 72px 0 80px;
  background-image:
    url('/images/hero.avif'); 
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}


    .hero-inner {
      position: relative;
  z-index: 1;
      display: grid;
      grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr);
      gap: 48px;
      align-items: center;
    }

    .eyebrow {
      text-transform: uppercase;
      letter-spacing: 0.28em;
      font-size: 0.78rem;
      color: var(--accent);
      margin-bottom: 14px;
    }

    .hero-title {
      font-size: clamp(3rem, 4vw, 4rem);
      font-weight: 900;
      line-height: 1.2;
      margin-bottom: 18px;
    }

    .hero-subtitle {
      color: var(--text-muted);
      font-size: 1.2rem;
      max-width: 520px;
      margin-bottom: 26px;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
      margin-bottom: 32px;
    }

    .hero-metrics {
      display: flex;
      flex-wrap: wrap;
      gap: 22px;
    }

.metric {
  padding: 10px 16px;
  border-radius: 999px;
  border: 1px solid rgba(255, 255, 255, 0.07);
  background: rgba(10, 12, 30, 0.85);
  display: flex;
  align-items: baseline;
  gap: 8px;
}

.metric strong {
  font-size: 1.3rem;
  color: var(--accent);
}

    .hero-visual {
      position: relative;
    }

	.metric strong {
		color: orangered
	}



    .hero-robot {
      margin-top: 8px;
      border-radius: 18px;
      background: radial-gradient(circle at top, #ffffff 0, #d8d9e4 40%, #a8abbc 70%, #505471 100%);
      height: 260px;
      position: relative;
      overflow: hidden;
    }

    .hero-robot::before {
      content: "";
      position: absolute;
      inset: 40px 40px 120px;
      border-radius: 22px;
      background: linear-gradient(145deg, #f6f7fa, #eff0f9);
      box-shadow: 0 24px 60px rgba(0, 0, 0, 0.25);
    }

    .hero-robot::after {
      content: "";
      position: absolute;
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 20px solid #111425;
      bottom: -60px;
      right: 60px;
      box-shadow: 0 16px 40px rgba(0, 0, 0, 0.85);
    }

    .hero-tag-label {
      font-size: 0.8rem;
      color: var(--text-muted);
      margin-bottom: 4px;
    }

    .hero-tag-pill {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 6px 14px;
      border-radius: 999px;
      background: rgba(0, 0, 0, 0.5);
      border: 1px solid rgba(255, 255, 255, 0.18);
      font-size: 0.74rem;
      color: var(--text-muted);
    }

    .hero-tag-pill span {
      width: 9px;
      height: 9px;
      border-radius: 999px;
      background: #27e38b;
      box-shadow: 0 0 14px rgba(39, 227, 139, 0.9);
    }
</style>
