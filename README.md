# Datepickr
A simple javascript datepicker with no dependencies, written by [Josh Salverda](http://code.google.com/u/josh.salverda/). Compatible with browsers as grizzled as IE6.

## Demo
You can find a demo [here](http://www.joshsalverda.com/sandbox/date_pick/datepickr.html).

## Installation and Usage
Install with [Bower](http://bower.io/):

	bower install --save datepickr

Alternatively, download `datepickr.js` or `datepickr.min.js` and `datepickr.css` to your project.

Include them in your HTML:

	<script type="text/javascript" src="datepickr.js"></script>
	<link rel="stylesheet" type="text/css" href="datepickr.css">

Set up an input where you want a datepicker and initialize:

	<input id="dateID" type="text"></input>
	<script>new datepickr('dateID')</script>

Configure with options from the [Google Code project documentation](http://code.google.com/p/datepickr/wiki/Documentation)

## License
[Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0)