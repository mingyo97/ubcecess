---
---
<html lang="{{ page.lang | default: site.lang | default: "en" }}">


  {% include head.html %}

  <body>

    {% include header.html %}

    <!-- Image -->
    <div id="swag" class="img-responsive center-block container-fluid">
	<!-- Swag -->
	<div class="row">
    		<div class="title-box col-xs-8 col-xs-offset-2 col-md-4 col-md-offset-4"> 
            	<p class="title"> Swag </p>
        	</div>
	</div>
    </div>

	<div class="container">
   		<!-- Rainjackets -->
		<!--
		<div class="row">
 			<div class="col-md-4 col-xs-6"><h1>Rain Jackets</h1></div>
			<div class="col-md-8 col-xs-6"><h2>for those cold Raincouver days</h2></div>
		</div>
		-->
	
		<h1>Rain Jackets</h1>
		<h2>for those cold Raincouver days</h2>	
	
		<div class="row blue-div">
			<div class="col-md-5 col-xs-6">
				<img src="/images/NF_Men_ECELogo.gif" class="img-responsive">
				<div class="row row-margin">
					<div class="col-md-7 col-md-offset-1 col-xs-7 col-xs-offset-1">
						<p>Rain Jacket (Female)</p>
					</div>
					<div class="col-md-4 col-xs-4">
						<p class="price">$120</p>
					</div>
				</div>
			</div>
			<div class="col-md-5 col-md-offset-2 col-xs-6">
				<img src="/images/NF_Women_ECELogo.gif" class="img-responsive">
				<div class="row row-margin">
					<div class="col-md-7 col-md-offset-1 col-xs-7 col-xs-offset-1">
						<p>Rain Jacket (Male)</p>
					</div>
					<div class="col-md-4 col-xs-4">
						<p class="price">$120</p>
					</div>
				</div>
			</div>
		</div>
		<!-- Swag -->
		<div>
        	<h1>Swag</h1><p>for your personal ECE collection</p>
    	</div>
	</div>
    {% include footer.html %}

  </body>

</html>
