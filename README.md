Evented
-----------

A repository for EventMachine (or anything based on EventMachine) examples
and so much more!

Because the event-driven programming model is so different to 'normal' programming,
good examples are critical to learning how to solve problems the 'event' way.

Got a non-trivial example?  Please submit it to me for inclusion.  It should
integrate more than one event-driven subsystem; no more 10 line echo server 
examples!  They are junk and don't teach much beyond a 30 second overview.

I'd like to see examples of calling:

 - 3rd party web services
 - database (mysql or postgresql)
 - memcached
 - message queue processing

Examples
==========

**thin/thumbnailer.rb**

A Thin-based thumbnail service which transparently pulls original images off S3 and thumbnails them according to URL parameters.

**qanat**

A SQS-based message queue processor.  Qanat will process up to 10 messages concurrently.

Sidenote: Qanat is one of the few official Scrabble words which does
not contain a U.  It is the Arabic word for an underground irrigation canal.

**evented_magick**

An eventmachine-aware version of `MiniMagick` which uses the `EM.system` call to increase performance.

Your Host
=============

Mike Perham, mperham AT gmail.com
<http://github.com/mperham>
<http://twitter.com/mperham>
<http://mikeperham.com>

