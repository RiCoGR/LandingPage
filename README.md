# LandingPage

LandingPage is a CSS, HTML and JavaScipt project for Landing Page section on Front end program.

## Responsive

Fully responsive Website.

## Dynamic Menu

Dynamicaly generated Menu.

Count all Section Tag Names on document.body and generate that much nav-items.

``` var section = document.body.getElementsByTagName("section");           
	for (var i = 0; i < section.length; i++) {
	    var finalHtml = "";
	    finalHtml += '<li class="nav-item">';
	    finalHtml += '<a class="nav-link page-scroll" href="#' + section[i].id + '">' + section[i].id.toUpperCase() + '</a>';
	    finalHtml += '</li>';
	    $("#navbarsExampleDefault ul").append(finalHtml);
	}
```