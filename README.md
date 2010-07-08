ibug: Firebug for your (i)Phone
===============================

Debug JavaScript on your mobile device from the comfort of your desktop browser.

Originally developed by Joe Hewitt: [Announcement](http://www.joehewitt.com/blog/firebug_for_iph.php) - [Subversion](http://fbug.googlecode.com/svn/trunk/ibug/)

_This is rough around the edges._

Tested running on Chrome OSX with a 3.0 iPhone 3GS.

Setup
-----

* Download and install Node.js: http://nodejs.org/#download

* Run the server: `node server.js`. 
 * You can specify host/port if you'd like: `node server.js example.com:8001`.

* Point a browser at the server, http://YOUR_IP:8001/. This is your **console**.
 * You can use 127.0.0.1 as YOUR_IP but this will not work on an actual device.

* Paste `<script type="application/x-javascript" src="http://YOUR_IP:8001/ibug.js"></script>` into the page you want to debug.

* Open the page you want to debug in your browser. This is your **client**.

* Type `alert('Hello world!')` in your console window.

* BAM.
