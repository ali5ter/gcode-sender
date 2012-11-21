Command line monitor and g-code sender for the [Arduino grblShield](https://www.synthetos.com/project/grblshield/).

Written so I could hook up my MacBook to my [ShapeOko](http://www.shapeoko.com/wiki/),
test a few [g-code instructions](http://linuxcnc.org/docs/html/gcode.html),
mess with the [grbl](https://github.com/grbl/grbl/wiki) configuration,
implement a simple jog system devined with waypoints and stream some g-code to
get said ShapeOko to dance.

Warning: This is all command line and nothing as user-friendly as the [Universal
G-Code Sender](https://github.com/winder/Universal-G-Code-Sender)

Status
------
* Monitor (ala the Arduino Serial Monitor Tool) complete.
* Jog feature done and being tested... mainly by my 5 year old son :)
* Writing a simple waypoint manager. Panders to my laziness so I don't have to
  keep jog'ing back to the same position each time.
* This waypoint manager might also provide a way to store limits for each axis.
* Started writing the framework for the g-code sender/streamer thingy.

Dependencies
------------
* color             <http://ansi-color.googlecode.com>

References
----------
* grblShield <http://www.synthetos.com/wiki/index.php?title=Projects:grblShield>
* grbl <https://github.com/grbl/grbl/wiki>
* g-code <http://linuxcnc.org/docs/html/gcode.html>
* ShapeOko <http://www.shapeoko.com/wiki/>
* Universal G-Code Sender <https://github.com/winder/Universal-G-Code-Sender>
