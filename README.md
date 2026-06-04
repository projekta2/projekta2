<!-- ─────────────────────────────────────────────────────────────────────────
     VISUAL ENHANCEMENT LAYER
     CSS below is active in GitLab · Gitea · GitHub Enterprise.
     github.com sanitizes <style> tags — every animation has an
     image-based fallback so the README looks great regardless.
     ───────────────────────────────────────────────────────────────────────── -->
<style>
  @keyframes pulseGlow {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.7; transform: scale(1.1); }
  }
  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
  }
  h2, h3, table, p, blockquote, details {
    animation: fadeInUp 0.5s ease both;
  }
  a > img {
    transition: transform 0.2s ease, filter 0.2s ease;
  }
  a > img:hover {
    transform: translateY(-2px);
    filter: brightness(1.05) drop-shadow(0 2px 6px rgba(249,115,22,0.3));
  }
  td {
    border-radius: 12px !important;
    padding: 20px !important;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  td:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(249,115,22,0.15);
  }
  .dot {
    display: inline-block;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #f97316;
    animation: pulseGlow 2s ease-in-out infinite;
    vertical-align: middle;
    margin-right: 6px;
  }
  code {
    background: rgba(249,115,22,0.08) !important;
    border: 1px solid rgba(249,115,22,0.2) !important;
    border-radius: 4px !important;
    padding: 2px 6px !important;
    font-size: 0.85em !important;
    color: #f97316 !important;
  }
  blockquote {
    border-left: 3px solid #f97316 !important;
    padding-left: 14px !important;
    color: #6b7280 !important;
  }
</style>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f97316,100:ea580c&height=200&section=header&text=Alexandre%20Iglesias&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Chrome%20Extension%20Developer%20%C2%B7%20Visual%20Designer%20%C2%B7%20Girona%2C%20Spain&descAlignY=56&descSize=15&descColor=ffffffcc" width="100%" />
</p>

<br />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=F97316&center=true&vCenter=true&width=620&lines=Building+extensions+that+respect+your+time.;Visual+Designer+who+learned+to+code.;Obsessed+with+detail%2C+bilingual+UX%2C+dark+mode+done+right." alt="Typing SVG" />
</p>

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## Who I am

I'm a Visual Designer who crossed into code — not by accident, but because the tools I wanted didn't exist yet.

I spent years running **Projekta2 Creative Studio**, building immersive web experiences at the intersection of design and engineering: the kind where you're not sure if you're looking at a website or an installation.

That background shapes everything I ship: obsession with detail, bilingual UX from day one, and dark mode that actually works.

Now I'm building Chrome extensions — small, focused tools for freelancers and developers who value their time.

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## What I'm building

<table width="100%">
  <tr>
    <td width="50%" valign="top">

### ◆ TabCost Pro

<p>
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Price-%245%20one--time%2C%20no%20subscription-f97316?style=flat-square" />
  <img src="https://img.shields.io/badge/Chrome%20Web%20Store-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
</p>

> *Every minute a tab sits idle, your time bleeds quietly. TabCost makes the cost visible.*

You work at an hourly rate. Your open tabs don't. TabCost Pro tracks inactive browser tabs and converts idle time into real opportunity cost — so you finally close the 23 tabs you've had open since Tuesday.

**Built for:** freelancers, consultants, anyone billing by the hour.

**What it does:**

▹ Real-time cost tracker per tab, based on your hourly rate  
▹ Auto-close idle tabs (configurable threshold)  
▹ CSV export for billing or time audits  
▹ Dark / Light themes · Bilingual EN/ES  
▹ One-time payment, no subscription  

<p>
  <a href="https://chromewebstore.google.com/detail/tabcost-pro/oifegknejkfiibmfapdfcgemclgmmghm"><img src="https://img.shields.io/badge/Install%20Free-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://projekta2.gumroad.com/l/tabcost-pro"><img src="https://img.shields.io/badge/Buy%20Pro%20%E2%80%94%20%245-ff90e8?style=for-the-badge&logo=gumroad&logoColor=black" /></a>
  <a href="https://projekta2.github.io/tabcost-landing/"><img src="https://img.shields.io/badge/Landing%20Page-f97316?style=for-the-badge" /></a>
</p>

<details>
<summary><code>Tech stack</code></summary>
<br />
<code>Manifest V3</code> · <code>Chrome Storage API</code> · <code>Chart.js</code> · <code>i18n</code> · <code>Gumroad licensing</code>
</details>

  </td>
    <td width="50%" valign="top">

### ◇ PR Focus Pro

<p>
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Pro%20%E2%80%94%20%249.50%20one--time%2C%20no%20subscription-f97316?style=flat-square" />
  <img src="https://img.shields.io/badge/Freemium-available-blue?style=flat-square" />
</p>

> *Your GitHub PR inbox is a mess. PR Focus Pro brings AI-powered clarity to the chaos.*

PR Focus Pro sits on top of GitHub and uses AI to summarize, score, and prioritize your pull requests — so you review what matters first, not what arrived first.

**Built for:** developers managing multiple repos or multi-account GitHub workflows.

**What it does:**

▹ AI summaries + risk scoring (0–100) per PR  
▹ Hybrid priority queue: CI status + age + AI risk  
▹ One-click draft review generation  
▹ Multi-account GitHub support  
▹ 100% local (BYOK) — OpenAI, Groq, Mistral, Ollama  
▹ Freemium: core free / Pro $9.50 one-time  

<p>
  <a href="https://projekta2.gumroad.com/l/PRFocusAIPro"><img src="https://img.shields.io/badge/Buy%20Pro%20%E2%80%94%20%249.50-ff90e8?style=for-the-badge&logo=gumroad&logoColor=black" /></a>
  <a href="https://projekta2.github.io/projekta2-pr-focus-landing/"><img src="https://img.shields.io/badge/Landing%20Page-f97316?style=for-the-badge" /></a>
  <a href="https://projekta2.github.io/projekta2-pr-focus-landing/pr-focus-demo.html"><img src="https://img.shields.io/badge/Live%20Demo-ff69b4?style=for-the-badge" /></a>
</p>

<details>
<summary><code>Tech stack</code></summary>
<br />
<code>GraphQL + REST</code> · <code>IndexedDB</code> · <code>AI prompt engineering</code> · <code>Gumroad license validation</code>
</details>

  </td>
  </tr>
</tr>

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## What I believe about software

Most tools are built to impress on a demo. I build for the third week of use — when the novelty is gone and all that's left is whether it actually saves you time.

That means: no dark patterns, no fake urgency, no subscription traps for features that should be one-time. Just tools that do one thing well, with care for the person using them.

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## Stack

<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Chrome%20Extensions%20MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/After%20Effects-9999FF?style=flat-square&logo=adobe-after-effects&logoColor=white" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white" />
</p>

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## If you're a potential client or employer

**Clients:** Both extensions are live and available to install or buy today. The best way to evaluate my work is to use it. If you have a specific use case or want a custom extension built, reach out.

**Employers / freelance:** I bring an unusual combination — production-level visual design and working knowledge of Chrome Extension APIs, AI integration, and JavaScript from scratch. I care deeply about UX that doesn't require a tutorial.

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## Let's talk

<span class="dot"></span>

<p>
  <a href="mailto:hello@projekta2.com"><img src="https://img.shields.io/badge/hello@projekta2.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/alexiglesias1"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/projekta2"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p><sub><i>Building in public · Girona, Spain · Always open to interesting problems.</i></sub></p>

<br />

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f97316,100:ea580c&height=100&section=footer" width="100%" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f97316,100:ea580c&height=200&section=header&text=Alexandre%20Iglesias&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Chrome%20Extension%20Developer%20%C2%B7%20Visual%20Designer%20%C2%B7%20Girona%2C%20Spain&descAlignY=56&descSize=15&descColor=ffffffcc" width="100%" />
</p>

<br />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=F97316&center=true&vCenter=true&width=620&lines=Building+extensions+that+respect+your+time.;Visual+Designer+who+learned+to+code.;Obsessed+with+detail%2C+bilingual+UX%2C+dark+mode+done+right." alt="Typing SVG" />
</p>

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## Who I am

I'm a Visual Designer who crossed into code — not by accident, but because the tools I wanted didn't exist yet.

I spent years running **Projekta2 Creative Studio**, building immersive web experiences at the intersection of design and engineering: the kind where you're not sure if you're looking at a website or an installation.

That background shapes everything I ship: obsession with detail, bilingual UX from day one, and dark mode that actually works.

Now I'm building Chrome extensions — small, focused tools for freelancers and developers who value their time.

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## What I'm building

<table width="100%">
  <tr>
    <td width="50%" valign="top">

### ◆ TabCost Pro

<p>
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Price-%245%20one--time%2C%20no%20subscription-f97316?style=flat-square" />
  <img src="https://img.shields.io/badge/Chrome%20Web%20Store-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
</p>

> *Every minute a tab sits idle, your time bleeds quietly. TabCost makes the cost visible.*

You work at an hourly rate. Your open tabs don't. TabCost Pro tracks inactive browser tabs and converts idle time into real opportunity cost — so you finally close the 23 tabs you've had open since Tuesday.

**Built for:** freelancers, consultants, anyone billing by the hour.

**What it does:**

▹ Real-time cost tracker per tab, based on your hourly rate  
▹ Auto-close idle tabs (configurable threshold)  
▹ CSV export for billing or time audits  
▹ Dark / Light themes · Bilingual EN/ES  
▹ One-time payment, no subscription  

<p>
  <a href="https://chromewebstore.google.com/detail/tabcost-pro/oifegknejkfiibmfapdfcgemclgmmghm"><img src="https://img.shields.io/badge/Install%20Free-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://projekta2.gumroad.com/l/tabcost-pro"><img src="https://img.shields.io/badge/Buy%20Pro%20%E2%80%94%20%245-ff90e8?style=for-the-badge&logo=gumroad&logoColor=black" /></a>
  <a href="https://projekta2.github.io/tabcost-landing/"><img src="https://img.shields.io/badge/Landing%20Page-f97316?style=for-the-badge" /></a>
</p>

<details>
<summary><code>Tech stack</code></summary>
<br />
<code>Manifest V3</code> · <code>Chrome Storage API</code> · <code>Chart.js</code> · <code>i18n</code> · <code>Gumroad licensing</code>
</details>

  </td>
    <td width="50%" valign="top">

### ◇ PR Focus Pro

<p>
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Pro%20%E2%80%94%20%249.50%20one--time%2C%20no%20subscription-f97316?style=flat-square" />
  <img src="https://img.shields.io/badge/Freemium-available-blue?style=flat-square" />
</p>

> *Your GitHub PR inbox is a mess. PR Focus Pro brings AI-powered clarity to the chaos.*

PR Focus Pro sits on top of GitHub and uses AI to summarize, score, and prioritize your pull requests — so you review what matters first, not what arrived first.

**Built for:** developers managing multiple repos or multi-account GitHub workflows.

**What it does:**

▹ AI summaries + risk scoring (0–100) per PR  
▹ Hybrid priority queue: CI status + age + AI risk  
▹ One-click draft review generation  
▹ Multi-account GitHub support  
▹ 100% local (BYOK) — OpenAI, Groq, Mistral, Ollama  
▹ Freemium: core free / Pro $9.50 one-time  

<p>
  <a href="https://projekta2.gumroad.com/l/PRFocusAIPro"><img src="https://img.shields.io/badge/Buy%20Pro%20%E2%80%94%20%249.50-ff90e8?style=for-the-badge&logo=gumroad&logoColor=black" /></a>
  <a href="https://projekta2.github.io/projekta2-pr-focus-landing/"><img src="https://img.shields.io/badge/Landing%20Page-f97316?style=for-the-badge" /></a>
  <a href="https://projekta2.github.io/projekta2-pr-focus-landing/pr-focus-demo.html"><img src="https://img.shields.io/badge/Live%20Demo-ff69b4?style=for-the-badge" /></a>
</p>

<details>
<summary><code>Tech stack</code></summary>
<br />
<code>GraphQL + REST</code> · <code>IndexedDB</code> · <code>AI prompt engineering</code> · <code>Gumroad license validation</code>
</details>

  </td>
  </tr>
</table>

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## What I believe about software

Most tools are built to impress on a demo. I build for the third week of use — when the novelty is gone and all that's left is whether it actually saves you time.

That means: no dark patterns, no fake urgency, no subscription traps for features that should be one-time. Just tools that do one thing well, with care for the person using them.

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## Stack

<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Chrome%20Extensions%20MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/After%20Effects-9999FF?style=flat-square&logo=adobe-after-effects&logoColor=white" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white" />
</p>

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## If you're a potential client or employer

**Clients:** Both extensions are live and available to install or buy today. The best way to evaluate my work is to use it. If you have a specific use case or want a custom extension built, reach out.

**Employers / freelance:** I bring an unusual combination — production-level visual design and working knowledge of Chrome Extension APIs, AI integration, and JavaScript from scratch. I care deeply about UX that doesn't require a tutorial.

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:f97316,100:ea580c&height=3&reversal=false" width="100%" />

<br />

## Let's talk

<span class="dot"></span>

<p>
  <a href="mailto:hello@projekta2.com"><img src="https://img.shields.io/badge/hello@projekta2.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/alexiglesias1"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/projekta2"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p><sub><i>Building in public · Girona, Spain · Always open to interesting problems.</i></sub></p>

<br />

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f97316,100:ea580c&height=100&section=footer" width="100%" />
</p>
