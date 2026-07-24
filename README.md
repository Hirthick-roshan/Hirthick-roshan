<div align="center">

<!-- HERO BANNER SECTION -->
<svg viewBox="0 0 1200 420" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a0c"/>
      <stop offset="50%" stop-color="#121318"/>
      <stop offset="100%" stop-color="#070709"/>
    </linearGradient>

    <!-- Glassmorphism Card Fill -->
    <linearGradient id="glass-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.05"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0.01"/>
    </linearGradient>

    <!-- Border Glow Gradient -->
    <linearGradient id="border-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.25"/>
      <stop offset="50%" stop-color="#6366f1" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0.05"/>
    </linearGradient>

    <!-- Text Typography Gradients -->
    <linearGradient id="text-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#FFFFFF"/>
      <stop offset="60%" stop-color="#F3F4F6"/>
      <stop offset="100%" stop-color="#9CA3AF"/>
    </linearGradient>

    <linearGradient id="accent-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#6366F1"/>
      <stop offset="50%" stop-color="#8B5CF6"/>
      <stop offset="100%" stop-color="#D946EF"/>
    </linearGradient>

    <!-- Ambient Glowing Orbs -->
    <radialGradient id="glow-purple" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8B5CF6" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#8B5CF6" stop-opacity="0"/>
    </radialGradient>

    <radialGradient id="glow-blue" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#6366F1" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#6366F1" stop-opacity="0"/>
    </radialGradient>

    <!-- Grid Pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#ffffff" stroke-opacity="0.03" stroke-width="1"/>
    </pattern>

    <style>
      .title { font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Segoe UI", Roboto, sans-serif; font-weight: 800; font-size: 52px; letter-spacing: -1.5px; }
      .subtitle { font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", Roboto, sans-serif; font-weight: 600; font-size: 17px; letter-spacing: 3px; text-transform: uppercase; }
      .badge-text { font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", Roboto, sans-serif; font-weight: 500; font-size: 13px; letter-spacing: 0.5px; }
      
      @keyframes float {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-8px); }
        100% { transform: translateY(0px); }
      }
      @keyframes pulse {
        0% { opacity: 0.3; }
        50% { opacity: 0.6; }
        100% { opacity: 0.3; }
      }
      .floating { animation: float 6s ease-in-out infinite; }
      .pulsing { animation: pulse 4s ease-in-out infinite; }
    </style>
  </defs>

  <!-- Canvas Background -->
  <rect width="1200" height="420" rx="24" fill="url(#bg-grad)"/>
  <rect width="1200" height="420" rx="24" fill="url(#grid)"/>

  <!-- Background Glows -->
  <circle cx="200" cy="100" r="250" fill="url(#glow-purple)" class="pulsing"/>
  <circle cx="1000" cy="300" r="300" fill="url(#glow-blue)" class="pulsing"/>

  <!-- Glassmorphism Container Card -->
  <g transform="translate(60, 40)">
    <rect width="1080" height="340" rx="20" fill="url(#glass-grad)" stroke="url(#border-grad)" stroke-width="1.5"/>
    
    <!-- Top Status Pill -->
    <g transform="translate(430, 42)">
      <rect width="220" height="32" rx="16" fill="#ffffff" fill-opacity="0.05" stroke="#ffffff" stroke-opacity="0.1" stroke-width="1"/>
      <circle cx="20" cy="16" r="4" fill="#10B981"/>
      <circle cx="20" cy="16" r="8" fill="#10B981" fill-opacity="0.3" class="pulsing"/>
      <text x="36" y="20" fill="#9CA3AF" class="badge-text">SYSTEMS OPERATIONAL</text>
    </g>

    <!-- Main Typography -->
    <text x="540" y="150" text-anchor="middle" fill="url(#text-grad)" class="title">HIRTHICK ROSHAN</text>
    <text x="540" y="195" text-anchor="middle" fill="url(#accent-grad)" class="subtitle">AI ENGINEER &nbsp;•&nbsp; MACHINE LEARNING ENGINEER</text>

    <!-- Minimal Modern Divider Line -->
    <line x1="440" y1="230" x2="640" y2="230" stroke="url(#accent-grad)" stroke-width="2" stroke-linecap="round"/>

    <!-- Bottom Tech Tags SVG Icons Row -->
    <g transform="translate(540, 275)" text-anchor="middle" class="floating">
      <text x="0" y="0" fill="#6B7280" font-family="-apple-system, sans-serif" font-size="14" font-weight="500" letter-spacing="1">
        INTELLIGENT SYSTEMS &nbsp;|&nbsp; NEURAL ARCHITECTURES &nbsp;|&nbsp; SCALABLE RAG
      </text>
    </g>
  </g>
</svg>

<br/><br/>

<!-- ANIMATED TYPING LINE -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=SF+Pro+Display&weight=600&size=20&duration=3000&pause=1000&color=A5B4FC&center=true&vCenter=true&width=600&height=40&lines=Building+AI+that+solves+real+problems.;LLMs+%E2%80%A2+RAG+%E2%80%A2+AI+Agents;FastAPI+%E2%80%A2+Python+%E2%80%A2+Machine+Learning" alt="Typing SVG" />
</a>

<br/><br/>
<hr fill="#1F2937" height="1px" stroke="none"/>
<br/>

<!-- TECH STACK SECTION -->
<p align="center">
  <img src="https://img.shields.io/badge/STACK-ARCHITECTURE-000000?style=for-the-badge&logoColor=white" fill="none"/>
</p>

<br/>

<!-- GLASS ICON GRID -->
<table>
  <tr>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="42" height="42" alt="Python"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>Python</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="42" height="42" alt="FastAPI"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>FastAPI</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="42" height="42" alt="TensorFlow"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>TensorFlow</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="42" height="42" alt="PyTorch"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>PyTorch</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://raw.githubusercontent.com/valohai/rebrand-icons/main/png/langchain-white.png" width="42" height="42" alt="LangGraph"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>LangGraph</b></font>
    </td>
  </tr>
  <tr>
    <td align="center" width="110" height="110">
      <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="42" height="42" alt="HuggingFace"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>HuggingFace</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="42" height="42" alt="Docker"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>Docker</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="42" height="42" alt="React"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>React</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="42" height="42" alt="SQL"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>SQL</b></font>
    </td>
    <td align="center" width="110" height="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="42" height="42" alt="Git"/><br/><br/>
      <font size="2" color="#9CA3AF"><b>Git</b></font>
    </td>
  </tr>
</table>

<br/><br/>
<hr fill="#1F2937" height="1px" stroke="none"/>
<br/>

<!-- FEATURED PROJECTS -->
<p align="center">
  <img src="https://img.shields.io/badge/FEATURED-SYSTEMS-000000?style=for-the-badge&logoColor=white" fill="none"/>
</p>

<br/>

<!-- Project 1 -->
<a href="https://github.com/Hirthick-roshan">
  <svg viewBox="0 0 800 130" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
    <rect width="800" height="130" rx="16" fill="#121318" stroke="#262626" stroke-width="1"/>
    <rect x="0" y="0" width="6" height="130" rx="3" fill="#6366F1"/>
    <rect x="30" y="35" width="60" height="60" rx="12" fill="#1E1E24" stroke="#333333"/>
    <text x="60" y="72" fill="#8B5CF6" font-family="-apple-system, sans-serif" font-weight="700" font-size="24" text-anchor="middle">📄</text>
    <text x="110" y="52" fill="#FFFFFF" font-family="-apple-system, sans-serif" font-weight="700" font-size="18">AI Resume Screening Platform</text>
    <text x="110" y="76" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-weight="400" font-size="13">Automated candidate analysis using fine-tuned LLMs and semantic extraction.</text>
    <rect x="110" y="90" width="70" height="20" rx="6" fill="#1F1F2E"/>
    <text x="145" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">Python</text>
    <rect x="188" y="90" width="70" height="20" rx="6" fill="#1F1F2E"/>
    <text x="223" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">FastAPI</text>
    <rect x="266" y="90" width="90" height="20" rx="6" fill="#1F1F2E"/>
    <text x="311" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">HuggingFace</text>
    <circle cx="740" cy="65" r="18" fill="#1E1E24"/>
    <path d="M735 65 L745 65 M741 60 L746 65 L741 70" stroke="#FFFFFF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
  </svg>
</a>

<br/>

<!-- Project 2 -->
<a href="https://github.com/Hirthick-roshan">
  <svg viewBox="0 0 800 130" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
    <rect width="800" height="130" rx="16" fill="#121318" stroke="#262626" stroke-width="1"/>
    <rect x="0" y="0" width="6" height="130" rx="3" fill="#8B5CF6"/>
    <rect x="30" y="35" width="60" height="60" rx="12" fill="#1E1E24" stroke="#333333"/>
    <text x="60" y="72" fill="#8B5CF6" font-family="-apple-system, sans-serif" font-weight="700" font-size="24" text-anchor="middle">🤖</text>
    <text x="110" y="52" fill="#FFFFFF" font-family="-apple-system, sans-serif" font-weight="700" font-size="18">Autonomous Research Agent</text>
    <text x="110" y="76" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-weight="400" font-size="13">Self-directed agent synthesizing web research into structured technical briefs.</text>
    <rect x="110" y="90" width="80" height="20" rx="6" fill="#1F1F2E"/>
    <text x="150" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">LangGraph</text>
    <rect x="198" y="90" width="70" height="20" rx="6" fill="#1F1F2E"/>
    <text x="233" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">Python</text>
    <rect x="276" y="90" width="70" height="20" rx="6" fill="#1F1F2E"/>
    <text x="311" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">Docker</text>
    <circle cx="740" cy="65" r="18" fill="#1E1E24"/>
    <path d="M735 65 L745 65 M741 60 L746 65 L741 70" stroke="#FFFFFF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
  </svg>
</a>

<br/>

<!-- Project 3 -->
<a href="https://github.com/Hirthick-roshan">
  <svg viewBox="0 0 800 130" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
    <rect width="800" height="130" rx="16" fill="#121318" stroke="#262626" stroke-width="1"/>
    <rect x="0" y="0" width="6" height="130" rx="3" fill="#D946EF"/>
    <rect x="30" y="35" width="60" height="60" rx="12" fill="#1E1E24" stroke="#333333"/>
    <text x="60" y="72" fill="#D946EF" font-family="-apple-system, sans-serif" font-weight="700" font-size="24" text-anchor="middle">⚡</text>
    <text x="110" y="52" fill="#FFFFFF" font-family="-apple-system, sans-serif" font-weight="700" font-size="18">Multi-modal RAG System</text>
    <text x="110" y="76" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-weight="400" font-size="13">High-throughput retrieval engine querying unstructured text, tables, and images.</text>
    <rect x="110" y="90" width="70" height="20" rx="6" fill="#1F1F2E"/>
    <text x="145" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">PyTorch</text>
    <rect x="188" y="90" width="50" height="20" rx="6" fill="#1F1F2E"/>
    <text x="213" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">SQL</text>
    <rect x="246" y="90" width="60" height="20" rx="6" fill="#1F1F2E"/>
    <text x="276" y="104" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">React</text>
    <circle cx="740" cy="65" r="18" fill="#1E1E24"/>
    <path d="M735 65 L745 65 M741 60 L746 65 L741 70" stroke="#FFFFFF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
  </svg>
</a>

<br/><br/>
<hr fill="#1F2937" height="1px" stroke="none"/>
<br/>

<!-- METRICS & STATS -->
<p align="center">
  <img src="https://img.shields.io/badge/METRICS-TELEMETRY-000000?style=for-the-badge&logoColor=white" fill="none"/>
</p>

<br/>

<!-- GitHub Stats -->
<img src="https://github-readme-stats.vercel.app/api?username=Hirthick-roshan&show_icons=true&theme=dark&bg_color=0D0D11&title_color=FFFFFF&text_color=9CA3AF&icon_color=8B5CF6&border_color=262626&hide_border=false&border_radius=16" fill="none" width="490"/>

<br/><br/>

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Hirthick-roshan&theme=react-dark&bg_color=0D0D11&hide_border=false&border_color=262626&color=8B5CF6&line=6366F1&point=FFFFFF&area=true&hide_title=true" fill="none" width="800"/>

<br/><br/>
<hr fill="#1F2937" height="1px" stroke="none"/>
<br/>

<!-- MINIMAL CONTACT FOOTER -->
<a href="https://linkedin.com/in/Hirthick-roshan">
  <img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=FFFFFF" height="35"/>
</a>
&nbsp;
<a href="https://github.com/Hirthick-roshan">
  <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=FFFFFF" height="35"/>
</a>
&nbsp;
<a href="mailto:your.email@domain.com">
  <img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=FFFFFF" height="35"/>
</a>
&nbsp;
<a href="https://leetcode.com/Hirthick-roshan">
  <img src="https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=leetcode&logoColor=FFA116" height="35"/>
</a>

<br/><br/>

<text fill="#4B5563" font-family="-apple-system, sans-serif" font-size="12">Designed with Precision &bull; Powered by GitHub Actions</text>

</div>
