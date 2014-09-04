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

When ``true``, enable suggest, if enable, please setting related

related
-------

Default: ''
Url for related video, return xml format like this:

.. code-block:: xml

	<?xml version="1.0" encoding="UTF-8"?>
	<videos>
        <video type="link">
	        <title><![CDATA[Same video 1]]></title>
	        <image>//imgs.meme.vn/video/clip/2014/09/04/14/39/ab421a95ba15c1b9e2a6a3218df40c04.jpg</image>
	        <!-- phuc vu cho type:link -->
	        <link target="_blank"><![CDATA[//www.meme.vn/video?v=gnqy5FbJZt]]></link>
	    </video>
	    <video type="link">
	        <title><![CDATA[Same video 2]]></title>
	        <image>//imgs.meme.vn/video/clip/2014/09/04/14/34/cfd4a7f06bb240c846f5f7ace20125fe.jpg</image>
	        <!-- phuc vu cho type:link -->
	        <link target="_blank"><![CDATA[//www.meme.vn/video?v=4rZmyeNP6p]]></link>
	    </video>
	    <video type="link">
	        <title><![CDATA[Same video 3]]></title>
	        <image>//imgs.meme.vn/video/clip/2014/09/04/14/08/e6299e6bca08f8876e98b6246cd15cf4.jpg</image>
	        <!-- phuc vu cho type:link -->
	        <link target="_blank"><![CDATA[//www.meme.vn/video?v=fx1kwWTPru]]></link>
	    </video>
	    <video type="link">
	        <title><![CDATA[Same video 4]]></title>
	        <image>//imgs.meme.vn/video/clip/2014/09/04/13/49/de86ac159d4476586d146b42c57df177.jpg</image>
	        <!-- phuc vu cho type:link -->
	        <link target="_blank"><![CDATA[//www.meme.vn/video?v=dEOsLbMoup]]></link>
	    </video>
	    <video type="link">
	        <title><![CDATA[Same video 5]]></title>
	        <image>//imgs.meme.vn/video/clip/2014/09/04/12/54/bfe118efe85d119bf70a6aa991e26e14.jpg</image>
	        <!-- phuc vu cho type:link -->
	        <link target="_blank"><![CDATA[//www.meme.vn/video?v=xstm4IAYy7]]></link>
	    </video>
	        <video type="link">
	        <title><![CDATA[Same video 6]]></title>
	        <image>//imgs.meme.vn/video/clip/2014/09/04/12/32/a7d3a1c66c54b04fbdf692327b6505b2.jpg</image>
	        <!-- phuc vu cho type:link -->
	        <link target="_blank"><![CDATA[//www.meme.vn/video?v=SCsNKr5aep]]></link>
	    </video>
	</videos>

shareon
-------

Default: false

When ``true``, enable share link on social

sources
-------

Setting list sources with resolution

Example:

.. code-block:: none

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

thumb
-----

Default: 'html5.memeplayer.com/beta/thumbs.jpg'

Thumbnails for video


styleSheet
----------

advertising
-----------

You can setting by hand in http://memeplayer.com/dashboard

Thank for reading.