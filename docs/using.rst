Using Memeplayer
================

To start using memeplayer. Fist import memeplayer.js in head tag

.. code-block:: html
	<script src="http://memeplayer.com/release/memeplayer.js"></script>

And create the div with id, example: demplayer

.. code-block:: html
	<div id="demoplayer"></div>

Config something, and call init function

.. code-block:: html
	<script>
	<script> 
	var config = {
	    "sources": {
	        "type": "mp4",
	        "qualities": [
	            {
	                "resolution": 360,
	                "src": "Your video url"
	            }
	        ]
	    },
	    "autostart": false,
	    "suggeston": false,
	    "shareon": false
	};
	 memePlayer.init("#demoplayer",config)
	</script>

Done! Very simple	