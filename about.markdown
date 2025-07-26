---
layout: page
title: About Us
permalink: /about/
---

<div class="about-hero">
  <div class="container">
    <h1>About MeeFun</h1>
    <p class="subtitle">Building the future through innovative technology solutions</p>
  </div>
</div>

<section class="company-overview">
  <div class="container">
    <div class="overview-grid">
      <div class="overview-content">
        <h2>Our Story</h2>
        <p>Guangzhou Miqu Information Technology Co., Ltd. (MeeFun) is a dynamic technology company dedicated to creating innovative digital solutions that empower businesses and enhance user experiences.</p>
        
        <p>Founded with a vision to bridge the gap between technology and human needs, we specialize in developing cutting-edge mobile applications, web platforms, and mini-programs that drive business growth and user engagement.</p>
        
        <div class="company-stats">
          <div class="stat-item">
            <div class="stat-number">100+</div>
            <div class="stat-label">Projects Completed</div>
          </div>
          <div class="stat-item">
            <div class="stat-number">50+</div>
            <div class="stat-label">Happy Clients</div>
          </div>
          <div class="stat-item">
            <div class="stat-number">5+</div>
            <div class="stat-label">Years Experience</div>
          </div>
        </div>
      </div>
      <div class="overview-visual">
        <div class="tech-illustration">
          <div class="floating-element" style="--delay: 0s">📱</div>
          <div class="floating-element" style="--delay: 1s">💻</div>
          <div class="floating-element" style="--delay: 2s">🌐</div>
          <div class="floating-element" style="--delay: 3s">⚡</div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="mission-vision">
  <div class="container">
    <div class="mission-grid">
      <div class="mission-card">
        <div class="mission-icon">🎯</div>
        <h3>Our Mission</h3>
        <p>To deliver exceptional digital solutions that transform businesses and create meaningful user experiences through innovative technology.</p>
      </div>
      <div class="mission-card">
        <div class="mission-icon">🔮</div>
        <h3>Our Vision</h3>
        <p>To be a leading technology partner that empowers businesses to thrive in the digital age through cutting-edge solutions and unwavering commitment to quality.</p>
      </div>
      <div class="mission-card">
        <div class="mission-icon">💎</div>
        <h3>Our Values</h3>
        <ul>
          <li>Innovation & Excellence</li>
          <li>Client Partnership</li>
          <li>Quality & Reliability</li>
          <li>Continuous Learning</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section class="services-detail">
  <div class="container">
    <h2>Our Core Services</h2>
    <div class="services-detail-grid">
      <div class="service-detail-card">
        <div class="service-header">
          <div class="service-icon">📱</div>
          <h3>Mobile App Development</h3>
        </div>
        <p>We create native and cross-platform mobile applications that deliver exceptional user experiences across iOS and Android platforms.</p>
        <div class="service-features">
          <span class="feature-tag">iOS Development</span>
          <span class="feature-tag">Android Development</span>
          <span class="feature-tag">Cross-platform</span>
          <span class="feature-tag">UI/UX Design</span>
        </div>
      </div>
      
      <div class="service-detail-card">
        <div class="service-header">
          <div class="service-icon">🌐</div>
          <h3>Web Application Development</h3>
        </div>
        <p>Modern, responsive web applications built with cutting-edge technologies and best practices for optimal performance and user experience.</p>
        <div class="service-features">
          <span class="feature-tag">Frontend Development</span>
          <span class="feature-tag">Backend Development</span>
          <span class="feature-tag">API Integration</span>
          <span class="feature-tag">Cloud Deployment</span>
        </div>
      </div>
      
      <div class="service-detail-card">
        <div class="service-header">
          <div class="service-icon">💬</div>
          <h3>Mini-Program Development</h3>
        </div>
        <p>WeChat and other platform mini-programs that enhance user engagement and business efficiency with seamless integration.</p>
        <div class="service-features">
          <span class="feature-tag">WeChat Mini-Program</span>
          <span class="feature-tag">Alipay Mini-Program</span>
          <span class="feature-tag">Platform Integration</span>
          <span class="feature-tag">User Engagement</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="contact-section">
  <div class="container">
    <h2>Get In Touch</h2>
    <p>Ready to start your next project? Let's discuss how we can help bring your ideas to life.</p>
    <div class="contact-info">
      <div class="contact-item">
        <div class="contact-icon">📧</div>
        <div class="contact-details">
          <h4>Email</h4>
          <a href="mailto:{{ site.email }}">{{ site.email }}</a>
        </div>
      </div>
      <div class="contact-item">
        <div class="contact-icon">🏢</div>
        <div class="contact-details">
          <h4>Company</h4>
          <p>{{ site.company_name }}</p>
        </div>
      </div>
      <div class="contact-item">
        <div class="contact-icon">🎯</div>
        <div class="contact-details">
          <h4>Industry</h4>
          <p>{{ site.industry }}</p>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
/* About Hero */
.about-hero {
  background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%);
  color: white;
  padding: 4rem 0;
  text-align: center;
}

.about-hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
  background: linear-gradient(45deg, #00d4ff, #ff6b6b);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.about-hero .subtitle {
  font-size: 1.3rem;
  color: #ccc;
}

/* Company Overview */
.company-overview {
  padding: 5rem 0;
  background: white;
}

.overview-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
}

.overview-content h2 {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
  color: #333;
}

.overview-content p {
  font-size: 1.1rem;
  line-height: 1.8;
  color: #555;
  margin-bottom: 1.5rem;
}

.company-stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
  margin-top: 3rem;
}

.stat-item {
  text-align: center;
}

.stat-number {
  font-size: 2.5rem;
  font-weight: 700;
  color: #00d4ff;
  margin-bottom: 0.5rem;
}

.stat-label {
  color: #666;
  font-size: 0.9rem;
}

/* Tech Illustration */
.tech-illustration {
  position: relative;
  height: 400px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.floating-element {
  position: absolute;
  font-size: 3rem;
  animation: float 4s ease-in-out infinite;
  animation-delay: var(--delay);
}

@keyframes float {
  0%, 100% { transform: translateY(0px) rotate(0deg); }
  50% { transform: translateY(-20px) rotate(10deg); }
}

/* Mission Vision */
.mission-vision {
  padding: 5rem 0;
  background: #f8f9fa;
}

.mission-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.mission-card {
  background: white;
  padding: 2.5rem;
  border-radius: 15px;
  text-align: center;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.mission-card:hover {
  transform: translateY(-5px);
}

.mission-icon {
  font-size: 3rem;
  margin-bottom: 1.5rem;
}

.mission-card h3 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  color: #333;
}

.mission-card p {
  color: #666;
  line-height: 1.6;
}

.mission-card ul {
  list-style: none;
  padding: 0;
  text-align: left;
}

.mission-card li {
  padding: 0.5rem 0;
  color: #666;
  position: relative;
  padding-left: 1.5rem;
}

.mission-card li::before {
  content: '✓';
  position: absolute;
  left: 0;
  color: #00d4ff;
  font-weight: bold;
}

/* Services Detail */
.services-detail {
  padding: 5rem 0;
  background: white;
}

.services-detail h2 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 3rem;
  color: #333;
}

.services-detail-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
}

.service-detail-card {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 15px;
  border-left: 4px solid #00d4ff;
  transition: transform 0.3s ease;
}

.service-detail-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}

.service-header {
  display: flex;
  align-items: center;
  margin-bottom: 1rem;
}

.service-header .service-icon {
  font-size: 2rem;
  margin-right: 1rem;
}

.service-header h3 {
  color: #333;
  margin: 0;
}

.service-detail-card p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 1.5rem;
}

.service-features {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.feature-tag {
  background: linear-gradient(45deg, #00d4ff, #0099cc);
  color: white;
  padding: 0.3rem 0.8rem;
  border-radius: 15px;
  font-size: 0.8rem;
  font-weight: 500;
}

/* Contact Section */
.contact-section {
  padding: 5rem 0;
  background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%);
  color: white;
  text-align: center;
}

.contact-section h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.contact-section p {
  font-size: 1.2rem;
  margin-bottom: 3rem;
  color: #ccc;
}

.contact-info {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  max-width: 800px;
  margin: 0 auto;
}

.contact-item {
  display: flex;
  align-items: center;
  background: rgba(255,255,255,0.1);
  padding: 2rem;
  border-radius: 15px;
  backdrop-filter: blur(10px);
}

.contact-icon {
  font-size: 2rem;
  margin-right: 1rem;
}

.contact-details h4 {
  margin: 0 0 0.5rem 0;
  color: #00d4ff;
}

.contact-details p,
.contact-details a {
  margin: 0;
  color: #ccc;
  text-decoration: none;
}

.contact-details a:hover {
  color: #00d4ff;
}

/* Responsive Design */
@media (max-width: 768px) {
  .overview-grid {
    grid-template-columns: 1fr;
  }
  
  .company-stats {
    grid-template-columns: 1fr;
  }
  
  .contact-info {
    grid-template-columns: 1fr;
  }
  
  .about-hero h1 {
    font-size: 2.5rem;
  }
}
</style>
