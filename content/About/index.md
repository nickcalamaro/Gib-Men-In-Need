 ---
---
  <style>
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 40px 20px;
    }
   
    .services-section {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
.service-card {
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 2px 8px rgba(54, 54, 54, 0.1); /* default (light mode) */
  transition: transform 0.3s ease;
}

/* When dark mode is active (assuming the <html> tag gets a "dark" class) */
html.dark .service-card {
  box-shadow: 0 2px 8px rgba(210, 210, 210, 0.15); /* lighter shadow for dark mode */
}
    .service-card:hover {
      transform: translateY(-5px);
    }
    .service-card h2 {
      margin-top: 0;
      font-size: 1.25rem;
      color: #0066cc;
    }
    .service-card ul {
      list-style-type: disc;
      padding-left: 20px;
      margin: 10px 0;
    }
    .service-card li {
      margin-bottom: 10px;
    }
    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }
    }
  </style>


<h1>Who We Are</h1>
  <p>
    Men in Need is a Gibraltar‐based charity registered as Charity Number 364. Our mission is to offer comprehensive and empathetic support to men experiencing a range of difficulties throughout Gibraltar. These include challenges related to unemployment, homelessness, addiction, mental health, domestic violence, and other critical areas of need. We aim to ensure that every man in Gibraltar has access to the resources and guidance necessary to rebuild his life.
  </p>
  
  <p>
    Working directly with the Ministry of Justice and collaborating closely with other key government departments—including the Ministry for Housing and the Ministry for Employment—we create a network that connects men to essential services. <i>Please note that we do not offer direct employment opportunities or access to housing</i>; rather, our role is to facilitate access to a range of support services.
  </p>
  
<div class="container">
    <h1>Services We Offer</h1>
    <div class="services-section">
      <div class="service-card">
        <h2>Employment and Community Service Support</h2>
        <ul>
          <li>Tailored guidance for men reentering employment after incarceration—including CV writing, cover letters, training opportunities, and work‑readiness essentials.</li>
          <li>Structured community service initiatives and inclusive work opportunities (event‑based participation with modest payments).</li>
          <li>Comprehensive reintegration support to rebuild lives and reduce reoffending.</li>
        </ul>
      </div>
      <div class="service-card">
        <h2>Government and Administrative Support</h2>
        <ul>
          <li>Assistance with completing applications for housing and other essential services.</li>
          <li>Expert guidance navigating government departments to secure entitled benefits.</li>
        </ul>
      </div>
      <div class="service-card">
        <h2>Crisis and Basic Needs Support</h2>
        <ul>
          <li>Timely crisis response including help with procuring groceries and essential necessities.</li>
          <li>Support with utility payments, household items, and food security.</li>
          <li>Provision of toiletries, hygiene products, and emergency accommodation.</li>
        </ul>
      </div>
      <div class="service-card">
        <h2>Wellbeing and Mental Health Services</h2>
        <ul>
          <li>Connection to professional mental health services and counseling.</li>
          <li>Wellbeing supports such as short‑term gym memberships to promote physical health.</li>
        </ul>
      </div>
      <div class="service-card">
        <h2>Social and Community Engagement Opportunities</h2>
        <ul>
          <li>Safe, inclusive discussion spaces for group sessions and peer support.</li>
          <li>Community outreach initiatives like regular meetups in local cafés to foster connection.</li>
        </ul>
      </div>
      <div class="service-card">
        <h2>Additional Practical Support Services</h2>
        <ul>
          <li>Educational assistance through courses (e.g., English, maths, holistic therapies).</li>
          <li>Clothing support for men and, where needed, their children.</li>
          <li>Transport aid for interviews, appointments, or support sessions.</li>
          <li>Childcare support for short-term needs, especially for single fathers.</li>
          <li>Digital access via basic mobile phones or data credit.</li>
          <li>Coverage of legal document fees for vital paperwork (IDs, birth certificates).</li>
        </ul>
      </div>
    </div>
  </div>
  
  <p>
    <a href="/trustees">Our experienced team</a> is made up of professionals and individuals who have personally faced challenges themselves. Through strategic partnerships with government agencies and community organizations, we ensure that every man we support is equipped with the knowledge, resources, and compassion necessary to achieve lasting personal transformation.
  </p>