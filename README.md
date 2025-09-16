<!-- README.md (HTML) -->
<div align="center">
  <h1>AhmirSuite <small style="font-size:16px;display:block;margin-top:-6px;">Employee & Inventory Management (Installer)</small></h1>
  <p style="margin-top:6px;">Cross-platform desktop system (Windows installer published)</p>

  <!-- Call-to-action buttons -->
  <p>
    <a href="https://github.com/mrshaikh456/AhmirSuite-Installer/releases/tag/v1.0.0" style="text-decoration:none;">
      <button style="background:#2ea44f;border:none;color:white;padding:8px 14px;border-radius:6px;font-weight:600;cursor:pointer">
        ⬇️ Download v1.0.0 (Windows .exe)
      </button>
    </a>
    &nbsp;
    <a href="https://ahmirsuite-installer.vercel.app/" style="text-decoration:none;">
      <button style="background:#0366d6;border:none;color:white;padding:8px 14px;border-radius:6px;font-weight:600;cursor:pointer">
        🌐 Hosted Installer Page (Vercel)
      </button>
    </a>
  </p>

  <p style="font-size:13px;color:#6a737d;margin-top:6px;">
    ⚠️ Currently only the Windows installer is published here. Source code and cross-platform builds will be released later.
  </p>
</div>

<hr/>

<!-- Summary -->
<section>
  <h2>Overview</h2>
  <p>
    <strong>AhmirSuite</strong> is a desktop employee &amp; inventory management application built with <strong>Electron</strong>, <strong>React</strong>, and <strong>SQLite</strong>.
    It aims to simplify daily retail and SME operations such as employee tracking, POS billing, inventory control, reporting, and role-based access management — all while supporting offline-first usage.
  </p>
</section>

<!-- Features -->
<section>
  <h2>Key Features</h2>
  <ul>
    <li>🔐 Role-based user management and secure authentication</li>
    <li>🧾 Point-of-Sale (POS) with real-time inventory updates</li>
    <li>📦 Inventory management (stock-in / stock-out / returns)</li>
    <li>📊 Analytics dashboard and insights engine (including Apriori-based patterns)</li>
    <li>💾 Local backup &amp; restore, activity &amp; error logging</li>
    <li>🌐 Multilingual UI (planned/partial) and installer distribution via a hosted page</li>
  </ul>
</section>

<!-- Tech stack -->
<section>
  <h2>Tech Stack</h2>
  <p>
    Frontend: React + Next.js + Vite • Desktop: Electron • Database: SQLite (sqlite3 / better-sqlite3) • Auth: bcryptjs • Scheduling: node-cron • UI: TailwindCSS + Radix
  </p>
</section>

<!-- Installation -->
<section>
  <h2>Installation (Windows)</h2>
  <ol>
    <li>Download the installer from the <a href="https://github.com/mrshaikh456/AhmirSuite-Installer/releases/tag/v1.0.0">GitHub Release (v1.0.0)</a> or the <a href="https://ahmirsuite-installer.vercel.app/">hosted installer page</a>.</li>
    <li>Run the <code>.exe</code> file and follow the setup wizard.</li>
    <li>Launch AhmirSuite from the Start Menu or Desktop shortcut.</li>
  </ol>

  <details>
    <summary style="cursor:pointer">Developer / build notes</summary>
    <p style="margin:6px 0;">
      The repository uses <code>electron-builder</code> to create installers (NSIS for Windows, AppImage for Linux, dmg for macOS). The packaged installer and unpacked app are included in <code>/dist</code> for the published release.
    </p>
  </details>
</section>

<!-- Release & changelog -->
<section>
  <h2>Releases</h2>
  <p>
    <strong>v1.0.0</strong> — Initial public installer release (Windows). Download at:
    <a href="https://github.com/mrshaikh456/AhmirSuite-Installer/releases/tag/v1.0.0">GitHub Releases</a>.
  </p>
  <p style="font-size:13px;color:#6a737d;">
    For a full changelog and future binaries, please check the <a href="https://github.com/mrshaikh456/AhmirSuite-Installer/releases">Releases page</a>.
  </p>
</section>

<!-- Roadmap -->
<section>
  <h2>Roadmap</h2>
  <ul>
    <li>Open-source the full project repository and publish source code</li>
    <li>Publish installer builds for macOS and Linux</li>
    <li>Enable cloud synchronization and multi-device support</li>
    <li>Companion mobile application (React Native)</li>
    <li>Extended analytics &amp; forecasting features</li>
  </ul>
</section>

<!-- License & contact -->
<section>
  <h2>License &amp; Contact</h2>
  <p>
    <strong>License:</strong> This repository currently distributes the installer under a proprietary license. The source code will be released under an appropriate open-source license in a future update.
  </p>
  <p>
    <strong>Contact:</strong> Abdullah Shaikh — <em>See GitHub profile</em>
  </p>
</section>

<hr/>

<footer style="font-size:12px;color:#6a737d;">
  <p>Built with ❤️ • Electron • React • SQLite</p>
</footer>
