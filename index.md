---
layout: default
title: Syed Ali
---

<section class="hero">
  <div class="hero-inner">
    <div>
      <h1>Syed Ali</h1>
      <p class="lead">I am an accelerated BS/MS student at Vanderbilt University studying Computer Science, with an additional major in Mathematics. I will graduate in May 2026.</p>
    <p class="lead">I am an interested in the intersection between Computer Science, Urban Planning, and Transit. Before this, I was a SWE intern at Capital One. My primary interests are in Backend Engineering, Distributed Systems, and Machine Learning.</p>

      <!-- Social favicons: Email, GitHub, LinkedIn -->
      <p class="social">
        <a class="social-link" href="mailto:syed.a.ali@vanderbilt.edu" title="Email">
        <!-- mail icon -->
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" aria-label="Email">
            <rect x="3" y="5" width="18" height="14" rx="2" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
            <path d="M3 7l9 6 9-6" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
            <path d="M7 12h10" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" opacity="0.6" />
        </svg>     </a>

        <a class="social-link" href="https://github.com/SySyAli" title="GitHub" target="_blank" rel="noopener">
          <!-- github icon -->
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M12 2C7.03 2 3 6.03 3 11c0 4.08 2.64 7.54 6.32 8.76.46.09.63-.20.63-.45 0-.22-.01-.80-.01-1.57-2.57.56-3.11-.62-3.31-1.19-.11-.28-.60-1.19-1.03-1.43-.35-.18-.85-.62-.01-.63.79-.01 1.36.73 1.55 1.03.90 1.52 2.33 1.08 2.90.82.09-.64.35-1.08.64-1.33-2.30-.26-4.72-1.15-4.72-5.12 0-1.13.39-2.06 1.03-2.79-.10-.26-.45-1.31.10-2.73 0 0 .84-.27 2.75 1.03A9.56 9.56 0 0 1 12 6.80c.85.004 1.71.116 2.51.34 1.91-1.30 2.75-1.03 2.75-1.03.55 1.42.20 2.47.10 2.73.64.73 1.03 1.66 1.03 2.79 0 3.98-2.43 4.85-4.74 5.11.36.31.68.92.68 1.86 0 1.34-.01 2.42-.01 2.75 0 .25.17.54.64.45C18.36 18.54 21 15.08 21 11c0-4.97-4.03-9-9-9z" fill="currentColor"/></svg>
        </a>

        <a class="social-link" href="https://www.linkedin.com/in/syed-ansab-ali/" title="LinkedIn" target="_blank" rel="noopener">
          <!-- linkedin icon -->
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M16 8a6 6 0 0 1 6 6v6h-4v-6a2 2 0 0 0-4 0v6h-4v-12h4v1.5" stroke="currentColor" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round"/><rect x="2" y="7" width="4" height="12" rx="1" stroke="currentColor" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round"/><circle cx="4" cy="4" r="2" stroke="currentColor" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </a>
      </p>

    </div>
  </div>
</section>

<section id="projects" class="section">
  <h2>Projects</h2>
  <div class="grid">
    <article class="card">
      <h3>Access911 <small class="meta">| October 2025</small></h3>
      <p class="meta">Next.js, AWS (Lambda, DynamoDB, Bedrock), TypeScript, Twilio, Mapbox</p>
      <ul>
        <li>Secured 3rd place and $10,000 at the AWS x Vanderbilt Mission Autonomy Hackathon by developing an AI-powered emergency response platform that reduces 911 hold times during disasters.</li>
        <li>Architected serverless AWS infrastructure using Lambda and DynamoDB for concurrent call processing; integrated Amazon Bedrock (Claude Sonnet 3.5) for real-time call summarization.</li>
        <li>Built end-to-end voice pipeline (Twilio, ElevenLabs) and Next.js dispatcher dashboard with live Mapbox visualization, achieving 93% success rate and 2.8s latency across 2,500 calls in 30 minutes.</li>
      </ul>
      <p><a class="link" href="#">Repository →</a></p>
    </article>

    <article class="card">
      <h3>Distributed Data Pipeline on Kubernetes <small class="meta">| October 2025</small></h3>
      <p class="meta">Kubernetes, Docker, Ansible, Kafka, Flask, Python</p>
      <ul>
        <li>Deployed scalable Kafka streaming pipeline on a 5-node Kubernetes cluster using Ansible for orchestration and Docker containerization with multiple publisher/subscriber replicas for distributed message processing.</li>
        <li>Configured Kubernetes infrastructure with master/worker architecture, private Docker registry, and firewall rules; designed deployment YAMLs for stateful and stateless services across the cluster.</li>
        <li>Built a multi-topic IoT data ingestion system processing sensor data; implemented horizontal scaling of subscribers and Flask web servers to prevent bottlenecks.</li>
      </ul>
      <p><a class="link" href="#">Repository →</a></p>
    </article>

    <article class="card">
      <h3>CourseCoach <small class="meta">| November 2024</small></h3>
      <p class="meta">Next.js, TypeScript, OpenAI API, Chakra UI</p>
      <ul>
        <li>Developed and presented a course scheduling platform, placing 2nd at VandyHacks XI, enabling students to optimize academic planning through AI-powered recommendations and interactive flowcharts.</li>
        <li>Integrated OpenAI API to provide personalized course recommendations into Next.js web app based on user history and preferences, improving decision-making and ensuring degree progress.</li>
      </ul>
      <p><a class="link" href="#">Repository →</a></p>
    </article>


  </div>
</section>

<section id="future-projects" class="section">
  <h2>Future Projects</h2>
  <ul>
    <li><strong>Transit Trip Planner</strong> — Multi-stop itinerary planner that optimizes for total travel time, fewest transfers, or reliability across transit, walking, and micro-mobility. Current apps only provide the ability for one route.
    </li>

    <li><strong>Collaborative AI Workspace</strong> — A real-time, Google-Docs-like generative AI app where teams co-edit prompts and responses, collaboratively refine queries, and receive shared, context-aware answers and suggestions instantly.</li>
  </ul>
</section>