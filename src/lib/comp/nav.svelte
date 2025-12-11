<script>
    let logo = "/images/sonK02g1HhQpYMD96kBANE5hEYY.png";


</script>

<div class="wrapper nav">
      <div class="nav-left">
        <div class="logo">
			<a href="#top"><img src={logo} alt="Robotspace Logo" ></a>
		</div>
      </div>
      <nav class="nav-links">
        <a href="#products" class="nav-primary">Products</a>
        <a href="#about" class="nav-primary">About</a>
        <a href="#careers"class="nav-primary">we're hiring</a>
        <div class="nav-cta">
          <a href="#demo" class="btn btn-accent">Book a demo</a>
        </div>
      </nav>
      <button class="mobile-menu">☰</button>
</div>

<style>
  header {
      position: sticky;
      top: 0;
      z-index: 20;
      -webkit-backdrop-filter: blur(18px);
      backdrop-filter: blur(18px);
      background: linear-gradient(to bottom, rgba(6, 7, 20, 0.95), rgba(6, 7, 20, 0.7), transparent);
      border-bottom: 1px solid rgba(255, 255, 255, 0.04);
    }

    .nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 16px 20px;
    }

    .nav-left {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo{
	  width: 140px;
	  height: auto;
	}

    .nav-links {
      display: flex;
      align-items: center;
      gap: 28px;
      font-size: 0.9rem;
    }

    .nav-links a {
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.16em;
      font-weight: 500;
      font-size: 0.78rem;
    }

    .nav-links a.nav-primary {
      color: var(--text-main);
    }

    .pill {
      border-radius: 999px;
      padding: 8px 18px;
      border: 1px solid var(--border-soft);
      background: rgba(10, 12, 30, 0.9);
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 10px 22px;
      border-radius: 999px;
      border: none;
      cursor: pointer;
      font-size: 0.8rem;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      font-weight: 600;
      white-space: nowrap;
    }

    .btn-ghost {
      background: transparent;
      color: var(--text-muted);
      border: 1px solid var(--border-soft);
    }

    .btn-accent {
      background: var(--accent);
      color: #fff;
      box-shadow: 0 16px 40px rgba(240, 104, 14, 0.55);
    }

    .nav-cta {
      
      display: flex;
      align-items: center;
      gap: 16px;
	  color: orangered;
    
    }
     .nav-cta a{
      color: #fff;
     }

    .mobile-menu {
      display: none;
    }

</style>
