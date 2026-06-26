OpenRockTumbler
---------------

This project aims to be a drop-in replacement controller for common rock tumblers such as the KoolStone C1 Pro.

# Goals

* ESPHome-compatible controller for potential integration with Home Assistant
* Timer:
  * More than 9-day limit
  * Resume tumbling after power loss if time remaining
  * Periodic stir operation after timer end to prevent grit from settling
* Hall effect rotation sensor:
  * Detect if drum is actually turning
    * Alerts if belt breaks
  * Constant speed control