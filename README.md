# Dynamic Shader
A Corona SDK plug-in for dynamically shading display objects in real time

# Dynamic Shader: Plugin API Docs

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [Library](http://docs.coronalabs.com/api/type/Library.html)
| __Corona Store__     | [Dynamic Shader](http://store.coronalabs.com/plugin/dynamic-shader)
| __Keywords__         | 
| __See also__         | 

## Overview

The Dynamic Shader plugin can be used in your [Corona](https://coronalabs.com/products/corona-sdk/) project. It enables you to add real time shading to your display objects.

ADDITIONALLY, you will need to provide a normal map file for each object you wish to shade.
There are many applications that will allow you to easily create normal maps for your image files.
We suggest trying [Sprite Illuminator](https://www.codeandweb.com/spriteilluminator) using their free trial option.  If you like it, please upgrade.


## Syntax

	local shader = require "plugin.dynamic-shader"

### Functions
__Controlling the Light Source__ 
##### [shader.addLight()](addLight.markdown)
##### [shader.removeLight()](removeLight.markdown)
##### [shader.setLightColor()](setLightColor.markdown)
##### [shader.setLightType()](setLightType.markdown)
##### [shader.getLightSource()](getLightSource.markdown)
##### [shader.getLightTable()](getLightTable.markdown)

__Adding and Removing Objects__ 
##### [shader.addObject()](addObject.markdown)
##### [shader.removeObject()](removeObject.markdown)
##### [shader.getObjectList()](getObjectList.markdown)


__Adjusting Shading Parameters__ 
##### [shader.setAlpha()](setAlpha.markdown)
##### [shader.setIntensity()](setIntensity.markdown)
##### [shader.setZValue()](setZValue.markdown)
##### [shader.setConstant()](setConstant.markdown)
##### [shader.setLinear()](setLinear.markdown)
##### [shader.setQuadratic()](setQuadratic.markdown)

__Controlling the Dynamic Shading Engine__ 
##### [shader.start()](start.markdown)
##### [shader.stop()](stop.markdown)
##### [shader.destroy()](destroy.markdown)
##### [shader.getEngineState()](getEngineState.markdown)

### Properties

##### [Dynamic Shader.PROPERTY](PROPERTY.markdown)

## Project Configuration

### Corona Store Activation

In order to use this plugin, you must activate the plugin at the [Corona Store](http://store.coronalabs.com/plugin/dynamic-shader).
You will also need to provide a normal map file for each object you wish to shade.
There are many applications that will allow you to easily create normal maps for your image files.
We suggest trying [Sprite Illuminator](https://www.codeandweb.com/spriteilluminator) using their free trial option.  If you like it, please upgrade.

### SDK

When you build using the Corona Simulator, the server automatically takes care of integrating the plugin into your project. 

All you need to do is add an entry into a `plugins` table of your `build.settings`. The following is an example of a minimal `build.settings` file:

``````
settings =
{
	plugins =
	{
		-- key is the name passed to Lua's 'require()'
		["plugin.dynamic-shader"] =
		{
			-- required
			publisherId = "REVERSE_PUBLISHER_URL",
		},
	},		
}
``````

### Enterprise

If you have activated this plugin, you can download this plugin from the corresponding plugin page in the [Corona Store](http://store.coronalabs.com/plugin/dynamic-shader).


## Platform-specific Notes

[Insert discussion on issues specific to iOS/Android/etc, or to specific devices]


## Resources

### Sample Code

You can access sample code [here](SAMPLE_CODE_URL).

### Support

More support is available from the PUBLISHER_NAME team:

* [E-mail](mailto://PUBLISHER_CONTACT@PUBLISHER_URL)
* [Forum](http://FORUM_URL)
* [Plugin Publisher](http://PUBLISHER_URL)


## Compatibility

| Platform                     | Supported
| ---------------------------- | ---------------------------- 
| iOS                          | Yes
| Android                      | Yes
| Android (GameStick)          | No
| Android (Kindle)             | Yes
| Android (NOOK)               | Yes
| Android (Ouya)               | No
| Mac App                      | Yes
| Win32 App                    | Yes
| Windows Phone 8              | No
| Corona Simulator (Mac)       | Yes
| Corona Simulator (Win)       | Yes

