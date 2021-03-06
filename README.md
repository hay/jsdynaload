jsDynaLoad()
============

A dynamic Javascript file loader with support for arrays and callbacks

Usage
-----

You can either load a single script (just provide the URL) or an array
of scripts. You can then provide a callback for your 'init' function

### Single script:
    jsDynaLoad("http://example.com/myscript.js", function() {
        alert('loaded!');
    });

### Multiple scripts:
    var scripts = ['script1.js', 'script2.js', 'script3.js'];
    jsDynaLoad(scripts, function() {
        alert("All scripts loaded!");
    });
    
For a demonstration check the 'example' directory, or read the [tutorial][tutorial]. For production you can either use the minified version or copy-paste in a `<script>` tag to save a HTTP request.
    
More information
----------------

### Source
[http://github.com/hay/jsdynaload](http://github.com/hay/jsdynaload)

### Tutorial
[http://www.haykranen.nl/projects/jsdynaload/](http://www.haykranen.nl/projects/jsdynaload/)

### Based on Nicholas C. Zakas' script:
[http://www.nczonline.net/blog/2009/07/28/the-best-way-to-load-external-javascript/](http://www.nczonline.net/blog/2009/07/28/the-best-way-to-load-external-javascript/)

License
-------
Licensed under the MIT / X11 License:
[http://opensource.org/licenses/mit-license.php](http://opensource.org/licenses/mit-license.php)