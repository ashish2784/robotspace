 
 <script>
    let Nintin= "/images/cr32EpYX1fqP96VC7puQT60mVwM.png";
    let Roopak= "/images/j5tJaL2iZCTkpOiS81e06QAVxRw.png";
    let Rohit= "/images/EnkrwR8PITl0OKf8nzAYtO3ko8.jpg";
 </script>
 
 <section class="section" id="team">
      <div class="wrapper">
        <div class="section-header">
          <span class="pill-labelp">Team</span>
          <h2 class="section-title">People behind Robotspace</h2>
          <p class="section-subtitle">
            Together, we are more than just a team; we are a collective force dedicated to simplifying manufacturing through robotics and automation. With a shared passion for innovation and a commitment to excellence, we are propelling Robotspace and our customers toward a future where manufacturing is streamlined, efficient, and empowered.
          </p>
        </div>

        <div class="team-grid">
          <article class="team-card">
            <div class="avatar"><img src={Roopak} alt="Roopak Jada"></div>
            <div class="team-name">Roopak Jada</div>
            <div class="team-role">Chief Executive Officer</div>
            <p class="team-desc">
              Over a decade designing and rolling out robotics, IoT and automation projects
              across the US, Europe and India, bridging product vision and factory reality.
            </p>
          </article>

          <article class="team-card">
            <div class="avatar"><img src={Nintin} alt="Sai Nithin Krishna Jonnalagadda"></div>
			<div class="team-name">Sai Nithin Krishna Jonnalagadda</div>
            <div class="team-role">Chief Operating Officer</div>
            <p class="team-desc">
              IIT-M alumnus with a background in large-scale data systems and ERP integrations,
              driving data-driven operations and continuous improvement.
            </p>
          </article>

          <article class="team-card">
            <div class="avatar"><img src={Rohit} alt="Rohit Reddy"></div>
            <div class="team-name">Rohit Reddy</div>
            <div class="team-role">Chief Business Officer</div>
            <p class="team-desc">
              Started as an automation engineer in the US and now focuses on bringing advanced
              industrial technology to manufacturing customers in India.
            </p>
          </article>
        </div>
      </div>
    </section>

<style>
   .team-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 20px;
    }

    .team-card {
      background: rgba(7, 9, 25, 0.96);
      border-radius: var(--radius-xl);
      border: 1px solid var(--border-soft);
      padding: 18px 18px 20px;
      text-align: left;
    }

    .avatar {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  overflow: hidden;
  background: none;
  margin-bottom: 12px;
}

.avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

    .team-name {
      font-weight: 600;
      font-size: 0.98rem;
      margin-bottom: 2px;
    }

    .team-role {
      text-transform: uppercase;
      letter-spacing: 0.16em;
      font-size: 0.7rem;
      color: var(--accent);
      margin-bottom: 8px;
    }

    .team-desc {
      font-size: 0.8rem;
      color: var(--text-muted);
    }

</style>
