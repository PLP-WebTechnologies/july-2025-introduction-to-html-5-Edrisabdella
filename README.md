<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="A beginner-friendly HTML5 webpage demonstrating semantic structure, accessibility, and SEO best practices." />
  <meta name="author" content="Edris Abdella" />
  <title>Introduction to HTML5</title>
</head>
<body>
  <header>
    <h1>Welcome to Edris HTML5 Learning Page</h1>
    <nav aria-label="Main Navigation">
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About This Page</h2>
      <p>This page demonstrates a basic and modern semantic HTML5 structure. It includes accessible markup and SEO-friendly content designed for beginners learning web development.</p>
    </section>

    <section id="features" aria-labelledby="features-heading">
      <h2 id="features-heading">Key Features</h2>
      <article>
        <h3>Semantic Elements</h3>
        <p>We use tags like <code>&lt;header&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code>, <code>&lt;article&gt;</code>, and <code>&lt;footer&gt;</code> for clarity and meaning.</p>
      </article>
      <article>
        <h3>Accessibility</h3>
        <p>Navigation is enhanced with ARIA labels and proper heading structure to support screen readers.</p>
      </article>
      <article>
        <h3>SEO Optimization</h3>
        <p>We include meta tags for description and use descriptive headings and text to improve search visibility.</p>
      </article>
    </section>
    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact</h2>
      <p>If you have any questions, feel free to reach out via email at <a href="mailto:edrisabdella178@gmail.com">edrisabdella178@gmail.com</a>.</p>
      <p>Phone number: <a href="tel:+251905131051">+251905131051</a></p>
      <address>Dire Dawa, Ethiopia</address>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Edris Abdella. All rights reserved.</p>
  </footer>
</body>
</html>
