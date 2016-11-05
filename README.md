gif-maker
=========

Make animated gifs from video clips

Installation
------------

### OSX

    $ brew install ffmpeg

### Fedora

    $ dnf install ffmpeg

Usage
-----

    $ ./gif-maker video.mp4 out.gif

Produces a 320x167, animated gif, 10fps, 10ms spaced

How it works
------------

* Use ffmpeg to produce a lot of jpegs from the video
* Convert jpegs to gifs
* Combine gifs to one animated gif

License
-------

BSD, short and sweet
