# OSINT-Bookmark-Manager
A portable, offline OSINT bookmark hub in a single HTML file. Import browser bookmarks, search everything instantly, customize themes, and save your full OSINT toolkit to a USB drive or VM—no installs, no tracking, pure operational efficiency.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>OSINT Bookmark Manager – Project Overview</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; line-height: 1.6; color: #111827; max-width: 900px; margin: 0 auto; padding: 24px; background-color: #ffffff;">

  <h1>🔖 OSINT Bookmark Manager – Version 1.0</h1>
  <h2>A Portable, Offline, Fully Modular Bookmark Intelligence Tool</h2>
  <p><strong>For OSINT Investigators, Analysts &amp; Cybersecurity Teams</strong></p>

  <p>
    The <strong>OSINT Bookmark Manager</strong> is a standalone, self-contained HTML application that turns your browser
    into a powerful bookmark intelligence assistant. It imports Chrome/Firefox bookmark exports, rebuilds folder
    structures, supports full searching, editing, theming, and persistent saving — all inside a single file.
  </p>
  <p>
    No installs. No server. No tracking. Just <strong>pure, portable OSINT workflow enhancement</strong>.
  </p>

  <hr>

  <h2>⭐ Why This Tool Matters for OSINT Work</h2>
  <p>
    OSINT investigations rely heavily on dozens — sometimes hundreds — of tools, dashboards, intel sources,
    search engines, dark-web portals, social platforms, breach databases, map tools, and identity pivots.
  </p>
  <p>
    Most investigators bookmark these resources everywhere:
  </p>
  <ul>
    <li>Multiple browsers and profiles</li>
    <li>VM environments and disposable sessions</li>
    <li>Work and personal machines</li>
    <li>USB drives and cloud accounts</li>
    <li>Random “OSINT framework” lists scattered around</li>
  </ul>
  <p>
    This creates <strong>fragmentation</strong>, <strong>inconsistency</strong>, and major <strong>OPSEC hazards</strong>.
  </p>

  <p>
    The OSINT Bookmark Manager solves this by providing a <strong>portable, persistent, offline-first bookmark ecosystem</strong>
    that goes anywhere you go.
  </p>

  <p>It is perfect for:</p>
  <ul>
    <li>Air-gapped investigations</li>
    <li>Disposable VM usage</li>
    <li>Field work and travel ops</li>
    <li>Dark-web OSINT sessions</li>
    <li>Research and training environments</li>
    <li>Corporate intelligence and threat intel teams</li>
  </ul>

  <p>
    Because it runs inside a single HTML file, you can store it on:
  </p>
  <ul>
    <li>USB drives</li>
    <li>Encrypted containers (e.g., VeraCrypt, LUKS)</li>
    <li>Qubes OS vault VMs</li>
    <li>Proxmox/QEMU VM images</li>
    <li>Offline laptops or secure servers</li>
    <li>Cloud drives (if that fits your model)</li>
  </ul>

  <p>
    Your entire OSINT bookmark collection becomes <strong>truly portable</strong>.
  </p>

  <hr>

  <h2>🚀 Core Features (Why You’ll Love This Tool)</h2>

  <h3>1. 100% Self-Contained HTML Application</h3>
  <p>
    The Bookmark Manager is just one HTML file using vanilla HTML, CSS, and JavaScript. No frameworks,
    no external CDNs, and no dependencies.
  </p>
  <p>This means:</p>
  <ul>
    <li>Works fully offline</li>
    <li>Portable between machines and environments</li>
    <li>Safe for hardened and OPSEC-sensitive setups</li>
    <li>Easy to keep under version control or inside case folders</li>
  </ul>

  <h3>2. Full Chrome/Firefox Bookmark Import (HTML)</h3>
  <p>
    The tool imports standard Netscape-format bookmark export files from browsers like Chrome and Firefox.
  </p>
  <p>It will:</p>
  <ul>
    <li>Reconstruct the entire folder hierarchy</li>
    <li>Parse and preserve bookmark titles and URLs</li>
    <li>Handle nested folders cleanly</li>
    <li>Display everything in an interactive, collapsible tree</li>
  </ul>
  <p>
    This is perfect for investigators who maintain multiple browser profiles or move between browser environments.
  </p>

  <h3>3. Persistent Saving Built In</h3>
  <p>
    When you click <strong>Save File (Persistent)</strong>, the application embeds your current bookmark tree directly
    into the HTML file itself.
  </p>
  <p>This gives you:</p>
  <ul>
    <li>A personalized OSINT bookmark file that travels with you</li>
    <li>Curated, cleaned, and structured OSINT resources baked into the tool</li>
    <li>A single artifact that can be archived, encrypted, or versioned</li>
  </ul>

  <h3>4. Powerful Search (Title, URL, Folder Path)</h3>
  <p>
    The search function supports quick filtering across:
  </p>
  <ul>
    <li>Bookmark titles</li>
    <li>URLs</li>
    <li>Folder paths (e.g., <em>OSINT / Social / Usernames</em>)</li>
  </ul>
  <p>
    This is extremely useful for OSINT workflows where you might have hundreds of bookmarks for:
  </p>
  <ul>
    <li>Reverse image tools</li>
    <li>People search engines</li>
    <li>Breach databases</li>
    <li>Dark-web gateways</li>
    <li>Passive DNS tools</li>
    <li>Corporate registries and open data sources</li>
    <li>Mapping and geolocation services</li>
  </ul>

  <h3>5. Add, Remove, and Organize Bookmarks</h3>
  <p>
    Beyond importing, you can actively manage your OSINT workspace:
  </p>
  <ul>
    <li>Add new bookmarks (e.g., new tools, dashboards, or pivots)</li>
    <li>Remove dead links or low-value resources</li>
    <li>Refine folder structures to match your investigative methodology</li>
    <li>Export the entire collection as JSON for backup or integration</li>
  </ul>
  <p>
    The Bookmark Manager becomes your <strong>living OSINT toolbox</strong>.
  </p>

  <h3>6. Multiple Professional, Hacker-Themed Color Schemes</h3>
  <p>
    The app ships with multiple themes, including:
  </p>
  <ul>
    <li>Dark Cyan (Default)</li>
    <li>Neon Purple</li>
    <li>Emerald Green</li>
    <li>Solarized</li>
    <li>Light Mode</li>
    <li>Matrix Green</li>
    <li>Red &amp; Black Hacker</li>
    <li>Midnight Blue</li>
  </ul>
  <p>
    Themes can be switched instantly and are stored locally, making it comfortable for long research sessions,
    presentations, or training environments.
  </p>

  <h3>7. USB &amp; Offline Friendly</h3>
  <p>
    Because everything runs client-side with no network calls, the Bookmark Manager is ideal for:
  </p>
  <ul>
    <li>Secure USB deployment</li>
    <li>Air-gapped labs</li>
    <li>Covert or sensitive investigations</li>
    <li>Training kits and workshops</li>
    <li>Locked-down corporate machines with no install rights</li>
  </ul>
  <p>
    You can literally keep your OSINT toolbox on a keychain.
  </p>

  <h3>8. Regex-Based Bookmark Parser</h3>
  <p>
    Instead of relying on brittle DOM parsing, this tool uses a regex-based parser tailored for Netscape bookmark
    format exports. This improves:
  </p>
  <ul>
    <li>Robustness across different browsers and export quirks</li>
    <li>Reliability when dealing with nested folders</li>
    <li>Handling of various encodings and embedded markup</li>
  </ul>

  <hr>

  <h2>🧭 Why OSINT Investigators Need a Tool Like This</h2>

  <h3>Centralization of OSINT Resources</h3>
  <p>
    Instead of relying on memory or scattered bookmarks, investigators get a <strong>central hub</strong> for:
  </p>
  <ul>
    <li>Search engines and meta-search tools</li>
    <li>Username and email OSINT tools</li>
    <li>Dark-web gateways and monitors</li>
    <li>Breach and credential leak databases</li>
    <li>Corporate registration and open data portals</li>
    <li>Social graph, geolocation, and metadata tools</li>
    <li>Reporting frameworks and reference material</li>
  </ul>

  <h3>Cross-Environment Consistency</h3>
  <p>
    Many investigators work across:
  </p>
  <ul>
    <li>Kali, Parrot, or other Linux distros</li>
    <li>Windows and macOS hosts</li>
    <li>Qubes OS or VM-based setups</li>
    <li>Tails or privacy-focused live environments</li>
    <li>Cloud sandboxes and remote labs</li>
  </ul>
  <p>
    Your bookmarks usually do not follow you. This tool fixes that by making your OSINT resources
    <strong>environment-agnostic</strong>.
  </p>

  <h3>Reduced OPSEC Footprint</h3>
  <p>
    Because your bookmarks are stored in a single HTML artifact (and optionally in localStorage),
    you avoid:
  </p>
  <ul>
    <li>Cloud-synced bookmark contamination</li>
    <li>Personal/work profile leakage</li>
    <li>Persistent traces on shared machines</li>
  </ul>
  <p>
    It aligns well with high-OPSEC workflows.
  </p>

  <h3>Training &amp; Collaboration Ready</h3>
  <p>
    You can distribute a pre-loaded bookmark manager to:
  </p>
  <ul>
    <li>Students in OSINT courses</li>
    <li>Incident response and threat intel teams</li>
    <li>Investigative journalists and researchers</li>
    <li>Red and blue teams in exercises</li>
  </ul>
  <p>
    Everyone starts from the same curated OSINT toolkit, improving consistency and speed.
  </p>

  <hr>

  <h2>📦 Technical Highlights</h2>
  <ul>
    <li>Standalone HTML + CSS + vanilla JavaScript</li>
    <li>No backend, no tracking, no analytics</li>
    <li>Runs offline once opened in a browser</li>
    <li>Uses <code>localStorage</code> for fast reloads</li>
    <li>Embeds bookmark data in a JSON script block for persistence</li>
    <li>Supports JSON export of the entire bookmark tree</li>
    <li>Mobile-responsive layout for smaller screens</li>
  </ul>

  <hr>

  <h2>📄 Licensing</h2>
  <p>
    This project is released under a <strong>Creative Commons Attribution-NonCommercial 4.0 International
    (CC BY-NC 4.0)</strong> license.
  </p>
  <p>
    You may use, modify, and share it for <strong>non-commercial</strong> purposes with appropriate attribution.
    Commercial use, resale, or monetization are not permitted under this license.
  </p>

  <hr>

  <h2>🎯 Final Pitch</h2>
  <p>
    If you want a <strong>portable, flexible, offline-ready OSINT toolkit</strong> that goes wherever you go,
    the OSINT Bookmark Manager is the perfect companion.
  </p>
  <p>
    It gives investigators a clean, fast, structured way to store, search, and transport large OSINT bookmark
    collections without relying on browser sync, cloud accounts, or installed extensions.
  </p>
  <p>
    This tool is:
  </p>
  <ul>
    <li>Your OSINT toolbox</li>
    <li>Your workflow accelerator</li>
    <li>Your portable intel library</li>
    <li>Your operational companion</li>
  </ul>

  <p><strong>Clone it, open the HTML file, import your bookmarks, and start investigating.</strong></p>

</body>
</html>
