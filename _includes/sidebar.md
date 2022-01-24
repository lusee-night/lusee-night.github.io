			<nav id="sidebar">
				<div class="p-4 pt-5">
		  		<a href="{{ '/' | relative_url }}" class="img logo  mb-5" style="background-image: url({{'images/logo/LuSEE-logo-3-1d1919.png' | relative_url}});border-radius: 10px;"></a>
	        <ul class="list-unstyled components mb-5">
            <li {% if page.name contains 'index' -%}class="active"{%- endif -%}>
              <a href="{{ '/' | relative_url }}">Home</a>
            </li>
            <li {% if page.name=='science' -%}class="active"{%- endif -%}>
              <a href="{{ '/content/science.html' | relative_url }}">Science</a>
            </li>
            <li {% if page.name contains 'software' -%}class="active"{%- endif -%}><!--  class="active" -->

	            <a href="#homeSubmenu" data-toggle="collapse" aria-expanded="false" class="dropdown-toggle">Software</a>
	            <ul class="collapse list-unstyled" id="homeSubmenu">
                <li>
                    <a href="{{ '/content/software_overview.html' | relative_url }}">Overview</a>
                </li>
                <li>
                    <a href="{{ '/content/software_packaging.html' | relative_url }}">Packaging</a>
                </li>
                <li>
                    <a href="{{ '/content/software_docker.html' | relative_url }}">Docker</a>
                </li>
	            </ul>
	          </li>

	          <li {% if page.name contains 'hardware' -%}class="active"{%- endif -%}>
              <a href="#pageSubmenu" data-toggle="collapse" aria-expanded="false" class="dropdown-toggle">Hardware</a>
              <ul class="collapse list-unstyled" id="pageSubmenu">
                <li>
                    <a href="{{ '/content/hardware_overview.html' | relative_url }}">Overview</a>
                </li>
              </ul>
	          </li>

	          <li {% if page.name=='reading' -%}class="active"{%- endif -%}>
              <a href="{{ '/content/reading.html' | relative_url }}">Reading List</a>
	          </li>

	          <li {% if page.name=='contact' -%}class="active"{%- endif -%}>
              <a href="{{ '/content/contact.html' | relative_url }}">Contact</a>
	          </li>

            <li {% if page.name=='about' -%}class="active"{%- endif -%}>
              <a href="{{ '/content/about.html' | relative_url }}">About this site</a>
          </li>
	        </ul>
      

          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>
          <ul>&nbsp;</ul>

	        <div class="footer">
	        	<p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
						  &copy;<script>document.write(new Date().getFullYear());</script> Bootstrap template by <a href="https://colorlib.com" target="_blank">Colorlib.com</a>
						  <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. --></p>
              <p>Site built<br/>  {{ site.time }}</p>
	        </div>

	      </div>
    	</nav>

        <!-- Page Content  -->
      <div id="content" class="p-4 p-md-5">

        <nav class="navbar navbar-expand-lg navbar-light bg-light">
          <div class="container-fluid">

            <button type="button" id="sidebarCollapse" class="btn btn-primary">
              <i class="fa fa-bars"></i>
              <span class="sr-only">Toggle Menu</span>
            </button>
            <button class="btn btn-dark d-inline-block d-lg-none ml-auto" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fa fa-bars"></i>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="nav navbar-nav ml-auto">
                <li  {% if page.name contains 'index' -%}class="active"{%- endif -%}">
                    <a class="nav-link" href="{{ '/' | relative_url }}">Home</a>
                </li>
                <li {% if page.name contains 'contact' -%}class="active"{%- endif -%}>
                    <a class="nav-link" href="{{ '/content/contact.html' | relative_url }}">Contact</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="https://github.com/lusee-night" target="_blank"><img src="{{ 'images/logo/github_64.png' | relative_url }}" height="20" ></a>
              </li>
              </ul>
            </div>
          </div>
        </nav>