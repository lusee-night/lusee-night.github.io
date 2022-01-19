			<nav id="sidebar">
				<div class="p-4 pt-5">
		  		<a href="{{ '/' | relative_url }}" class="img logo  mb-5" style="background-image: url({{'images/logo/LuSEE-logo-3-1d1919.png' | relative_url}});border-radius: 10px;"></a>
	        <ul class="list-unstyled components mb-5">
            <li>
              <a href="{{ '/' | relative_url }}">Home</a>
            </li>
            <li>
              <a href="{{ '/content/science.html' | relative_url }}">Science</a>
            </li>
            <li><!--  class="active" -->

	            <a href="#homeSubmenu" data-toggle="collapse" aria-expanded="false" class="dropdown-toggle">Software</a>
	            <ul class="collapse list-unstyled" id="homeSubmenu">
                <li>
                    <a href="{{ '/content/software_overview.html' | relative_url }}">Overview</a>
                </li>
                <li>
                    <a href="{{ '/content/packaging.html' | relative_url }}">Packaging</a>
                </li>
                <li>
                    <a href="{{ '/content/docker.html' | relative_url }}">Docker</a>
                </li>
	            </ul>
	          </li>

	          <li>
              <a href="#pageSubmenu" data-toggle="collapse" aria-expanded="false" class="dropdown-toggle">Hardware</a>
              <ul class="collapse list-unstyled" id="pageSubmenu">
                <li>
                    <a href="#">HW Page 1</a>
                </li>
                <li>
                    <a href="#">HW Page 2</a>
                </li>
                <li>
                    <a href="#">HW Page 3</a>
                </li>
              </ul>
	          </li>

	          <li>
              <a href="{{ '/content/contact.html' | relative_url }}">Contact</a>
	          </li>

            <li>
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
                <li class="nav-item active">
                    <a class="nav-link" href="{{ '/' | relative_url }}">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="{{ '/content/contact.html' | relative_url }}">Contact</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="https://github.com/lusee-night" target="_blank"><img src="{{ 'images/logo/github_64.png' | relative_url }}" height="16" ></a>
              </li>
              </ul>
            </div>
          </div>
        </nav>