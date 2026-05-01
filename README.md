
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  .profile { padding: 2rem 0; max-width: 680px; font-family: var(--font-sans); }
  .header { text-align: center; margin-bottom: 2.5rem; }
  .name { font-size: 26px; font-weight: 500; color: var(--color-text-primary); letter-spacing: -0.5px; }
  .tagline { font-size: 13px; color: var(--color-text-secondary); margin-top: 6px; font-family: var(--font-mono); }
  .cursor { display: inline-block; width: 2px; height: 14px; background: #00c896; margin-left: 2px; animation: blink 1s step-end infinite; vertical-align: middle; }
  @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }
  .section { margin-bottom: 2rem; }
  .section-label { font-size: 11px; font-weight: 500; color: var(--color-text-tertiary); text-transform: uppercase; letter-spacing: 1.5px; margin-bottom: 12px; }
  .chips { display: flex; flex-wrap: wrap; gap: 8px; }
  .chip { display: inline-flex; align-items: center; gap: 6px; padding: 5px 12px; border-radius: 999px; border: 0.5px solid var(--color-border-secondary); font-size: 12px; font-weight: 500; color: var(--color-text-secondary); background: var(--color-background-primary); transition: border-color 0.2s; }
  .chip:hover { border-color: var(--color-border-primary); color: var(--color-text-primary); }
  .chip-dot { width: 7px; height: 7px; border-radius: 50%; flex-shrink: 0; }
  .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 10px; }
  .project-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 14px 16px; cursor: pointer; transition: border-color 0.2s, background 0.2s; text-decoration: none; display: block; }
  .project-card:hover { border-color: var(--color-border-primary); background: var(--color-background-secondary); }
  .project-icon { font-size: 16px; margin-bottom: 8px; }
  .project-name { font-size: 13px; font-weight: 500; color: var(--color-text-primary); margin-bottom: 4px; }
  .project-desc { font-size: 12px; color: var(--color-text-secondary); line-height: 1.5; }
  .contact-row { display: flex; flex-wrap: wrap; gap: 8px; align-items: center; }
  .contact-link { display: inline-flex; align-items: center; gap: 7px; padding: 7px 14px; border-radius: 999px; border: 0.5px solid var(--color-border-secondary); font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-decoration: none; transition: all 0.2s; }
  .contact-link:hover { color: var(--color-text-primary); border-color: var(--color-border-primary); background: var(--color-background-secondary); }
  .contact-icon { width: 16px; height: 16px; display: flex; align-items: center; justify-content: center; }
  .divider { height: 0.5px; background: var(--color-border-tertiary); margin: 1.5rem 0; }
  .motto { font-size: 13px; color: var(--color-text-tertiary); text-align: center; font-style: italic; margin-top: 1.5rem; }
  .dot-java { background: #e8a56b; }
  .dot-spring { background: #50c9a0; }
  .dot-aws { background: #f0a04b; }
  .dot-db { background: #4a90d9; }
  .dot-js { background: #f7df1e; }
  .dot-react { background: #61dafb; }
  .dot-git { background: #f05032; }
  .dot-linux { background: #fcc624; }
</style>

<div class="profile">
  <div class="header">
    <div class="name">Rakesh Kayal<span class="cursor"></span></div>
    <div class="tagline">Backend Engineer &nbsp;·&nbsp; Java &amp; Spring Boot</div>
  </div>

  <div class="section">
    <div class="section-label">Tech Stack</div>
    <div class="chips">
      <span class="chip"><span class="chip-dot dot-java"></span>Java</span>
      <span class="chip"><span class="chip-dot dot-spring"></span>Spring Boot</span>
      <span class="chip"><span class="chip-dot dot-spring"></span>Spring AI</span>
      <span class="chip"><span class="chip-dot dot-db"></span>MySQL</span>
      <span class="chip"><span class="chip-dot dot-spring"></span>MongoDB</span>
      <span class="chip"><span class="chip-dot dot-aws"></span>AWS</span>
      <span class="chip"><span class="chip-dot dot-js"></span>JavaScript</span>
      <span class="chip"><span class="chip-dot dot-react"></span>React</span>
      <span class="chip"><span class="chip-dot dot-git"></span>Git</span>
      <span class="chip"><span class="chip-dot dot-linux"></span>Linux</span>
    </div>
  </div>

  <div class="section">
    <div class="section-label">Featured Projects</div>
    <div class="projects">
      <a class="project-card" href="https://github.com/rakeshkayal/predictive-api" target="_blank">
        <div class="project-icon">⚙</div>
        <div class="project-name">Predictive API</div>
        <div class="project-desc">Prediction endpoints built with Spring Boot</div>
      </a>
      <a class="project-card" href="https://github.com/rakeshkayal/chrome-ext" target="_blank">
        <div class="project-icon">⬡</div>
        <div class="project-name">Chrome Extension</div>
        <div class="project-desc">Browser productivity tool with AI integration</div>
      </a>
      <a class="project-card" href="https://github.com/rakeshkayal/chat-app" target="_blank">
        <div class="project-icon">◈</div>
        <div class="project-name">Real-time Chat</div>
        <div class="project-desc">WebSocket-based chat app built with Spring</div>
      </a>
    </div>
  </div>

  <div class="divider"></div>

  <div class="section">
    <div class="section-label">Reach me</div>
    <div class="contact-row">
      <a class="contact-link" href="mailto:rakeshkayal276@gmail.com">
        <svg class="contact-icon" viewBox="0 0 16 16" fill="none"><rect x="1" y="3" width="14" height="10" rx="1.5" stroke="currentColor" stroke-width="1.2"/><path d="M1 4.5l7 5 7-5" stroke="currentColor" stroke-width="1.2"/></svg>
        rakeshkayal276@gmail.com
      </a>
      <a class="contact-link" href="https://linkedin.com/in/rakeshkayal" target="_blank">
        <svg class="contact-icon" viewBox="0 0 16 16" fill="currentColor"><rect x="1" y="1" width="14" height="14" rx="2"/><path d="M4 6.5h1.5V12H4zM4.75 5.5a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5zM7 6.5h1.4v.75h.02C8.67 6.8 9.3 6.4 10 6.4c1.6 0 1.9 1.05 1.9 2.4V12h-1.5V9.1c0-.55-.01-1.25-.76-1.25-.77 0-.89.6-.89 1.2V12H7z" fill="white"/></svg>
        LinkedIn
      </a>
      <a class="contact-link" href="https://github.com/rakeshkayal" target="_blank">
        <svg class="contact-icon" viewBox="0 0 16 16" fill="currentColor"><path d="M8 1C4.13 1 1 4.13 1 8c0 3.09 2 5.71 4.79 6.63.35.06.48-.15.48-.34v-1.2c-1.95.42-2.36-.94-2.36-.94-.32-.81-.78-1.02-.78-1.02-.64-.44.05-.43.05-.43.7.05 1.07.72 1.07.72.62 1.07 1.64.76 2.04.58.06-.45.24-.76.44-.93-1.55-.18-3.19-.78-3.19-3.46 0-.76.27-1.39.72-1.88-.07-.18-.31-.89.07-1.85 0 0 .59-.19 1.93.72A6.7 6.7 0 0 1 8 4.84c.6 0 1.2.08 1.76.23 1.34-.91 1.93-.72 1.93-.72.38.96.14 1.67.07 1.85.45.49.72 1.12.72 1.88 0 2.69-1.64 3.28-3.2 3.46.25.22.48.65.48 1.31v1.94c0 .19.13.4.49.33A7.003 7.003 0 0 0 15 8c0-3.87-3.13-7-7-7z"/></svg>
        GitHub
      </a>
    </div>
  </div>

  <div class="motto">Work smart — without watching the clock</div>
</div>
