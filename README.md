Calculator
===========

![Screenshot](http://github.com/abidibo/Calculator/raw/master/logo.jpg)

Simple n-digits calculator with the following supported operations:

- sum
- difference
- division
- multiplication
- percentage
- pow
- sqrt


How to use
----------

Calculator requires 

- core/1.4.5
- more/1.4.0.1 Drag

**Include mootools framework and Calculator plugin**

	<script src="path-to-mootools-framework-core-and-more" type="text/javascript"></script>
	<script src="path-to-calculator-js" type="text/javascript"></script>

**Include Calculator stylesheet**

	<link href="path-to-calculator-css" type="text/css" rel="stylesheet" />

**Example code**

Javascript:

	window.addEvent('domready', function() {
		var calc = new Calculator({
			drag: true,
			digits: 12
		});
	})

For more demos please visit the Calculator demo page at http://www.abidibo.net/projects/js/calculator/demo

Screenshots
-----------

![Screenshot](http://github.com/abidibo/Calculator/raw/master/Docs/c_screenshot.png)

Links
-----------------

The project page: http://www.abidibo.net/projects/js/calculator  
The documentation page: http://www.abidibo.net/projects/js/calculator/doc   
The demo page: http://www.abidibo.net/projects/js/calculator/demo

Please report bugs, errors and advices in the github project page: http://github.com/abidibo/Calculator

