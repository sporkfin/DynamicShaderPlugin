# shader.setPulseAlpha_up()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Pulse Alpha__      | [setPulseAlpha()](setPulseAlpha.markdown), [setPulseAlpha_down()](setPulseAlpha_down.markdown)
| __Pulse Intensity__  |[setPulseIntensity()](setPulseIntensity.markdown), [setPulseIntensity_up()](setPulseIntensity_up.markdown), [setPulseIntensity_down()](setPulseIntensity_down.markdown)
| __Pulse zValue__     |[setPulseZValue()](setPulseZValue.markdown), [setPulseZValue_up()](setPulseZValue_up.markdown), [setPulseZValue_down()](setPulseZValue_down.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Sets the maximum alpha value of the pulse


## Syntax

	shader.setPulseAlpha_up( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulseAlpha_up( 0.75 ) -- Sets the maximum alpha value of the pulse
-- alpha pulses to 0.75

``````
