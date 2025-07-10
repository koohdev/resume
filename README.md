<!DOCTYPE html>
<html>
<head>
<title>Resume</title>

  // to be replace
  <!-- Primary Meta Tags -->
<title>Meta Tags — Preview, Edit and Generate</title>
<meta name="title" content="Meta Tags — Preview, Edit and Generate" />
<meta name="description" content="With Meta Tags you can edit and experiment with your content then preview how your webpage will look on Google, Facebook, X and more!" />

<!-- Open Graph / Facebook -->
<meta property="og:type" content="website" />
<meta property="og:url" content="https://metatags.io/" />
<meta property="og:title" content="Meta Tags — Preview, Edit and Generate" />
<meta property="og:description" content="With Meta Tags you can edit and experiment with your content then preview how your webpage will look on Google, Facebook, X and more!" />
<meta property="og:image" content="https://metatags.io/images/meta-tags.png" />

<!-- X (Twitter) -->
<meta property="twitter:card" content="summary_large_image" />
<meta property="twitter:url" content="https://metatags.io/" />
<meta property="twitter:title" content="Meta Tags — Preview, Edit and Generate" />
<meta property="twitter:description" content="With Meta Tags you can edit and experiment with your content then preview how your webpage will look on Google, Facebook, X and more!" />
<meta property="twitter:image" content="https://metatags.io/images/meta-tags.png" />


  // smooth scrolling
  <link rel="stylesheet" href="https://unpkg.com/lenis@1.3.4/dist/lenis.css">
</head>
<body>

  <main>

    <h1>John Angel Guevarra</h1>
    <p>Creative Thinker & Problem Solver</p>
    
  </main>

  // smooth scrolling js
<script src="https://unpkg.com/lenis@1.3.4/dist/lenis.min.js"></script> 
  <script>
    // Initialize Lenis
const lenis = new Lenis();

// Use requestAnimationFrame to continuously update the scroll
function raf(time) {
  lenis.raf(time);
  requestAnimationFrame(raf);
}

requestAnimationFrame(raf);
  </script>
</body>
</html>
