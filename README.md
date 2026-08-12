<!--
  Profile README for Ronel Geronimo
  Improved layout using HTML tags and lightweight badges for GitHub profile README
  Repository snapshot last refreshed: 2026-08-12
-->
<div align="center">
  <!-- Header / Title -->
  <h1>👋 Hello — I'm <strong>Ronel Geronimo</strong></h1>
  <p><em>Automation Test Engineer — web, mobile, API & performance automation</em></p>
  <!-- Optional avatar (uncomment and replace the src with your image URL) -->
  <!-- <img src="https://avatars.githubusercontent.com/RonelBG1213" alt="Ronel Geronimo" width="120" style="border-radius:50%;"> -->
  <!-- Quick badges -->
  <p>
    <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
    <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
    <img alt="Appium" src="https://img.shields.io/badge/Appium-662D91?style=flat-square&logo=appium&logoColor=white" />
    <img alt="k6" src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" />
  </p>
</div>
<hr />
<!-- Cover Section -->
<h2>🎯 About me</h2>
<p>
  I build and maintain test automation across web, mobile, and APIs, working mostly in the
  TypeScript/JavaScript and Python ecosystems. Lately I've been moving past writing suites and into
  building the tooling around them — locator helpers, reporting integrations, and performance harnesses.
</p>
<!-- Cover details laid out with HTML -->
<div>
  <h3>📚 Current focus</h3>
  <ul>
    <li>Building developer tooling for Playwright — locator generation and run reporting</li>
    <li>Leveraging AI to accelerate test automation, enhancing development speed and maintaining high quality</li>
    <li>Wiring test results into team workflows (Microsoft Teams / Power Automate)</li>
    <li>Performance testing with Grafana k6 and JMeter</li>
    <li>Cross-language coverage: Playwright (TS / Python), Selenium (Java), Appium (JS / Python)</li>
    <li>Prototyping game mechanics in Python with pygame-ce — a side track for practising systems design</li>
  </ul>
</div>
<!-- Repository information -->
<h2>📂 Repository snapshot</h2>
<p>
  A mix of tooling, framework templates, and learning experiments. Highlights first:
</p>
<h3>🔭 Recent work</h3>
<table>
  <tr>
    <td><a href="https://chromewebstore.google.com/detail/locator-lens/kmcaboccnefnjbmgcaebmeglglcopfkk"><strong>locator-lens</strong></a></td>
    <td>
      Chrome extension that turns a clicked page element into a Playwright locator — with scoring,
      explanations, and verification. Bundles Playwright's own selector engine so suggestions match
      what a real test resolves. <em>TypeScript, Preact, esbuild.</em>
    </td>
  </tr>
  <tr>
    <td><a href="https://github.com/RonelBG1213/trace_viewer_extension"><strong>trace_viewer_extension</strong></a></td>
    <td>
      Chrome extension (Manifest V3) for opening a Playwright <code>trace.zip</code> without touching the
      terminal — drop the file or paste its path and the trace renders in the official Playwright Trace
      Viewer, framed from <code>trace.playwright.dev</code> and driven over origin-checked
      <code>postMessage</code>. <em>TypeScript, Vite.</em>
    </td>
  </tr>
  <tr>
    <td><a href="https://github.com/RonelBG1213/playwright-power-automate-reporter"><strong>playwright-power-automate-reporter</strong></a></td>
    <td>
      Posts a Playwright run summary to a Microsoft Teams chat or channel as an Adaptive Card, via a
      Power Automate HTTP trigger. Reporter plugin, CLI, and programmatic API — zero runtime
      dependencies. <em>Node.js / JavaScript.</em>
    </td>
  </tr>
  <tr>
    <td><a href="https://github.com/RonelBG1213/selenium_pom"><strong>selenium_pom</strong></a></td>
    <td>Selenium Page Object Model structure. <em>Java.</em></td>
  </tr>
</table>
<h3>🧪 By area</h3>
<ul>
  <li>
    <strong>Web automation</strong> —
    <a href="https://github.com/RonelBG1213/DemoTSFramework">DemoTSFramework</a>,
    <a href="https://github.com/RonelBG1213/typescript_demo">typescript_demo</a>,
    <a href="https://github.com/RonelBG1213/selenium_pom">selenium_pom</a>,
    <a href="https://github.com/RonelBG1213/li_bot">li_bot</a>
  </li>
  <li>
    <strong>Mobile automation (Appium)</strong> —
    <a href="https://github.com/RonelBG1213/webdriverio_appium">webdriverio_appium</a>,
    <a href="https://github.com/RonelBG1213/appium_python_demo">appium_python_demo</a>,
    <a href="https://github.com/RonelBG1213/appium_python">appium_python</a>
  </li>
  <li>
    <strong>API testing</strong> —
    <a href="https://github.com/RonelBG1213/supertestframework">supertestframework</a>,
    <a href="https://github.com/RonelBG1213/python_request">python_request</a>
  </li>
  <li>
    <strong>Performance testing</strong> —
    <a href="https://github.com/RonelBG1213/grafanak6_trials">grafanak6_trials</a>,
    <a href="https://github.com/RonelBG1213/jmeter_test_trials">jmeter_test_trials</a>
  </li>
  <li>
    <strong>Tooling &amp; extensions</strong> —
    <a href="https://chromewebstore.google.com/detail/locator-lens/kmcaboccnefnjbmgcaebmeglglcopfkk">locator-lens</a>,
    <a href="https://github.com/RonelBG1213/trace_viewer_extension">trace_viewer_extension</a>,
    <a href="https://github.com/RonelBG1213/playwright-power-automate-reporter">playwright-power-automate-reporter</a>
  </li>
  <li>
    <strong>Game prototypes (Python / pygame-ce)</strong> —
    <a href="https://github.com/RonelBG1213/hack_and_slash_base">hack_and_slash_base</a> (top-down twin-stick
    arena brawler),
    <a href="https://github.com/RonelBG1213/dungeon_maker_base">dungeon_maker_base</a> (turn-based pixel RPG
    with a built-in dungeon editor)
  </li>
  <li>
    <strong>Notes &amp; learning</strong> —
    <a href="https://github.com/RonelBG1213/python_guide">python_guide</a>,
    <a href="https://github.com/RonelBG1213/tsjsguide">tsjsguide</a>
  </li>
</ul>
<!-- Invitation to help -->
<details>
  <summary>💡 Want to help improve these repositories?</summary>
  <p>
    Please feel free to suggest improvements, open issues, or submit PRs — I welcome constructive feedback.
    If you spot anything that can be improved (tests, docs, structure), thank you for contributing!
  </p>
</details>
<!-- Contact / LinkedIn -->
<h2>📫 Connect with me</h2>
<p>
  <a href="https://www.linkedin.com/in/ronel-geronimo-72622b166" target="_blank" rel="noopener noreferrer">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:ronelbautistageronimo@gmail.com" target="_blank" rel="noopener noreferrer">
    <img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.upwork.com/freelancers/~01ea5a8e664cd0d2a0" target="_blank" rel="noopener noreferrer">
    <img alt="Upwork" src="https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white" />
  </a>
  <a href="https://www.patreon.com/cw/Ronel924" target="_blank" rel="noopener noreferrer">
    <img alt="Patreon" src="https://img.shields.io/badge/Patreon-FF424D?style=for-the-badge&logo=patreon&logoColor=white" />
  </a>
</p>
<!-- Small helpful tips for README visitors -->
<hr />
<h3>🔧 Quick tips</h3>
<ul>
  <li>If you're exploring my repos, start with any README in the project root — I try to keep examples runnable.</li>
  <li>Tests and automation scripts often include a requirements.txt or package.json with setup instructions.</li>
  <li>Some of the smaller trial repos are scratch experiments rather than polished projects — the ones under <em>Recent work</em> are the maintained ones.</li>
  <li>Open an issue if something breaks or isn't clear — I appreciate the signal to improve things.</li>
</ul>
<p align="center">Made with ❤️ — Happy testing and learning!</p>
