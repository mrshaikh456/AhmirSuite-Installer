<!-- README.md (HTML) -->
<div align="center">
  <h1>AhmirSuite <small style="font-size:16px;display:block;margin-top:-6px;">Employee & Inventory Management System (Installer)</small></h1>
  <p style="margin-top:6px;">Offline-first desktop ERP for SMEs • Built with Electron, React, and SQLite</p>

  <!-- Download buttons -->
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
    ⚠️ Currently only the Windows installer is available. macOS & Linux builds will follow.
  </p>
</div>

<hr/>

<!-- Overview -->
<section>
  <h2>Overview</h2>
  <p>
    <strong>AhmirSuite</strong> is an offline-first desktop application designed for small to medium-sized enterprises (SMEs). 
    It simplifies business operations such as employee management, payroll, inventory tracking, POS billing, insights, and financial reporting. 
    With a modern UI/UX stack, it bridges the gap between lightweight desktop tools and enterprise-grade ERP systems.
  </p>
</section>

<!-- Features -->
<section>
  <h2>✨ Key Features</h2>
  <ul>
    <li>🔐 Role-based access control with authentication &amp; permissions</li>
    <li>👨‍💼 Employee records: attendance, payroll, roles, salary management</li>
    <li>📦 Inventory management: stock, purchase, sales, and returns</li>
    <li>🧾 POS integration with real-time billing &amp; stock updates</li>
    <li>🔄 Returns management with automatic reconciliation</li>
    <li>📊 Analytics &amp; insights dashboards: sales trends, employee performance, stock flow</li>
    <li>📈 Apriori-based pattern mining for intelligent decision support</li>
    <li>💰 Financial dashboard with revenue, expenses, and profit trends</li>
    <li>🗂️ Activity logging: transactions, errors, and audit trails</li>
    <li>💾 Backup &amp; restore (secure recovery options)</li>
    <li>🌐 Multilingual interface support (switchable UI)</li>
    <li>⚡ Offline-first: fully functional without internet dependency</li>
    <li>🌍 Web installer page hosted via Vercel for easy distribution</li>
  </ul>
</section>

<!-- Tech Stack -->
<section>
  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> React 18 + Next.js 14 + Vite 7 + TailwindCSS + Radix UI + shadcn components</li>
    <li><strong>Desktop Framework:</strong> Electron + Node.js</li>
    <li><strong>Database:</strong> SQLite (<code>sqlite3</code> &amp; <code>better-sqlite3</code> for performance)</li>
    <li><strong>Authentication:</strong> bcryptjs (password hashing)</li>
    <li><strong>Scheduling / Background Jobs:</strong> node-cron (e.g., backup reminders, insights refresh)</li>
    <li><strong>Dev Tools:</strong> Visual Studio Code, GitHub, Figma, PostCSS, TypeScript</li>
    <li><strong>Build &amp; Packaging:</strong> electron-builder (NSIS for Windows, AppImage for Linux, dmg for macOS)</li>
    <li><strong>Analytics:</strong> Vercel Analytics (installer page usage)</li>
  </ul>
</section>

<!-- Installation -->
<section>
  <h2>🚀 Installation (Windows)</h2>
  <ol>
    <li>Download the installer from <a href="https://github.com/mrshaikh456/AhmirSuite-Installer/releases/tag/v1.0.0">GitHub Releases</a> or the <a href="https://ahmirsuite-installer.vercel.app/">hosted page</a>.</li>
    <li>Run the <code>.exe</code> file and follow the setup wizard.</li>
    <li>Launch AhmirSuite from the Start Menu or Desktop shortcut.</li>
  </ol>
  <details>
    <summary style="cursor:pointer">Developer / Build Notes</summary>
    <p>
      Installers are packaged with <code>electron-builder</code>. 
      Current release includes NSIS installer for Windows. 
      Linux (AppImage) and macOS (dmg) builds will be added in upcoming releases.
    </p>
  </details>
</section>

<!-- Roadmap -->
<section>
  <h2>🗺️ Roadmap</h2>
  <ul>
    <li>📂 Open-source the full project repository</li>
    <li>💻 Release macOS &amp; Linux installer builds</li>
    <li>📱 Companion mobile app (React Native)</li>
    <li>☁️ Cloud synchronization (multi-device access)</li>
    <li>🌍 Enhanced multilingual &amp; regional market support</li>
    <li>📈 Advanced analytics &amp; AI forecasting</li>
    <li>💳 Integration with payroll, accounting, and payment gateways</li>
    <li>🕑 Backup scheduling improvements (cron-based)</li>
    <li>🔄 Auto-update system for installers</li>
  </ul>
</section>

<!-- License -->
<section>
  <h2>📜 License</h2>
  <p>
    This repository currently distributes the installer under a <strong>proprietary license</strong>. 
    The full source code will be published in future updates under an appropriate open-source license.
  </p>
</section>

<hr/>

<footer style="font-size:12px;color:#6a737d;">
  <p>© 2025 AhmirSuite • Built with ❤️ using Electron, React, and SQLite</p>
</footer>
