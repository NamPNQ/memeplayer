Settings
========

primary
-------
Default: 'flash'
When ``'html'``, force using html5 for player

autostart
---------
Default: false
When ``true``, auto start

suggeston
---------
Default: false
When ``true``, enable suggest

shareon
-------
Default: false
When ``true``, enable share link on social

sources
-------
Setting list sources with resolution
Example:

..code-block::
	"sources": {
        "type": "mp4",
        "qualities": [
            {
                "resolution": 360,
                "src": "Your video url"
            },
            {
                "resolution": 480,
                "src": "Your video url"
            }
        ]
    }