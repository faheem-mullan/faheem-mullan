<div align="left">

  <!-- Live Animated Banner Header -->
  <p align="center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f2937&height=200&section=header&text=BACKEND%20ENGINEER&fontSize=45&fontColor=ffffff&fontAlignY=40&animation=fadeIn" width="100%" alt="Header" />
  </p>

  <p align="center">
    <a href="https://git.io/typing-svg">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&pause=1000&color=61AFEF&center=true&vcenter=true&width=600&lines=Building+Production-Grade+APIs;Node.js+%7C+Express.js+%7C+PostgreSQL+%7C+C%23;Focus+on+Security%2C+Data+%26+Global+Error+Handling" alt="Typing SVG" />
    </a>
  </p>

  <br />

  <!-- Icons Grid -->
  <h3>🛠️ STACK & TOOLS</h3>
  <p>
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=js,nodejs,express,postgres,cs,postman,git,github&theme=dark&perline=8" alt="Tech Stack Icons" />
    </a>
  </p>

  <br />

  <!-- Architecture Matrix -->
  <h3>⚡ SYSTEM ARCHITECTURE</h3>

  <table>
    <tr>
      <td width="30%"><b>Backend Core</b></td>
      <td>JavaScript (ES6+), Node.js, Express.js REST APIs, C#</td>
    </tr>
    <tr>
      <td><b>Data & Persistence</b></td>
      <td>PostgreSQL, Connection Pooling (<code>pg.Pool</code>), DBeaver</td>
    </tr>
    <tr>
      <td><b>Security & Auth</b></td>
      <td><code>bcrypt</code> Hashing, Parameterized SQL (Anti-SQLi), JWT, Zod Validation</td>
    </tr>
    <tr>
      <td><b>Resilience & Tooling</b></td>
      <td>Global Error Handling Middleware, Postman (API Testing), Git Version Control</td>
    </tr>
  </table>

  <br />

  <!-- Hard Engineering Patterns -->
  <h3>🛡️ PRODUCTION PATTERNS</h3>
  <ul>
    <li><b>Centralized Error Handling:</b> Express global error-handling middleware intercepting async failures, masking stack traces in production, and standardizing JSON error outputs.</li>
    <li><b>SQL Injection Immunity:</b> Zero string concatenation in database queries; strict parameterized input binding (<code>$1, $2</code>) across all pool operations.</li>
    <li><b>Database Integrity:</b> Schema-level constraints (<code>UNIQUE</code>, <code>CHECK</code>) with explicit PostgreSQL error state handling (e.g., code <code>23505</code>).</li>
    <li><b>Cryptographic Hashing:</b> Asynchronous <code>bcrypt</code> salt generation ensuring zero plain-text password persistence.</li>
    <li><b>Modular Layering:</b> Decoupled system architecture isolating Routing, Business Logic (Controllers), and Data Access layers.</li>
  </ul>

</div>
