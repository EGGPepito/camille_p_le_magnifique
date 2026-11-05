[index.html](https://github.com/user-attachments/files/34434992/index.html)
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
   "http://www.w3.org/TR/html4/strict.dtd">
<html lang="fr">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  <meta name="description" content="Short description of your website">
  <meta name="keywords" content="keyword1, keyword2, keyword3">
  <meta name="author" content="Your Name">
  <title>My Website - Home</title>

  <!-- CSS: link an external stylesheet here later -->
  <!-- <link rel="stylesheet" type="text/css" href="css/style.css"> -->

  <!-- CSS: or use an internal stylesheet -->
  <style type="text/css">
    /* Add your CSS here */
  </style>

  <!-- JavaScript: link an external script here later -->
  <!-- <script type="text/javascript" src="js/script.js"></script> -->
</head>

<body>

  <!-- ===== WRAPPER (page container) ===== -->
  <div id="wrapper">

    <!-- ===== HEADER ===== -->
    <div id="header">
      <div id="logo">
        <h1><a href="index.html">My Website</a></h1>
        <p class="tagline">Your catchy tagline goes here</p>
      </div>
    </div>

    <!-- ===== NAVIGATION ===== -->
    <div id="navigation">
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="blog.html">Blog</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </div>

    <!-- ===== HERO / BANNER ===== -->
    <div id="hero">
      <h2>ur zesty</h2>
      <p>A short introduction that tells visitors what this site is about.</p>
      <p><a href="services.html" class="button">Learn More</a></p>
    </div>

    <!-- ===== MAIN AREA (content + sidebar) ===== -->
    <div id="main">

      <!-- ----- Main content column ----- -->
      <div id="content">

        <div class="section" id="featured">
          <h2>Featured</h2>

          <div class="feature-box" id="feature-1">
            <h3>Feature One</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore.</p>
            <p><a href="#">Read more</a></p>
          </div>

          <div class="feature-box" id="feature-2">
            <h3>Feature Two</h3>
            <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo.</p>
            <p><a href="#">Read more</a></p>
          </div>

          <div class="feature-box" id="feature-3">
            <h3>Feature Three</h3>
            <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla.</p>
            <p><a href="#">Read more</a></p>
          </div>
        </div>

        <div class="section" id="latest-news">
          <h2>Latest News</h2>

          <div class="post">
            <h3><a href="#">Post title one</a></h3>
            <p class="meta">Posted on 01 January 2026</p>
            <p>Short excerpt of the post. Excepteur sint occaecat cupidatat non proident.</p>
          </div>

          <div class="post">
            <h3><a href="#">Post title two</a></h3>
            <p class="meta">Posted on 15 January 2026</p>
            <p>Short excerpt of the post. Sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>

      </div>
      <!-- end #content -->

      <!-- ----- Sidebar ----- -->
      <div id="sidebar">

        <div class="widget" id="search-widget">
          <h3>Search</h3>
          <form action="search.html" method="get">
            <div>
              <label for="q">Search:</label>
              <input type="text" id="q" name="q">
              <input type="submit" value="Go">
            </div>
          </form>
        </div>

        <div class="widget" id="links-widget">
          <h3>Quick Links</h3>
          <ul>
            <li><a href="#">Link one</a></li>
            <li><a href="#">Link two</a></li>
            <li><a href="#">Link three</a></li>
          </ul>
        </div>

        <div class="widget" id="newsletter-widget">
          <h3>Newsletter</h3>
          <form action="subscribe.html" method="post">
            <div>
              <label for="email">Email:</label>
              <input type="text" id="email" name="email">
              <input type="submit" value="Subscribe">
            </div>
          </form>
        </div>

      </div>
      <!-- end #sidebar -->

      <!-- Clear floats here once you add CSS floats -->
      <div class="clear"></div>

    </div>
    <!-- end #main -->

    <!-- ===== FOOTER ===== -->
    <div id="footer">
      <div class="footer-column" id="footer-about">
        <h4>About</h4>
        <p>A few words about your website or company.</p>
      </div>

      <div class="footer-column" id="footer-contact">
        <h4>Contact</h4>
        <p>123 Example Street<br>75000 Paris, France<br>info@example.com</p>
      </div>

      <div class="footer-column" id="footer-social">
        <h4>Follow Us</h4>
        <ul>
          <li><a href="#">Facebook</a></li>
          <li><a href="#">Twitter</a></li>
          <li><a href="#">Instagram</a></li>
        </ul>
      </div>

      <div class="clear"></div>

      <p id="copyright">&copy; 2026 My Website. All rights reserved.</p>
    </div>

  </div>
  <!-- end #wrapper -->

  <!-- JavaScript: scripts placed here load after the page content -->
  <script type="text/javascript">
    // Add your JavaScript here
  </script>

</body>
</html>
