<!DOCTYPE html>
<html>

  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <meta name="description" content="Build Control : ">

    <link rel="stylesheet" type="text/css" media="screen" href="stylesheets/stylesheet.css">

    <title>Build Control</title>
  </head>

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          <a id="forkme_banner" href="https://github.com/DHGMS-Solutions/buildcontrol">View on GitHub</a>

          <h1 id="project_title">Build Control</h1>
          <h2 id="project_tagline"></h2>

            <section id="downloads">
              <a class="zip_download_link" href="https://github.com/DHGMS-Solutions/buildcontrol/zipball/master">Download this project as a .zip file</a>
              <a class="tar_download_link" href="https://github.com/DHGMS-Solutions/buildcontrol/tarball/master">Download this project as a tar.gz file</a>
            </section>
        </header>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main_content_wrap" class="outer">
      <section id="main_content" class="inner">
        <h3>
<a id="welcome-to-build-control" class="anchor" href="#welcome-to-build-control" aria-hidden="true"><span class="octicon octicon-link"></span></a>Welcome to Build Control.</h3>

<p>Build Control is a Work in progress on having a single build template that can be used to control build quality at different stages of the development cycle.</p>

<div class="row">
  <div class="col-md-6">Rule Name</div>
  <div class="col-md-2">Dev</div>
  <div class="col-md-2">Test</div>
  <div class="col-md-2">Prod</div>
</div>
{% for rule in site.data.rules %}
<div class="row">
  <div class="col-md-6">{{ rule.name }}</div>
  <div class="col-md-2">?</div>
  <div class="col-md-2">?</div>
  <div class="col-md-2">?</div>
</div>
{% endfor %}
</section>
    </div>

    <!-- FOOTER  -->
    <div id="footer_wrap" class="outer">
      <footer class="inner">
        <p class="copyright">Build Control maintained by <a href="https://github.com/DHGMS-Solutions">DHGMS-Solutions</a></p>
        <p>Published with <a href="http://pages.github.com">GitHub Pages</a></p>
      </footer>
    </div>

    

  </body>
</html>
