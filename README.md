Backbone for Maven
=============

This library gives you a way to drop [Backbone.js](http://backbonejs.org/) into your project as a [Maven](maven.apache.org) dependency, which mens you don't have to include these third party files in your own source control.

pom.xml
-------

Add this to the <dependencies> element of your pom.xml

		<dependency>
			<groupId>com.efsavage</groupId>
			<artifactId>backbonejs</artifactId>
			<version>0.9.2</version>
		</dependency>

Usage
-------
The files will "mount" themselves at the following URLs:

* /ext/js/backbone.js

Requirements
-------

This requires a Servlet 3.0 container, such as Jetty 8.

Minified vs. Full Versions
-------

The minified versions of .css and .js files are used by default, append ?min=false to see the full versions.

Modifications
-------

The files served have not been modified in any way from their original distribution.