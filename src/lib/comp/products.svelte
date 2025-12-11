<!-- Products -->

<section class="section" id="products">
      <div class="wrapper">
        <div class="section-header">
          <span class="pill-label">Products</span>
          <h2 class="section-title">Automation for every corner of the factory</h2>
          <p class="section-subtitle">
            A connected portfolio of robots, control hardware and manufacturing software that
            work together as one system.
          </p>
        </div>

        <div class="products-grid">


          <!-- Legato -->
          <article class="product-card">
            <div class="product-info">
              <div class="product-tag">Robotic platform</div>
              <h3 class="product-name">Legato</h3>
              <p class="product-subtitle"><b>A single platform for line automation</b></p>
              <p class="product-body">
                Configure robotic assembly, inspection, packing, palletizing, pick-and-place and
                sorting applications using the same software and hardware building blocks.
              </p>
              <div class="product-metrics">
                <div class="product-metric-pill">Up to 50% faster deployment</div>
                <div class="product-metric-pill">5× ROI vs manual operations</div>
              </div>
              <div class="product-footer">
                <span>Controls · Gantry · Pneumatics · Linear Actuator · Vacuum · Grippers · Pneumatics</span>
              </div>
            </div>
            <div class="product-image-wrap">
              <img src="/images/Okss1DWieT9KgONlcLCn0Yp6Ohw.jpg" alt="Legato Robotic Platform" class="product-image">
            </div>
          </article>

          <!-- iFactory AI -->
          <article class="product-card">
            <div class="product-info">
              <div class="product-tag">Manufacturing OS</div>
              <h3 class="product-name">iFactory&nbsp;AI</h3>
              <p class="product-subtitle"><b>Run your plant from anywhere</b></p>
              <p class="product-body">
                Real-time visibility, planning and coordination across machines, operators,
                robots, automation islands, ERP and communication tools in one interface.
              </p>
              <div class="product-metrics">
                <div class="product-metric-pill">5× faster response to issues</div>
                <div class="product-metric-pill">Up to 30% lower MTTR</div>
              </div>
              <div class="product-footer">
                <span>Monitoring · MES · Scheduling · Quality</span>
              </div>
            </div>
            <div class="product-image-wrap">
              <img src="/images/FnFfWwES0ClV1uBZ4oq3kVLM.jpg" alt="iFactory AI Manufacturing OS" class="product-image">
            </div>
          </article>

          <!-- Scoot -->
          <article class="product-card">
            <div class="product-info">
              <div class="product-tag">Autonomous mobile robots</div>
              <h3 class="product-name">Scoot</h3>
              <p class="product-subtitle"><b>Material movement on autopilot</b></p>
              <p class="product-body">
                A LIDAR-based SLAM navigation fully autonomous industrial robot that can move material within your factory. Scoot is capable of performing various tasks by integrating with other robots, machines, and software systems.

Scoot can be easily integrated with machines, robotic arms and call buttons simplifying the deployments. 

Scoot provides solutions for manufacturing, pharmaceuticals, hospitality, warehouses, commercial, and other industries.
</p>
              <div class="product-metrics">
                <div class="product-metric-pill">100% autonomous operation</div>
                <div class="product-metric-pill">50&nbsp;kg – 500&nbsp;kg payloads</div>
              </div>
              <div class="product-footer">
                <span>Manufacturing · Pharma · Warehousing</span>
              </div>
            </div>
            <div class="product-image-wrap">
              <img src="/images/8i9hPaITmicnje8a2seoU7KInYc.png" alt="Scoot Autonomous Mobile Robot" class="product-image">
            </div>
          </article>

          <!-- ioWare -->
          <article class="product-card">
            <div class="product-info">
              <div class="product-tag">Industrial IoT hardware</div>
              <h3 class="product-name">ioWare</h3>
              <p class="product-subtitle">Gateway &amp; smart HMI</p>
              <p class="product-body">
                Connect sensors, legacy machines and PLCs to the cloud or iFactory AI with a
                drop-in gateway and operator-friendly HMI designed for harsh industrial
                environments.
              </p>
              <div class="product-metrics">
                <div class="product-metric-pill">15+ processes digitised</div>
                <div class="product-metric-pill">Rapid adoption with smart HMI</div>
              </div>
              <div class="product-footer">
                <span>Modbus · MQTT · Ethernet · Wi-Fi</span>
              </div>
            </div>
            <div class="product-image-wrap">
              <img src="/images/UsP0N6UTQ1HnzgY2j4d7spO38c.png" alt="ioWare Industrial IoT Hardware" class="product-image">
            </div>
          </article>
        </div>
      </div>
    </section>
 
<style>
      /* Products */
    #products{
      background: #fff;
      color: #000;
    }



    .products-grid {
      display: grid;
      grid-template-columns: repeat( 1, minmax(0, 1fr));
      gap: 24px;
    }

    .product-card {
      background: rgba(251, 251, 251, 0.96);
      border-radius: var(--radius-xl);
      border: 1px solid var(--border-soft);
      padding: 50px 22px 24px;
      position: relative;
      overflow: hidden;
    }
    .product-card {
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      gap: 24px;
    }

    .product-info {
      flex: 1;
    }

    .product-image-wrap {
      flex: 1;
      display: flex;
      justify-content: flex-end;
      align-items: center;
    }

    .product-image {
      width: 100%;
      max-width: 380px;
      border-radius: 12px;
    }

    .product-tag {
      text-transform: uppercase;
      letter-spacing: 0.2em;
      font-size: 0.76rem;
      color: var(--bg);
      margin-bottom: 6px;
    }

    .product-name {
      font-size: 1.3rem;
      font-weight: 600;
      margin-bottom: 4px;
      color: var(--bg);
    }

    .product-subtitle {
      font-size: 1.3rem;
      color: var(--bg);
      margin-bottom: 10px;
    }

    .product-body {
      font-size: 0.76rem;
      color: var(--bg);
      font-size: 0.86rem;
      margin-bottom: 18px;
    }

    .product-metrics {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-bottom: 14px;
    }

    .product-metric-pill {
      background: #ff7a32;       
  color: #ffffff;           
  padding: 10px 22px;
  border-radius: 999px;     
  font-weight: 500;
  border: none;              
  display: inline-block;
}
    
    .product-footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 0.75rem;
      color: var(--bg);
    }


</style>
