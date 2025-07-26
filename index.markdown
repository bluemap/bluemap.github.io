---
layout: home
title: Home
---

<div class="hero-section">
  <div class="hero-content">
    <div class="hero-text">
      <h1 class="hero-title">MeeFun</h1>
      <p class="hero-slogan">{{ site.slogan }}</p>
      <p class="hero-subtitle">Guangzhou Miqu Information Technology Co., Ltd.</p>
      <div class="hero-buttons">
        <a href="#services" class="btn btn-primary">Our Services</a>
        <a href="#about" class="btn btn-secondary">Learn More</a>
      </div>
    </div>
    <div class="hero-visual">
      <div class="tech-circles">
        <div class="circle circle-1"></div>
        <div class="circle circle-2"></div>
        <div class="circle circle-3"></div>
        <div class="logo-container">
          <div class="meefun-logo">MF</div>
        </div>
      </div>
    </div>
  </div>
</div>

<section id="services" class="services-section">
  <div class="container">
    <h2 class="section-title">Our Core Services</h2>
    <div class="services-grid">
      <div class="service-card">
        <div class="service-icon">📱</div>
        <h3>Mobile App Development</h3>
        <p>Native and cross-platform mobile applications for iOS and Android platforms, delivering exceptional user experiences.</p>
      </div>
      <div class="service-card">
        <div class="service-icon">🌐</div>
        <h3>Web Application Development</h3>
        <p>Modern, responsive web applications built with cutting-edge technologies and best practices.</p>
      </div>
      <div class="service-card">
        <div class="service-icon">💬</div>
        <h3>Mini-Program Development</h3>
        <p>WeChat and other platform mini-programs that enhance user engagement and business efficiency.</p>
      </div>
    </div>
  </div>
</section>

<section id="about" class="about-section">
  <div class="container">
    <div class="about-content">
      <div class="about-text">
        <h2>About MeeFun</h2>
        <p class="philosophy">{{ site.philosophy }}</p>
        <div class="company-info">
          <div class="info-item">
            <strong>Industry:</strong> {{ site.industry }}
          </div>
          <div class="info-item">
            <strong>Contact:</strong> <a href="mailto:{{ site.email }}">{{ site.email }}</a>
          </div>
        </div>
      </div>
      <div class="about-visual">
        <div class="tech-grid">
          <div class="tech-item">React</div>
          <div class="tech-item">Vue.js</div>
          <div class="tech-item">Node.js</div>
          <div class="tech-item">Python</div>
          <div class="tech-item">Flutter</div>
          <div class="tech-item">Swift</div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="cta-section">
  <div class="container">
    <h2>Ready to Start Your Project?</h2>
    <p>Let's build something amazing together</p>
    <a href="mailto:{{ site.email }}" class="btn btn-primary">Get In Touch</a>
  </div>
</section>

<style>
/* Hero Section */
.hero-section {
  min-height: 100vh;
  background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 50%, #16213e 100%);
  display: flex;
  align-items: center;
  position: relative;
  overflow: hidden;
}

.hero-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="%23333" stroke-width="0.5"/></pattern></defs><rect width="100" height="100" fill="url(%23grid)"/></svg>');
  opacity: 0.1;
}

.hero-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  position: relative;
  z-index: 2;
}

.hero-text {
  flex: 1;
  color: white;
}

.hero-title {
  font-size: 4rem;
  font-weight: 700;
  margin: 0;
  background: linear-gradient(45deg, #00d4ff, #ff6b6b);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-slogan {
  font-size: 1.5rem;
  margin: 1rem 0;
  color: #00d4ff;
  font-weight: 300;
}

.hero-subtitle {
  font-size: 1.1rem;
  margin: 1rem 0 2rem;
  color: #ccc;
}

.hero-buttons {
  display: flex;
  gap: 1rem;
}

.btn {
  padding: 12px 24px;
  border-radius: 25px;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
  border: 2px solid transparent;
}

.btn-primary {
  background: linear-gradient(45deg, #00d4ff, #0099cc);
  color: white;
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 20px rgba(0, 212, 255, 0.3);
}

.btn-secondary {
  background: transparent;
  color: #00d4ff;
  border-color: #00d4ff;
}

.btn-secondary:hover {
  background: #00d4ff;
  color: white;
}

/* Hero Visual */
.hero-visual {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}

.tech-circles {
  position: relative;
  width: 300px;
  height: 300px;
}

.circle {
  position: absolute;
  border-radius: 50%;
  border: 2px solid;
  animation: float 6s ease-in-out infinite;
}

.circle-1 {
  width: 200px;
  height: 200px;
  top: 50px;
  left: 50px;
  border-color: #00d4ff;
  animation-delay: 0s;
}

.circle-2 {
  width: 150px;
  height: 150px;
  top: 75px;
  left: 75px;
  border-color: #ff6b6b;
  animation-delay: 2s;
}

.circle-3 {
  width: 100px;
  height: 100px;
  top: 100px;
  left: 100px;
  border-color: #4ecdc4;
  animation-delay: 4s;
}

.logo-container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.meefun-logo {
  width: 80px;
  height: 80px;
  background: linear-gradient(45deg, #00d4ff, #ff6b6b);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-weight: 700;
  font-size: 1.5rem;
  box-shadow: 0 10px 30px rgba(0, 212, 255, 0.3);
}

@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-20px); }
}

/* Services Section */
.services-section {
  padding: 5rem 0;
  background: #f8f9fa;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.section-title {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 3rem;
  color: #333;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.service-card {
  background: white;
  padding: 2rem;
  border-radius: 15px;
  text-align: center;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.service-card:hover {
  transform: translateY(-5px);
}

.service-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.service-card h3 {
  color: #333;
  margin-bottom: 1rem;
}

.service-card p {
  color: #666;
  line-height: 1.6;
}

/* About Section */
.about-section {
  padding: 5rem 0;
  background: white;
}

.about-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
}

.about-text h2 {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
  color: #333;
}

.philosophy {
  font-size: 1.2rem;
  line-height: 1.8;
  color: #555;
  margin-bottom: 2rem;
  font-style: italic;
}

.company-info {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.info-item {
  color: #666;
}

.info-item a {
  color: #00d4ff;
  text-decoration: none;
}

.tech-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
}

.tech-item {
  background: linear-gradient(45deg, #00d4ff, #0099cc);
  color: white;
  padding: 1rem;
  border-radius: 10px;
  text-align: center;
  font-weight: 500;
  transition: transform 0.3s ease;
}

.tech-item:hover {
  transform: scale(1.05);
}

/* CTA Section */
.cta-section {
  padding: 5rem 0;
  background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%);
  text-align: center;
  color: white;
}

.cta-section h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.cta-section p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  color: #ccc;
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero-content {
    flex-direction: column;
    text-align: center;
  }
  
  .hero-title {
    font-size: 3rem;
  }
  
  .about-content {
    grid-template-columns: 1fr;
  }
  
  .tech-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .hero-buttons {
    justify-content: center;
  }
}
</style>
