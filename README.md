<p align="center">
  <a href="https://github.com/satriazoid">
    <img src=".image/Banner-profile.png" alt="Satria Alfarizki" width="100%" style="border-radius: 5px;"/>
  </a>
</p>

 <!-- Status Badges -->
   <div align="center">
    <img src="https://img.shields.io/badge/Status-Open%20to%20Work-0EA5E9?style=for-the-badge&logo=github&logoColor=white" alt="Status"/>
    <img src="https://img.shields.io/badge/Location-Indonesia-FF6B00?style=for-the-badge&logo=mapbox&logoColor=white" alt="Location"/>
    <img src="https://img.shields.io/badge/Focus-AI%20%26%20Automation-7C3AED?style=for-the-badge&logo=openai&logoColor=white" alt="Focus"/>
  </div>
  
  <br/>
  
  <!-- Quick Stats -->
  <div align="center">
    <img src="https://komarev.com/ghpvc/?username=satriazoid&style=flat-square&color=0EA5E9" alt="Profile Views"/>
    <img src="https://img.shields.io/github/followers/satriazoid?style=flat-square&logo=github&label=Followers&color=0EA5E9" alt="GitHub Followers"/>
  </div>

## Professional Summary

I am a Fullstack Developer and Data Science practitioner. My work spans systems programming in Go, automation built on Multi-LLM orchestration, and fullstack web engineering with React, Next.js, and Laravel.

Recent projects include a native Windows terminal written in Go, a multi-provider AI gateway with error-classified failover, open-source Python tooling for cleaning AI-generated text, and client systems such as automated data pipelines and admin dashboards.

## What I Build

### Systems Programming & AI Infrastructure (Go)
* **Native Windows Terminal:** GPU-free, mouse-first terminal for Windows in Go - ConPTY shell integration, a custom ANSI parser, and GDI rendering on a self-managed character grid. No browser engine, no webview, no JavaScript at runtime; frameless window with the tab strip doubling as the title bar.
* **Multi-Provider AI Gateway:** Single-binary Go gateway for LLM traffic with error-classified fallback logic (retryable errors advance to the next provider, terminal errors stop immediately), health-aware routing driven by EWMA latency tracking, per-model routing policies, and opt-in context compression. Runs at roughly 14-23 MB idle memory - no Node.js required.
* **Agent Safety Tooling:** Filesystem sandbox wrapper for local AI coding agents with whitelist/blacklist policy enforcement, fake-error blocking, audit logging, and Linux namespace isolation.

### AI Integration & Multi-LLM Orchestration
* **Orchestration Layer:** Built a multi-LLM orchestration layer integrating Gemini, GPT-4, and Claude, with API rotation and exponential backoff fallback logic.
* **Cost Control:** Applied restrictive prompt structures and context compression across model requests to lower API consumption.
* **Autonomous Workflows:** Built NLP data classification agents, multi-tenant chatbot workflows, and system-triggered analytical reporting tools.

### Data Engineering & Web Automation
* **Web Scraping:** Built scraping pipelines with Python, Selenium, and BeautifulSoup for client data collection, including proxy rotation, user-agent handling, and CAPTCHA-bypass middleware for restricted platforms.
* **ETL Pipelines:** Automated cleaning steps that validate, normalize, and load unstructured raw text into central databases.

### Fullstack Engineering
* **Web Applications:** Built web applications with React, Node.js, and Laravel, applying code-splitting and lazy-loading to improve load times.
* **Admin Dashboards:** Built dashboards with real-time Chart.js visualizations and JWT/RBAC access control.

### Open-Source Tooling
* **antitextai:** Published Python CLI that strips AI and LLM tells - invisible Unicode, smart quotes, banner separators, conversational frames - from text, Markdown, and source code. Ships as an installable Agent Skill for AI coding tools.
* **Academic Document Automation:** Built Python engines (MyDocument, WhitePaper, Universal-Academic-Document-Engine) that convert raw text into standards-compliant academic Word documents, with automatic sub-chapter detection and AI-text cleansing.
* **VS Code Extensions:** Developed Laragon-Controller for monitoring system resources and controlling Laragon services from the sidebar.

### Data Science & Decision Support Systems
* **Machine Learning Pipelines:** Built ensemble regression pipelines combining Random Forest, XGBoost, and LightGBM with spatial feature engineering and log-target transformation for housing price prediction.
* **Decision Support Systems:** Implemented AHP, SAW, and WP methods for ICU patient prioritization based on medical severity (WiDS Datathon 2020 dataset).
* **NLP & Analytics:** Sentiment analysis using neural network and LSTM approaches; analytics dashboards with Streamlit, Pandas, and SQLite.

### DevOps & Cloud Infrastructure
* **Database Administration:** Managed MySQL and PostgreSQL databases on AWS and Hostinger, covering performance tuning, relational indexing, and automated backups.
* **CI/CD:** Set up GitHub Actions pipelines and Docker containerization for client projects.

## Writing & Publication

I write about Multi-LLM orchestration, web scraping implementation, and infrastructure tuning.

<p align="left">
  <a href="https://satriazoid.substack.com" target="_blank">
    <img src="https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Substack" />
  </a>
</p>


## Technical Stack

<div align="center">
  
  <!-- Wrapped in a dynamic HTML table to prevent broken text alignment -->
  <table border="0" cellpadding="0" cellspacing="0">
    <tr>
      <td align="center" valign="middle">
        <img src="https://github-readme-stats.vercel.app/api?username=satriazoid&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117" alt="" width="400px"/>
      </td>
      <td align="center" valign="middle">
        <img src="https://github-readme-streak-stats.herokuapp.com?user=satriazoid&theme=dark&hide_border=true&bg_color=0d1117&stroke=0EA5E9&currStreakLabel=0EA5E9" alt="" width="400px"/>
      </td>
    </tr>
  </table>

  <br/><br/>
  
<table width="100%">
  <tr>
    <td width="25%" valign="top" align="left"><strong>Languages</strong></td>
    <td valign="top" align="left">
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Go"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white" alt="PHP"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" alt="MySQL"/>
    </td>
  </tr>

  <tr>
    <td width="25%" valign="top" align="left"><strong>Frontend & UI</strong></td>
    <td valign="top" align="left">
      <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js"/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
      <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
      <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white" alt="Chart.js"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3"/>
    </td>
  </tr>

  <tr>
    <td width="25%" valign="top" align="left"><strong>Backend & Automation</strong></td>
    <td valign="top" align="left">
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js"/>
      <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white" alt="Laravel"/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white" alt="Express"/>
      <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white" alt="Selenium"/>
      <img src="https://img.shields.io/badge/Web_Scraping-4CAF50?style=flat&logo=python&logoColor=white" alt="Web Scraping"/>
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase"/>
    </td>
  </tr>

<tr>
  <td width="25%" valign="top" align="left"><strong>Data & Analytics</strong></td>
  <td valign="top" align="left">
    <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas"/>
    <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy"/>
    <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" alt="Streamlit"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
    <img src="https://img.shields.io/badge/JupyterLab-F37626?style=flat&logo=jupyter&logoColor=white" alt="JupyterLab"/>
    <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white" alt="Google Colab"/>
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
    <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" alt="SQLite"/>
  </td>
</tr>

  <tr>
    <td width="25%" valign="top" align="left"><strong>DevOps & Deployment</strong></td>
    <td valign="top" align="left">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" alt="Nginx"/>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux"/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white" alt="AWS"/>
      <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" alt="Cloudflare"/>
      <img src="https://img.shields.io/badge/Hostinger-673DE6?style=flat&logo=hostinger&logoColor=white" alt="Hostinger"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>
      <img src="https://img.shields.io/badge/pnpm-F69220?style=flat&logo=pnpm&logoColor=white" alt="pnpm"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" alt="Vercel"/>
    </td>
  </tr>
</table>

</div>



## Connect With Me

<div align="center">
  <a href="mailto:satriaalfarizkib2@gmail.com">
    <img
      src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"
      alt="Gmail"
    />
  </a>

  <a href="mailto:satriaalfa77@outlook.com">
    <img
      src="https://img.shields.io/badge/Outlook-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white"
      alt="Outlook"
    />
  </a>
  <a href="https://www.instagram.com/satrialpha/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://satriazoid.substack.com" target="_blank">
    <img src="https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Substack" />
  </a>
  <br/><br/>
  <sub>Built by Satriazoid</sub>
</div>
