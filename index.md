---
layout: default
title: Syed Ali
---

<section class="hero">
  <div class="hero-inner">
    <div>
      <h1>Syed Ali</h1>
      <p class="lead">I am an accelerated BS/MS student at Vanderbilt University studying Computer Science, with an additional major in Mathematics. I will graduate in May 2026.</p>
    <p class="lead">I am interested in the intersection between Computer Science, Urban Planning, and Transit. Before this, I was a SWE intern at Capital One. My primary interests are in Backend Engineering, Distributed Systems, and Machine Learning.</p>

    <p class="social">
        <a href="mailto:syed.a.ali@vanderbilt.edu" title="Email"><i class="fa fa-envelope" style="font-size:28px;color:#34231e;"></i></a>&nbsp;&nbsp;
        <a href="https://github.com/SySyAli" title="GitHub" target="_blank" rel="noopener"><i class="fab fa-github" style="font-size:28px;color:#34231e;"></i></a>&nbsp;&nbsp;
        <a href="https://www.linkedin.com/in/syed-ansab-ali/" title="LinkedIn" target="_blank" rel="noopener"><i class="fab fa-linkedin" style="font-size:28px;color:#34231e;"></i></a>
    </p>
    </div>
  </div>
</section>

<section id="projects" class="section">
<h2>Projects</h2>
<div class="grid" style="display:flex;gap:1.5rem;align-items:flex-start;overflow-x:auto;padding-bottom:1rem;">
    <article class="card" style="min-width:320px;flex:0 0 320px;">
        <h3>Access911 <small class="meta">| October 2025</small></h3>
        <p class="meta">Next.js, AWS (Lambda, DynamoDB, Bedrock), TypeScript, Twilio, Mapbox</p>
        <ul>
            <li>Secured 3rd place and $10,000 at the AWS x Vanderbilt Mission Autonomy Hackathon by developing an AI-powered emergency response platform that reduces 911 hold times during disasters.</li>
            <li>Architected serverless AWS infrastructure using Lambda and DynamoDB for concurrent call processing; integrated Amazon Bedrock (Claude Sonnet 3.5) for real-time call summarization.</li>
            <li>Built end-to-end voice pipeline (Twilio, ElevenLabs) and Next.js dispatcher dashboard with live Mapbox visualization, achieving 93% success rate and 2.8s latency across 2,500 calls in 30 minutes.</li>
        </ul>
        <p><a class="link" href="https://github.com/SySyAli/access911">Repository →</a></p>
    </article>

    <article class="card" style="min-width:320px;flex:0 0 320px;">
        <h3>Distributed Data Pipeline on Kubernetes <small class="meta">| October 2025</small></h3>
        <p class="meta">Kubernetes, Docker, Ansible, Kafka, Flask, Python</p>
        <ul>
            <li>Deployed scalable Kafka streaming pipeline on a 5-node Kubernetes cluster using Ansible for orchestration and Docker containerization with multiple publisher/subscriber replicas for distributed message processing.</li>
            <li>Configured Kubernetes infrastructure with master/worker architecture, private Docker registry, and firewall rules; designed deployment YAMLs for stateful and stateless services across the cluster.</li>
            <li>Built a multi-topic IoT data ingestion system processing sensor data; implemented horizontal scaling of subscribers and Flask web servers to prevent bottlenecks.</li>
        </ul>
        <!-- <p><a class="link" href="https://github.com/SySyAli/course_coach">Repository →</a></p> -->
    </article>

    <article class="card" style="min-width:320px;flex:0 0 320px;">
        <h3>CourseCoach <small class="meta">| November 2024</small></h3>
        <p class="meta">Next.js, TypeScript, OpenAI API, Chakra UI</p>
        <ul>
            <li>Developed and presented a course scheduling platform, placing 2nd at VandyHacks XI, enabling students to optimize academic planning through AI-powered recommendations and interactive flowcharts.</li>
            <li>Integrated OpenAI API to provide personalized course recommendations into Next.js web app based on user history and preferences, improving decision-making and ensuring degree progress.</li>
        </ul>
        <p><a class="link" href="https://github.com/SySyAli/course_coach">Repository →</a></p>
    </article>
</div>
</section>

<section id="future-projects" class="section">
  <h2>Future Projects</h2>
<ul style="display:flex;gap:1.5rem;align-items:flex-start;overflow-x:auto;padding-bottom:1rem;">
    <li class="card" style="min-width:320px;flex:0 0 320px;">
        <h3>Transit Trip Planner <small class="meta">| Planned</small></h3>
        <p class="meta">Multi-modal routing, GTFS, optimization</p>
        <p>Multi-stop itinerary planner that optimizes for total travel time, fewest transfers, or reliability across transit, walking, and micro-mobility. Current apps only provide the ability for one route.</p>
    </li>

    <li class="card" style="min-width:320px;flex:0 0 320px;">
        <h3>Collaborative AI Workspace <small class="meta">| Planned</small></h3>
        <p class="meta">Real-time collaboration, generative AI, shared context</p>
        <p>Google‑Docs-like generative AI app where teams co-edit prompts and responses, refine queries, and get shared, context‑aware answers.</p>
    </li>
</ul>
  </ul>
</section>