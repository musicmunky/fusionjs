# fusionjs

This is a javascript library I've been writing in bits and pieces over the years.
Basically, whenever I find myself writing the same piece of code over and over again I throw it into this file for the sake of convenience.
I am fully aware that a lot of what is done in this library already exists (and is probably better implemented) in things like
jQuery, etc.  But this is mine.  So it might be useless, but it's mine.
  
  
# requirements
The main thing you'll need if you want to use this is some version of jQuery, preferably the latest 1.x release greater than 1.8 or so.  I haven't tested the library
with any of the 2.x or 3.x releases, so there's no guarantee it'll work with them.  You might ask, again, why I'm using this library at all
when I'm already importing jQuery?  Well, honestly the only reason the library need jQuery is for the AJAX stuff, which I'm currently working on
replacing.  The plan is to get to a point where it doesn't need jQuery, but until then you'll need it if you plan on doing an AJAX calls.