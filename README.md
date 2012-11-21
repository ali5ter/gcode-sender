Monitor and g-code sender for the Arduino grblShield

Written so I could hook up my MacBookPro to my ShapeOko, test a few g-code
instructions, mess with the grbl configuration, have a simple jog and waypoint
system and stream some g-code files.

Warning: This is all command line and nothing as user-friendly as the Universal
G-Code Sender

Status
------
* Monitor (ala the Arduino Serial Monitor Tool) complete.
* Jog feature done and being tested... mainly by my 5 year old son :)
* Writing a simple waypoint manager. Panders to my laziness so I don't have to
  keep jog'ing back to the same position each time.
* This waypoint manager could also provide a way to This way to configure a
  stored limit for each axis.
* Started writing the framework for the g-code sender/streamer thingy.

Dependencies
------------
* color             <http://ansi-color.googlecode.com>

References
----------
* grbl <https://github.com/grbl/grbl/wiki>
* g-code <http://linuxcnc.org/docs/html/gcode.html>
* ShapeOko <http://www.shapeoko.com/wiki/>
* Universal G-Code Sender <https://github.com/winder/Universal-G-Code-Sender>
