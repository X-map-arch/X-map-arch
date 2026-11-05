<!-- Custom Split Animated Banner (Black/Yellow & White with Lightning) -->
<div align="center">
  <svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg" style="border-radius: 8px; border: 1px solid #30363d; margin-bottom: 20px;">
    
    <!-- Background Split: Left Black, Right White -->
    <rect x="0" y="0" width="400" height="200" fill="#0d1117" />
    <rect x="400" y="0" width="400" height="200" fill="#ffffff" />
    
    <!-- Yellow Diagonal Slash (Split effect) -->
    <polygon points="380,0 400,0 420,200 400,200" fill="#FFD700" />
    
    <!-- Text: Left Side (Yellow text on Black) -->
    <text x="380" y="115" font-family="'Fira Code', monospace" font-size="50" font-weight="bold" fill="#FFD700" text-anchor="end" letter-spacing="2">X-map-</text>
    
    <!-- Text: Right Side (Black text on White) -->
    <text x="430" y="115" font-family="'Fira Code', monospace" font-size="50" font-weight="bold" fill="#000000" text-anchor="start" letter-spacing="2">arch</text>

    <!-- Subtitle -->
    <text x="400" y="150" font-family="'Segoe UI', sans-serif" font-size="16" fill="#8b949e" text-anchor="middle" letter-spacing="3">PHANTOM IN THE SYSTEM</text>

    <!-- Animated Lightning Strike (Passing through text) -->
    <g>
      <!-- The Lightning Bolt Shape -->
      <polygon points="400,0 370,70 420,80 350,200" fill="#FFD700" opacity="0">
        <!-- Animation: Waits, then flashes and moves across -->
        <animate attributeName="opacity" values="0;0;1;0;0" keyTimes="0;0.7;0.75;0.8;1" dur="4s" repeatCount="indefinite" />
        <animateTransform attributeName="transform" type="translate" values="-400,0; 400,0" dur="4s" repeatCount="indefinite" />
      </polygon>
      
      <!-- Flash Effect (Makes the whole banner glow briefly) -->
      <rect x="0" y="0" width="800" height="200" fill="#FFD700" opacity="0" style="mix-blend-mode: overlay;">
        <animate attributeName="opacity" values="0;0;0.4;0;0" keyTimes="0;0.7;0.75;0.8;1" dur="4s" repeatCount="indefinite" />
      </rect>
    </g>
  </svg>
</div>

<!-- Profile Info & Badges (No Logo) -->
<div align="center">
  <p style="font-family: 'Segoe UI', sans-serif; font-size: 16px; color: #c9d1d9; letter-spacing: 1px;">
    <b>Cybersecurity</b> | <b>Penetration Testing</b> | <b>Systems</b>
  </p>
  
  <!-- Real-time Views & Followers -->
  <img src="https://komarev.com/ghpvc/?username=X-map-arch&color=FFD700&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views">
  &nbsp;
  <img src="https://img.shields.io/badge/FOLLOWERS-2-FFD700?style=for-the-badge&labelColor=161b22" alt="Followers">
</div>

<br>
<hr style="border: 1px solid #30363d;">

<!-- About Section -->
<h2 style="font-family: 'Segoe UI', sans-serif; font-weight: 600; color: #ffffff;">About</h2>
<p style="font-family: 'Segoe UI', sans-serif; font-size: 15px; color: #c9d1d9; line-height: 1.6;">
  I build practical, robust security tools: automated wireless penetration frameworks and secure web applications. My focus is on clean interfaces and building open-source projects that people can use without friction.
</p>
<ul style="font-family: 'Segoe UI', sans-serif; font-size: 15px; color: #c9d1d9; line-height: 1.8;">
  <li>Developing <b>X-MAP-Auto-Phantom</b> for wireless security testing (2.4GHz & 5GHz)</li>
  <li>Working across Python, Shell Scripting, PHP, and C</li>
  <li>Exploring Linux internals and low-level system security</li>
  <li>Continuously learning and iterating</li>
</ul>

<hr style="border: 1px solid #30363d;">

<!-- Technologies & Tools -->
<h2 style="font-family: 'Segoe UI', sans-serif; font-weight: 600; color: #ffffff;">Technologies & Tools</h2>
<div align="center">
  <img src="https://skillicons.dev/icons?i=linux,bash,python,php,html,c,vscode,git,github&theme=dark" alt="Tech Stack" style="margin-bottom: 15px;" />
  <br>
  <img src="https://img.shields.io/badge/Wireshark-0d1117?style=for-the-badge&logo=wireshark&logoColor=FFD700&borderColor=30363d" alt="Wireshark">
  <img src="https://img.shields.io/badge/Nmap-0d1117?style=for-the-badge&logo=nmap&logoColor=FFD700&borderColor=30363d" alt="Nmap">
  <img src="https://img.shields.io/badge/Metasploit-0d1117?style=for-the-badge&logo=metasploit&logoColor=FFD700&borderColor=30363d" alt="Metasploit">
  <img src="https://img.shields.io/badge/Burp_Suite-0d1117?style=for-the-badge&logo=burpsuite&logoColor=FFD700&borderColor=30363d" alt="Burp Suite">
  <img src="https://img.shields.io/badge/Aircrack--ng-0d1117?style=for-the-badge&logo=wifi&logoColor=FFD700&borderColor=30363d" alt="Aircrack-ng">
  <img src="https://img.shields.io/badge/Kali_Linux-0d1117?style=for-the-badge&logo=kali-linux&logoColor=FFD700&borderColor=30363d" alt="Kali">
</div>

<hr style="border: 1px solid #30363d;">

<!-- Featured Projects -->
<h2 style="font-family: 'Segoe UI', sans-serif; font-weight: 600; color: #ffffff;">Featured Projects</h2>
<table style="width: 100%; border-collapse: collapse; font-family: 'Segoe UI', sans-serif; font-size: 14px; color: #c9d1d9;">
  <thead>
    <tr style="border-bottom: 1px solid #30363d; text-align: left;">
      <th style="padding: 10px 5px; color: #ffffff;">Project</th>
      <th style="padding: 10px 5px; color: #ffffff;">Description</th>
      <th style="padding: 10px 5px; color: #ffffff;">Stack</th>
    </tr>
  </thead>
  <tbody>
    <tr style="border-bottom: 1px solid #21262d;">
      <td style="padding: 10px 5px;"><a href="https://github.com/X-map-arch/X-MAP-Auto-Phantom" style="color: #58a6ff; text-decoration: none;">X-MAP-Auto-Phantom</a></td>
      <td style="padding: 10px 5px;">Automated Evil Twin attack framework for wireless pentesting.</td>
      <td style="padding: 10px 5px;"><span style="color: #FFD700;">Shell</span></td>
    </tr>
    <tr style="border-bottom: 1px solid #21262d;">
      <td style="padding: 10px 5px;"><a href="https://github.com/X-map-arch/MEDILINK" style="color: #58a6ff; text-decoration: none;">MEDILINK</a></td>
      <td style="padding: 10px 5px;">Secure platform connecting patients and medical services.</td>
      <td style="padding: 10px 5px;"><span style="color: #FFD700;">PHP</span></td>
    </tr>
    <tr style="border-bottom: 1px solid #21262d;">
      <td style="padding: 10px 5px;"><a href="https://github.com/X-map-arch/PORTFOLIO" style="color: #58a6ff; text-decoration: none;">PORTFOLIO</a></td>
      <td style="padding: 10px 5px;">Personal aesthetic portfolio showcasing technical skills.</td>
      <td style="padding: 10px 5px;"><span style="color: #FFD700;">HTML</span></td>
    </tr>
    <tr style="border-bottom: 1px solid #21262d;">
      <td style="padding: 10px 5px;"><a href="https://github.com/X-map-arch/SFRA_01" style="color: #58a6ff; text-decoration: none;">SFRA_01</a></td>
      <td style="padding: 10px 5px;">Python-based security tool/script for network analysis.</td>
      <td style="padding: 10px 5px;"><span style="color: #FFD700;">Python</span></td>
    </tr>
    <tr style="border-bottom: 1px solid #21262d;">
      <td style="padding: 10px 5px;"><a href="https://github.com/X-map-arch/my-portfolio" style="color: #58a6ff; text-decoration: none;">my-portfolio</a></td>
      <td style="padding: 10px 5px;">A web-based personal portfolio project.</td>
      <td style="padding: 10px 5px;"><span style="color: #FFD700;">HTML</span></td>
    </tr>
    <tr style="border-bottom: 1px solid #21262d;">
      <td style="padding: 10px 5px;"><a href="https://github.com/X-map-arch/mahi-project-" style="color: #58a6ff; text-decoration: none;">mahi-project-</a></td>
      <td style="padding: 10px 5px;">Web development project built with PHP backend.</td>
      <td style="padding: 10px 5px;"><span style="color: #FFD700;">PHP</span></td>
    </tr>
  </tbody>
</table>

<hr style="border: 1px solid #30363d;">

<!-- GitHub Stats -->
<h2 style="font-family: 'Segoe UI', sans-serif; font-weight: 600; color: #ffffff;">GitHub Activity</h2>
<div align="center" style="margin-top: 15px;">
  <img src="https://github-readme-stats.vercel.app/api?username=X-map-arch&show_icons=true&theme=dark&bg_color=0D1117&title_color=FFD700&text_color=8b949e&icon_color=FFD700&border_color=30363d&hide_border=false&border_radius=8" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=X-map-arch&theme=dark&background=0D1117&ring=FFD700&fire=FFD700&currStreakNum=FFFFFF&sideNums=c9d1d9&currStreakLabel=FFD700&sideLabels=8b949e&dates=8b949e&border=30363d&border_radius=8" alt="GitHub Streak" width="48%" />
</div>

<hr style="border: 1px solid #30363d;">

<!-- Footer -->
<div align="center">
  <p style="font-family: 'Segoe UI', sans-serif; font-size: 13px; color: #8b949e; font-style: italic;">
    "Phantom in the System. Securing the Wireless Waves."
  </p>
</div>
