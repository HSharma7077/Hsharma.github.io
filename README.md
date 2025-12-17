<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Harshit Sharma – PhD Candidate at ESCP</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Personal academic webpage of Harshit Sharma, PhD candidate at ESCP Business School." />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <div class="intro">
        <!-- Replace profile.jpg with your own image file name or remove the <img> if you don't have one yet -->
        <img src="profile.jpg" alt="Photo of Your Name" class="avatar" />
        <div>
          <h1>Harshit Sharma</h1>
          <h2>PhD Candidate · ESCP Business School</h2>
          <p class="tagline">
            I am a PhD candidate in Economics at ESCP Business School in Berlin, supervised by Prof. Gonçalo Pina under the Chair of International Economics. My research interests lie at the intersection of behavioral and experimental economics, public policy, and electricity markets. I am particularly interested in how individuals and firms respond to incentives in complex, real-world environments, and I plan to conduct field experiments to study these questions in applied policy and energy-market settings.

My current research agenda includes two working papers and two additional projects, including one based on NFL performance data and another on housing markets and noise pollution. These build on my experience as a research assistant working on behavioral economics, housing economics, and historical finance at ESCP Berlin, as well as prior research roles at the University of Cologne and the Max Planck Institute on topics such as employee behavior, gender wage gaps, aging workforces, AI and the future of work, and team decision-making under cognitive biases. I hold an M.Sc. in Economics (Research Track) from the University of Cologne and a B.Sc. in Economics (Honours) from Doon University, alongside experience in development policy and survey work through positions at the German Institute of Development and Sustainability and the Annual Status of Education Report (ASER) initiative.
          </p>
          <div class="social-links">
            <a href="hsharma@escp.eu">Email</a>
            <a href="https://www.linkedin.com/in/harshitsharma13" target="_blank" rel="noopener">LinkedIn</a>
            <a href="https://github.com/HSharma7077" target="_blank" rel="noopener">GitHub</a>
          </div>
        </div>
      </div>

      <nav class="main-nav">
        <a href="#about" class="active">Home</a>
        <a href="#research">Research</a>
        <a href="#teaching">Teaching</a>
        <a href="#cv">CV</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>
<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

  <main class="container main-content">
    <!-- About / Home -->
   
## Step 2: Configure your site

    <!-- Research -->
    <section id="research" class="card">
      <h3>Research</h3>
_You turned on GitHub Pages! :tada:_

      <h4>Working Papers</h4>
      <ul class="item-list">
        <li>
          <strong>Title of Working Paper 1</strong><br />
          <span class="muted">with Coauthor A, Coauthor B</span><br />
          <span class="muted">Working paper, [Year].</span><br />
          <span>
            One–two sentence abstract of this paper. What is the question,
            method, and main result?
          </span>
        </li>
        <li>
          <strong>Title of Working Paper 2</strong><br />
          <span class="muted">Solo author</span><br />
          <span class="muted">Job market paper (if applicable).</span><br />
          <span>
            Brief description of your contribution and findings.
          </span>
        </li>
      </ul>
We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

      <h4>Publications</h4>
      <ul class="item-list">
        <li>
          <strong>Article Title</strong><br />
          <span class="muted">Journal Name, Volume(Issue), Year.</span><br />
          <span class="muted">with Coauthor A, Coauthor B</span>
        </li>
        <li>
          <strong>Another Article Title</strong><br />
          <span class="muted">Conference / Working paper series, Year.</span>
        </li>
      </ul>
    </section>
Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

    <!-- Teaching -->
    <section id="teaching" class="card">
      <h3>Teaching</h3>
      <ul class="item-list">
        <li>
          <strong>Course Name</strong> – ESCP Business School, Campus  
          <span class="muted">Role (e.g. Instructor / TA), Term ‘YY</span>
        </li>
        <li>
          <strong>Course Name 2</strong> – ESCP Business School  
          <span class="muted">Role, Term ‘YY</span>
        </li>
        <li>
          <strong>Guest Lecture: Topic</strong> – Institution, Term ‘YY
        </li>
      </ul>
    </section>
We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

    <!-- CV -->
    <section id="cv" class="card">
      <h3>CV</h3>
      <p>
        You can download my full CV here:
        <a href="cv.pdf" target="_blank" rel="noopener">Download CV (PDF)</a>
      </p>
      <p class="muted">
        (Place a file named <code>cv.pdf</code> in the same folder as this
        <code>index.html</code>.)
      </p>
    </section>
### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

    <!-- Contact -->
    <section id="contact" class="card">
      <h3>Contact</h3>
      <p>
        <strong>Email:</strong> <a href="mailto:hsharma@escp.eu">hsharma@escp.eu</a><br />
        <strong>Affiliation:</strong> ESCP Business School, [Campus]<br />
        <strong>Office:</strong> [C-105]<br />
      </p>
      <p>
        I am happy to be contacted about research collaborations, teaching,
        and presentations.
      </p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© 2025 Harshit Sharma · PhD Candidate at ESCP Business School</p>
    </div>
  </footer>
</body>
</html>
