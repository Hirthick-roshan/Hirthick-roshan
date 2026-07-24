<div align="center">

  <!-- MODERN HERO BANNER SVG -->
  <svg viewBox="0 0 1000 280" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Deep Dark Background Gradient -->
      <linearGradient id="hero-bg" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#0a0a0c"/>
        <stop offset="50%" stop-color="#121318"/>
        <stop offset="100%" stop-color="#070709"/>
      </linearGradient>

      <!-- Glass Fill -->
      <linearGradient id="glass" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#ffffff" stop-opacity="0.04"/>
        <stop offset="100%" stop-color="#ffffff" stop-opacity="0.01"/>
      </linearGradient>

      <!-- Glass Border Glow -->
      <linearGradient id="border-glow" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#6366f1" stop-opacity="0.5"/>
        <stop offset="50%" stop-color="#8b5cf6" stop-opacity="0.2"/>
        <stop offset="100%" stop-color="#d946ef" stop-opacity="0.4"/>
      </linearGradient>

      <!-- Title Text Gradient -->
      <linearGradient id="title-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#FFFFFF"/>
        <stop offset="70%" stop-color="#E2E8F0"/>
        <stop offset="100%" stop-color="#94A3B8"/>
      </linearGradient>

      <!-- Accent Text Gradient -->
      <linearGradient id="accent-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#6366F1"/>
        <stop offset="50%" stop-color="#8B5CF6"/>
        <stop offset="100%" stop-color="#D946EF"/>
      </linearGradient>

      <!-- Ambient Glow Orbs -->
      <radialGradient id="orb-indigo" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#6366F1" stop-opacity="0.25"/>
        <stop offset="100%" stop-color="#6366F1" stop-opacity="0"/>
      </radialGradient>

      <!-- Grid Pattern -->
      <pattern id="grid-pattern" width="30" height="30" patternUnits="userSpaceOnUse">
        <path d="M 30 0 L 0 0 0 30" fill="none" stroke="#ffffff" stroke-opacity="0.03" stroke-width="1"/>
      </pattern>
    </defs>

    <!-- Canvas -->
    <rect width="1000" height="280" rx="20" fill="url(#hero-bg)"/>
    <rect width="1000" height="280" rx="20" fill="url(#grid-pattern)"/>

    <!-- Ambient Glows -->
    <circle cx="150" cy="80" r="200" fill="url(#orb-indigo)"/>
    <circle cx="850" cy="200" r="220" fill="url(#orb-indigo)"/>

    <!-- Main Card Container -->
    <g transform="translate(40, 30)">
      <rect width="920" height="220" rx="16" fill="url(#glass)" stroke="url(#border-glow)" stroke-width="1.5"/>

      <!-- Status Pill -->
      <g transform="translate(360, 28)">
        <rect width="200" height="28" rx="14" fill="#10B981" fill-opacity="0.1" stroke="#10B981" stroke-opacity="0.3" stroke-width="1"/>
        <circle cx="18" cy="14" r="4" fill="#10B981"/>
        <text x="32" y="18" fill="#10B981" font-family="-apple-system, sans-serif" font-size="11" font-weight="700" letter-spacing="1">AVAILABLE FOR AI ROLES</text>
      </g>

      <!-- Name & Title -->
      <text x="460" y="102" text-anchor="middle" fill="url(#title-grad)" font-family="-apple-system, BlinkMacSystemFont, 'SF Pro Display', sans-serif" font-weight="800" font-size="42" letter-spacing="-1">HIRTHICK ROSHAN R</text>
      <text x="460" y="136" text-anchor="middle" fill="url(#accent-grad)" font-family="-apple-system, BlinkMacSystemFont, 'SF Pro Text', sans-serif" font-weight="600" font-size="15" letter-spacing="2">AI ENGINEER &nbsp;•&nbsp; MACHINE LEARNING ENGINEER</text>

      <!-- Subtitle Tech Badges -->
      <g transform="translate(460, 178)" text-anchor="middle">
        <text x="0" y="0" fill="#94A3B8" font-family="-apple-system, sans-serif" font-size="13" font-weight="500" letter-spacing="0.5">
          Autonomous Agents &nbsp;|&nbsp; Local RAG Systems &nbsp;|&nbsp; Full-Stack GenAI
        </text>
      </g>
    </g>
  </svg>

  <br/><br/>

  <!-- ANIMATED TYPING LINE -->
  <a href="https://linkedin.com/in/hirthick-roshan">
    <img src="https://readme-typing-svg.demolab.com?font=SF+Pro+Display&weight=600&size=18&duration=2500&pause=1000&color=A5B4FC&center=true&vCenter=true&width=600&height=35&lines=Building+autonomous+multi-agent+pipelines.;Engineering+local+RAG+systems+with+zero+API+cost.;FastAPI+%E2%80%A2+LangGraph+%E2%80%A2+ChromaDB+%E2%80%A2+PyTorch" alt="Typing SVG" />
  </a>

  <br/><br/>
  <hr fill="#1E293B" height="1px" stroke="none" />
  <br/>

  <!-- SKILLS SECTION (PURE SVG CARDS - NO TABLE BORDERS) -->
  <p align="center">
    <img src="https://img.shields.io/badge/CORE_STACK-000000?style=for-the-badge&logoColor=white" />
  </p>

  <br/>

  <svg viewBox="0 0 800 180" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="card-bg" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#121318"/>
        <stop offset="100%" stop-color="#0c0d10"/>
      </linearGradient>
    </defs>

    <!-- Row 1 -->
    <g transform="translate(0, 0)">
      <!-- Python -->
      <g transform="translate(10, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">Python</text>
      </g>
      <!-- FastAPI -->
      <g transform="translate(165, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">FastAPI</text>
      </g>
      <!-- LangGraph -->
      <g transform="translate(320, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://raw.githubusercontent.com/langchain-ai/langchain/master/docs/static/img/langchain_stack.png" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">LangGraph</text>
      </g>
      <!-- PyTorch -->
      <g transform="translate(475, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">PyTorch</text>
      </g>
      <!-- Hugging Face -->
      <g transform="translate(630, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">HuggingFace</text>
      </g>
    </g>

    <!-- Row 2 -->
    <g transform="translate(0, 90)">
      <!-- Docker -->
      <g transform="translate(10, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">Docker</text>
      </g>
      <!-- React -->
      <g transform="translate(165, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">React</text>
      </g>
      <!-- SQL -->
      <g transform="translate(320, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">SQL</text>
      </g>
      <!-- Git -->
      <g transform="translate(475, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" x="55" y="12" width="30" height="30"/>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">Git</text>
      </g>
      <!-- Vector DB -->
      <g transform="translate(630, 0)">
        <rect width="140" height="75" rx="12" fill="url(#card-bg)" stroke="#262626" stroke-width="1"/>
        <text x="70" y="32" fill="#8B5CF6" font-family="-apple-system, sans-serif" font-size="20" text-anchor="middle">⚡</text>
        <text x="70" y="58" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">ChromaDB</text>
      </g>
    </g>
  </svg>

  <br/><br/>
  <hr fill="#1E293B" height="1px" stroke="none" />
  <br/>

  <!-- FEATURED PROJECTS CARDS (CLEAN SVG) -->
  <p align="center">
    <img src="https://img.shields.io/badge/FEATURED_SYSTEMS-000000?style=for-the-badge&logoColor=white" />
  </p>

  <br/>

  <!-- Project 1 -->
  <a href="https://github.com/Hirthick-roshan">
    <svg viewBox="0 0 800 110" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
      <rect width="800" height="110" rx="14" fill="#121318" stroke="#262626" stroke-width="1"/>
      <rect x="0" y="0" width="5" height="110" rx="2" fill="#6366F1"/>
      <text x="30" y="42" fill="#FFFFFF" font-family="-apple-system, sans-serif" font-weight="700" font-size="17">🤖 Autonomous Research Agent with Episodic Memory</text>
      <text x="30" y="66" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-weight="400" font-size="12">Decomposes sub-questions, executes DuckDuckGo web searches, &amp; synthesizes reports via LangGraph &amp; ChromaDB[cite: 1].</text>
      <rect x="30" y="78" width="80" height="18" rx="4" fill="#1F1F2E"/><text x="70" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">LangGraph</text>
      <rect x="118" y="78" width="75" height="18" rx="4" fill="#1F1F2E"/><text x="155" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">ChromaDB</text>
      <rect x="201" y="78" width="85" height="18" rx="4" fill="#1F1F2E"/><text x="243" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">Llama3 / Ollama</text>
    </svg>
  </a>

  <br/><br/>

  <!-- Project 2 -->
  <a href="https://github.com/Hirthick-roshan">
    <svg viewBox="0 0 800 110" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
      <rect width="800" height="110" rx="14" fill="#121318" stroke="#262626" stroke-width="1"/>
      <rect x="0" y="0" width="5" height="110" rx="2" fill="#8B5CF6"/>
      <text x="30" y="42" fill="#FFFFFF" font-family="-apple-system, sans-serif" font-weight="700" font-size="17">⚡ Multi-Modal RAG System (Zero API Dependency)</text>
      <text x="30" y="66" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-weight="400" font-size="12">Local search system querying unstructured text and graphics from textbooks using CLIP cross-modal embeddings[cite: 1].</text>
      <rect x="30" y="78" width="60" height="18" rx="4" fill="#1F1F2E"/><text x="60" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">PyTorch</text>
      <rect x="98" y="78" width="50" height="18" rx="4" fill="#1F1F2E"/><text x="123" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">CLIP</text>
      <rect x="156" y="78" width="75" height="18" rx="4" fill="#1F1F2E"/><text x="193" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">ChromaDB</text>
    </svg>
  </a>

  <br/><br/>

  <!-- Project 3 -->
  <a href="https://github.com/Hirthick-roshan">
    <svg viewBox="0 0 800 110" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
      <rect width="800" height="110" rx="14" fill="#121318" stroke="#262626" stroke-width="1"/>
      <rect x="0" y="0" width="5" height="110" rx="2" fill="#D946EF"/>
      <text x="30" y="42" fill="#FFFFFF" font-family="-apple-system, sans-serif" font-weight="700" font-size="17">📄 AI Resume Screening &amp; Hiring Platform</text>
      <text x="30" y="66" fill="#9CA3AF" font-family="-apple-system, sans-serif" font-weight="400" font-size="12">Full-stack ATS platform with sentence-transformers semantic matching &amp; proctored technical testing[cite: 1].</text>
      <rect x="30" y="78" width="60" height="18" rx="4" fill="#1F1F2E"/><text x="60" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">FastAPI</text>
      <rect x="98" y="78" width="50" height="18" rx="4" fill="#1F1F2E"/><text x="123" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">React</text>
      <rect x="156" y="78" width="50" height="18" rx="4" fill="#1F1F2E"/><text x="181" y="91" fill="#A5B4FC" font-family="-apple-system, sans-serif" font-size="10" font-weight="600" text-anchor="middle">spaCy</text>
    </svg>
  </a>

  <br/><br/>
  <hr fill="#1E293B" height="1px" stroke="none" />
  <br/>

  <!-- CONNECT PROFILE LINKS -->
  <p align="center">
    <img src="https://img.shields.io/badge/CONNECT-000000?style=for-the-badge&logoColor=white" />
  </p>

  <br/>

  <a href="https://linkedin.com/in/hirthick-roshan">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://leetcode.com/u/Hirthick_roshan/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://www.hackerrank.com/profile/hirthickroshan24">
    <img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black"/>
  </a>
  &nbsp;&nbsp;
  <a href="mailto:hirthickroshan24@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

</div>
