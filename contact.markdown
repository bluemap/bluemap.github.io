---
layout: page
title: Contact Us
permalink: /contact/
---

<div class="contact-hero">
  <div class="container">
    <h1>Get In Touch</h1>
    <p class="subtitle">Let's discuss your next project and bring your ideas to life</p>
  </div>
</div>

<section class="contact-content">
  <div class="container">
    <div class="contact-grid">
      <div class="contact-form-section">
        <h2>Send Us a Message</h2>
        <p>Fill out the form below and we'll get back to you within 24 hours.</p>
        
        <form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
          <div class="form-group">
            <label for="name">Full Name *</label>
            <input type="text" id="name" name="name" required>
          </div>
          
          <div class="form-group">
            <label for="email">Email Address *</label>
            <input type="email" id="email" name="email" required>
          </div>
          
          <div class="form-group">
            <label for="company">Company</label>
            <input type="text" id="company" name="company">
          </div>
          
          <div class="form-group">
            <label for="service">Service Interest</label>
            <select id="service" name="service">
              <option value="">Select a service</option>
              <option value="mobile-app">Mobile App Development</option>
              <option value="web-app">Web Application Development</option>
              <option value="mini-program">Mini-Program Development</option>
              <option value="consultation">Consultation</option>
              <option value="other">Other</option>
            </select>
          </div>
          
          <div class="form-group">
            <label for="budget">Project Budget</label>
            <select id="budget" name="budget">
              <option value="">Select budget range</option>
              <option value="under-10k">Under $10,000</option>
              <option value="10k-25k">$10,000 - $25,000</option>
              <option value="25k-50k">$25,000 - $50,000</option>
              <option value="50k-100k">$50,000 - $100,000</option>
              <option value="over-100k">Over $100,000</option>
            </select>
          </div>
          
          <div class="form-group">
            <label for="message">Project Details *</label>
            <textarea id="message" name="message" rows="6" placeholder="Tell us about your project, goals, and requirements..." required></textarea>
          </div>
          
          <button type="submit" class="submit-btn">Send Message</button>
        </form>
      </div>
      
      <div class="contact-info-section">
        <h2>Contact Information</h2>
        <p>Ready to start your project? Here's how you can reach us.</p>
        
        <div class="contact-cards">
          <div class="contact-card">
            <div class="contact-icon">📧</div>
            <div class="contact-details">
              <h3>Email</h3>
              <p>For general inquiries and project discussions</p>
              <a href="mailto:{{ site.email }}">{{ site.email }}</a>
            </div>
          </div>
          
          <div class="contact-card">
            <div class="contact-icon">🏢</div>
            <div class="contact-details">
              <h3>Company</h3>
              <p>{{ site.company_name }}</p>
              <p class="company-cn">{{ site.company_name_cn }}</p>
            </div>
          </div>
          
          <div class="contact-card">
            <div class="contact-icon">🎯</div>
            <div class="contact-details">
              <h3>Industry</h3>
              <p>{{ site.industry }}</p>
            </div>
          </div>
          
          <div class="contact-card">
            <div class="contact-icon">💼</div>
            <div class="contact-details">
              <h3>Business Hours</h3>
              <p>Monday - Friday: 9:00 AM - 6:00 PM (GMT+8)</p>
              <p>Weekend: By appointment</p>
            </div>
          </div>
        </div>
        
        <div class="response-time">
          <div class="response-icon">⚡</div>
          <div class="response-text">
            <h3>Quick Response</h3>
            <p>We typically respond to all inquiries within 24 hours during business days.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="faq-section">
  <div class="container">
    <h2>Frequently Asked Questions</h2>
    <div class="faq-grid">
      <div class="faq-item">
        <h3>What is your typical project timeline?</h3>
        <p>Project timelines vary depending on complexity and scope. A simple mobile app might take 6-8 weeks, while complex web applications can take 3-6 months. We'll provide a detailed timeline during our initial consultation.</p>
      </div>
      
      <div class="faq-item">
        <h3>Do you provide ongoing support after launch?</h3>
        <p>Yes, we offer comprehensive post-launch support including maintenance, updates, bug fixes, and feature enhancements. We can also provide hosting and monitoring services.</p>
      </div>
      
      <div class="faq-item">
        <h3>What technologies do you specialize in?</h3>
        <p>We work with modern technologies including React, Vue.js, Node.js, Python, Flutter, React Native, Swift, and Kotlin. We choose the best technology stack based on your specific requirements.</p>
      </div>
      
      <div class="faq-item">
        <h3>How do you handle project communication?</h3>
        <p>We maintain regular communication through scheduled meetings, progress reports, and collaboration tools. You'll have a dedicated project manager as your main point of contact.</p>
      </div>
      
      <div class="faq-item">
        <h3>Do you work with international clients?</h3>
        <p>Absolutely! We have experience working with clients from various countries and can accommodate different time zones and communication preferences.</p>
      </div>
      
      <div class="faq-item">
        <h3>What is your development process?</h3>
        <p>We follow an agile development process that includes discovery, design, development, testing, and deployment phases. We involve you throughout the process to ensure the final product meets your expectations.</p>
      </div>
    </div>
  </div>
</section>

<style>
/* Contact Hero */
.contact-hero {
  background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%);
  color: white;
  padding: 4rem 0;
  text-align: center;
}

.contact-hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
  background: linear-gradient(45deg, #00d4ff, #ff6b6b);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.contact-hero .subtitle {
  font-size: 1.3rem;
  color: #ccc;
}

/* Contact Content */
.contact-content {
  padding: 5rem 0;
  background: white;
}

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: start;
}

/* Contact Form */
.contact-form-section h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: #333;
}

.contact-form-section > p {
  color: #666;
  margin-bottom: 2rem;
  font-size: 1.1rem;
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.form-group {
  display: flex;
  flex-direction: column;
}

.form-group label {
  margin-bottom: 0.5rem;
  color: #333;
  font-weight: 500;
}

.form-group input,
.form-group select,
.form-group textarea {
  padding: 12px 16px;
  border: 2px solid #e1e5e9;
  border-radius: 8px;
  font-size: 1rem;
  transition: border-color 0.3s ease;
  background: white;
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
  outline: none;
  border-color: #00d4ff;
  box-shadow: 0 0 0 3px rgba(0, 212, 255, 0.1);
}

.form-group textarea {
  resize: vertical;
  min-height: 120px;
}

.submit-btn {
  background: linear-gradient(45deg, #00d4ff, #0099cc);
  color: white;
  padding: 14px 28px;
  border: none;
  border-radius: 25px;
  font-size: 1.1rem;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s ease;
  margin-top: 1rem;
}

.submit-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 20px rgba(0, 212, 255, 0.3);
}

/* Contact Info */
.contact-info-section h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: #333;
}

.contact-info-section > p {
  color: #666;
  margin-bottom: 2rem;
  font-size: 1.1rem;
}

.contact-cards {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.contact-card {
  display: flex;
  align-items: flex-start;
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 15px;
  transition: transform 0.3s ease;
}

.contact-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.contact-icon {
  font-size: 2rem;
  margin-right: 1rem;
  flex-shrink: 0;
}

.contact-details h3 {
  color: #333;
  margin: 0 0 0.5rem 0;
  font-size: 1.2rem;
}

.contact-details p {
  color: #666;
  margin: 0 0 0.3rem 0;
  line-height: 1.5;
}

.contact-details a {
  color: #00d4ff;
  text-decoration: none;
  font-weight: 500;
}

.contact-details a:hover {
  text-decoration: underline;
}

.company-cn {
  font-size: 0.9rem;
  color: #888;
}

.response-time {
  display: flex;
  align-items: center;
  background: linear-gradient(45deg, #00d4ff, #0099cc);
  color: white;
  padding: 1.5rem;
  border-radius: 15px;
}

.response-icon {
  font-size: 2rem;
  margin-right: 1rem;
  flex-shrink: 0;
}

.response-text h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.2rem;
}

.response-text p {
  margin: 0;
  opacity: 0.9;
}

/* FAQ Section */
.faq-section {
  padding: 5rem 0;
  background: #f8f9fa;
}

.faq-section h2 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 3rem;
  color: #333;
}

.faq-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 2rem;
}

.faq-item {
  background: white;
  padding: 2rem;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.faq-item:hover {
  transform: translateY(-5px);
}

.faq-item h3 {
  color: #333;
  margin-bottom: 1rem;
  font-size: 1.3rem;
}

.faq-item p {
  color: #666;
  line-height: 1.6;
}

/* Responsive Design */
@media (max-width: 768px) {
  .contact-grid {
    grid-template-columns: 1fr;
  }
  
  .faq-grid {
    grid-template-columns: 1fr;
  }
  
  .contact-hero h1 {
    font-size: 2.5rem;
  }
  
  .contact-form-section h2,
  .contact-info-section h2 {
    font-size: 2rem;
  }
}
</style> 