<!-- README.md: Neovim-style HTML + inline-CSS profile for GitHub -->

<div align="center" style="margin-bottom:12px;">
  <!-- Header (pseudo-title bar) -->
  <div style="display:inline-block; width:min(900px,95%); text-align:left; font-family: 'Fira Code', ui-monospace, SFMono-Regular, Menlo, Monaco, 'Roboto Mono', monospace;">
    <div style="background:#0b0f10; border-top-left-radius:8px; border-top-right-radius:8px; padding:8px 12px; display:flex; align-items:center; gap:8px; box-shadow:0 6px 18px rgba(0,0,0,0.6);">
      <div style="width:10px; height:10px; background:#ff5f56; border-radius:50%;"></div>
      <div style="width:10px; height:10px; background:#ffbd2e; border-radius:50%;"></div>
      <div style="width:10px; height:10px; background:#27c93f; border-radius:50%;"></div>
      <div style="flex:1; color:#9ae6b4; font-weight:600;">README.md — Natnat@rye0x — nvim</div>
      <div style="color:#6b7280; font-size:12px;">NORMAL</div>
    </div>

    <!-- "Buffer" area -->
    <div style="background:#000a0b; color:#9ae6b4; padding:20px; border-bottom-left-radius:8px; border-bottom-right-radius:8px; border:1px solid rgba(160, 255, 180, 0.04);">
      
      <!-- Intro "typing" line (static image used as effect) -->
      <div style="display:flex; align-items:center; gap:10px; margin-bottom:8px;">
        <div style="font-family: 'Fira Code', monospace; color:#8be68b; font-weight:700; font-size:14px;">💻 Natnat@GitHub:~$</div>
        <img alt="typing" src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=14&duration=2800&pause=800&color=8be68b&width=480&lines=Welcome+to+my+GitHub!;Neovim+style+profile;I+code+in+Vim+mode" style="height:22px" />
      </div>

      <!-- Buffer with ~ lines and actual content -->
      <pre style="margin:0; line-height:1.45; font-family: 'Fira Code', monospace; font-size:13px; white-space:pre-wrap;">
~   User:      Natnat  (rye0x)
~   Role:      Computer Science Student — Full-Stack Dev
~   Location:  University of the Philippines
~   Status:    Coding & learning nvim plugins
~
~   About:
~     I build web apps (Next.js, Flask/Django), set up infra (Docker, PostgreSQL),
~     and love making clean UIs. This README is styled to feel like a Neovim buffer.
~
~   Quick Commands
~     :projects    — view highlighted repos
~     :stats       — show GitHub stats
~     :connect     — social links
~
~ ---------------------------------------------------------------------------
~  GitHub Stats:
~    (run :stats)
~ ---------------------------------------------------------------------------
      </pre>

      <!-- GitHub stats & languages (images) inside a faux command output -->
      <div style="margin-top:12px; background:#02110f; border-radius:6px; padding:10px; border:1px solid rgba(90,255,160,0.04);">
        <div style="font-family: 'Fira Code', monospace; color:#6ee7b7; font-size:12px; margin-bottom:8px;">:stats --user rye0x</div>
        <div style="display:flex; gap:12px; flex-wrap:wrap; justify-content:center;">
          <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=rye0x&show_icons=true&theme=gruvbox&hide_border=true" style="max-height:140px; border-radius:6px; box-shadow:0 6px 20px rgba(0,0,0,0.6);" />
          <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rye0x&layout=compact&theme=gruvbox&hide_border=true" style="max-height:140px; border-radius:6px; box-shadow:0 6px 20px rgba(0,0,0,0.6);" />
          <img alt="Streak" src="https://streak-stats.demolab.com/?user=rye0x&theme=gruvbox&hide_border=true" style="max-height:140px; border-radius:6px; box-shadow:0 6px 20px rgba(0,0,0,0.6);" />
        </div>
      </div>

      <!-- Tech / plugins line -->
      <div style="margin-top:12px; display:flex; gap:10px; align-items:center; justify-content:space-between; flex-wrap:wrap;">
        <div style="font-family: 'Fira Code', monospace; color:#a7f3d0; font-size:13px;">:plugins — tech stack</div>
        <div style="display:flex; gap:8px; align-items:center;">
          <img src="https://skillicons.dev/icons?i=nextjs,react,ts,python,flask,django,postgresql,docker,git,vim" alt="icons" style="height:28px;"/>
        </div>
      </div>

      <!-- Projects example (faux file list) -->
      <div style="margin-top:14px; font-family:'Fira Code', monospace; font-size:13px; color:#9ae6b4;">
        <div style="margin-bottom:6px;">:projects</div>
        <div style="padding:10px; background:#00120f; border-radius:6px; border:1px solid rgba(120,255,180,0.03);">
          <div>• <strong>LuckyMe CMS</strong> — Next.js + Flask CMS for static site (feature/homepage)</div>
          <div>• <strong>AI SME Loan Recommender</strong> — Django/Flask + ML models (Random Forest, GBoost)</div>
          <div>• <strong>Learning Management System</strong> — Next.js frontend, Django backend, local VM deployment</div>
        </div>
      </div>

      <!-- Connect / social -->
      <div style="margin-top:12px; display:flex; gap:10px; align-items:center; justify-content:center; flex-wrap:wrap;">
        <a href="https://www.facebook.com/mnaquino01" style="text-decoration:none;">
          <img src="https://img.shields.io/badge/-Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
        </a>
        <a href="https://www.linkedin.com/in/nbaquino" style="text-decoration:none;">
          <img src="https://img.shields.io/badge/-LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
        </a>
        <a href="https://github.com/rye0x" style="text-decoration:none;">
          <img src="https://img.shields.io/badge/-GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
        </a>
      </div>

      <!-- bottom statusline (mimic nvim statusline) -->
      <div style="margin-top:14px; border-radius:6px; padding:8px 10px; display:flex; justify-content:space-between; align-items:center; background:linear-gradient(90deg, rgba(0,0,0,0.2), rgba(0,0,0,0.05)); font-family:'Fira Code', monospace; color:#6ee7b7; font-size:12px;">
        <div> NORMAL  —  README.md</div>
        <div>Ln 42, Col 1 — 100%</div>
      </div>

    </div>
  </div>
</div>
