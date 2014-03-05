# Alfred 2 Workflow for Philips Hue

## I need v2 Testers!

Want to try out version 2 of this workflow?  I need testers to help me try it out before I publish it!  Interested?  Tweet at [@benjamin_knight](https://twitter.com/benjamin_knight)

Here's a sneak peek:

![v2](http://cl.ly/image/0R2p2H0z2443/Screen%20Shot%202014-03-04%20at%209.32.11%20PM.png)

Features:

* "Lights" is now the index result set.
* "All Lights" option for setting the state for all lights in one command.
* Lights icons are now the actual current light color!  Plus better icons overall.
* Save presets states for all lights.
* Set which lights the workflow controls.
* Set reminders using the scheduling API.

## Usage

	hue [<command> | <light>:<function>:<query>]

## Examples

	hue off
	hue on
	hue party
	hue lights
	hue 2:off
	hue 1:effect:colorloop
	hue 1:effect:none
	hue 3:color:red

## Download

Download the current version here: http://goo.gl/L3swBq

### Changelog

	1.0
	 * Speed improvements
	
	0.9
	 * Initial Release
	 * Old download link: http://goo.gl/H26W2
 
## Setup

![Setup](/screenshots/setup.png)

Press the link button on the top of the bridge and use the `setup-hue` Alfred keyword within 30 seconds to automatically configure the workflow to work with the Hue bridge on the local network.

A group id can optionally be specified, e.g. `setup-hue 1` (defaults to `0`, which is all of the Hue bulbs).  This will control which lights are affected by the group actions (e.g. "Turn all lights off").  Check out the docs for the [Groups API](http://developers.meethue.com/2_groupsapi.html).

## Screenshots

Home (blank query):

![Home](/screenshots/home.png)

Lights:

![Lights](/screenshots/lights.png)

Light controls:

![Control](/screenshots/control.png)

Setting the color:

![Color](/screenshots/color.png)

## Roadmap

* Add the ability to save current state as a preset.
