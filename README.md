<style>
  .main {
    display: flex;
    flex-direction: column;
    gap: 40px;
  }
  .header {
    display: grid;
    grid-template-columns: 150px 1fr 1fr;
    gap: 24px;
    align-items: center;
  }

  .avatar {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    object-position: center 30%;
  }

  .name-column,
  .info-column {
    display: flex;
    flex-direction: column;
    gap: 8px;
  }

  .info-column {
    text-align: right
  }

  .name {
    font-size: 32px;
    font-weight: bold;
  }

  .subtitle {
    font-size: 24px;
    color: #666;
  }

  .bold {
    font-weight: 800
  }

  .skills {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 30px;
    align-items: start;
}

.skills h2 {
    margin-top: 0;
}

.skills-table {
    width: 100%;
    border-collapse: collapse;
}

.skills-table th,
.skills-table td {
    padding: 8px;
    text-align: left;
    vertical-align: top;
}

.skills-table th:first-child,
.skills-table td:first-child {
    width: 35%;
}

@media (max-width: 700px) {
    .skills {
        grid-template-columns: 1fr;
    }
}
</style>
<div class="main">
  <div class="header">
    <div>
      <img
        src="./images/avatar.JPG"
        class="avatar"
        alt="Portrait Wout Van Wijmeersch"
      >
    </div>
    <div class="name-column">
      <span class="name">Wout Van Wijmeersch</span>
      <span class="subtitle">Full Stack Developer</span>
    </div>
    <div class="info-column">
      <span><a href="https://www.woutvanwijmeersch.be" target=blank>woutvanwijmeersch.be</a></span>
      <span><a href="mailto:contact@woutvanwijmeersch.be" target=blank>contact@woutvanwijmeersch.be</a></span>
    </div>
  </div>
</div>

## About

Applied Computer Science graduate with experience developing software applications using technologies such as Angular, Laravel and Java. Passionate about building modern, user-friendly, and reliable software solutions. Eager to explore new technologies and continuously develop technical skills through hands-on projects, practical learning and problem-solving.

<div class="skills">
  <div>
    <h2>Soft Skills</h2>
    <ul>
      <li>Problem-solving</li>
      <li>Motivated</li>
      <li>Eager to learn</li>
      <li>Flexibility</li>
    </ul>
  </div>
  <div>
    <h2>Hard Skills</h2>
    <table class="skills-table">
      <thead>
        <tr>
          <th>Category</th>
          <th>Technology</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>Languages</strong></td>
          <td>JavaScript, Java, Python, C#, PHP, Kotlin</td>
        </tr>
        <tr>
          <td><strong>Frameworks &amp; Platforms</strong></td>
          <td>React, Angular, Node.js, Spring Boot, Blazor, .NET, Laravel</td>
        </tr>
        <tr>
          <td><strong>Databases</strong></td>
          <td>MySQL, MongoDB, Redis, Neo4j, PostgreSQL</td>
        </tr>
        <tr>
          <td><strong>Other</strong></td>
          <td>Docker, Git, Windows, Ubuntu, Raspbian, VirtualBox</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

## Projects

- **Portfolio** (React, NodeJS, MySQL)

- **360° Zorg Item Lending** (Kotlin, .NET, Blazor, PostgreSQL)

- **Social Media App** (React, NodeJS, MySQL)

- **IT Conference Management App** (Java, Spring Boot, MySQL)

- **Splendor Card Game** (Java, JavaFX, MySQL)

- **Delaware B2B Platform** (Java, JavaFX, React, NodeJS, MySQL)

## Github statistics

<img src="https://komarev.com/ghpvc/?username=wout-vanwijmeersch"></img>

[![Wout Van Wijmeersch](https://github-stats-extended.vercel.app/api/?username=wout-vanwijmeersch&show_icons=true&theme=calm&rank_icon=github&include_all_commits=true&custom_title=Wout+Van+Wijmeersch&disable_animations=true&number_format=long&show=prs_merged_percentage,prs_reviewed)](https://github-stats-extended.vercel.app/api/?username=wout-vanwijmeersch&show_icons=true&theme=calm&rank_icon=github&include_all_commits=true&custom_title=Wout+Van+Wijmeersch&disable_animations=true&number_format=long&show=prs_merged_percentage,prs_reviewed)
