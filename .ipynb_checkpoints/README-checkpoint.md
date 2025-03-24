# The New and Improved _beatblock guide_

<sub/> More info from base editor guide.

## Table of Contents

<sub/> Will Do later

## Getting Started

### Importing Songs

### Issues with Importing Songs

### Placing Notes & Events

### Note Types

### VFX Event Types

### Other Event Types (and advanced)

### Hotkeys

## Var List

### Bools
caseSensitive = true

#### Standard Bools
| Variable Name             | Default | Description                                                            |
| ------------------------- | ------- | ---------------------------------------------------------------------- |
| vfx.hwaves.flip           | false   | Should the amplitude of hwaves flip every frame? (hwaves is easable)   |
| vfx.notesFollowPlayer     | true    | Should notes move with the player when p.x or p.y is changed           |
| vfx.drawCombo             | true    | Should combo be displayed?                                             |
| vfx.drawAccuracy          | true    | Should accuracy be displayed in expanded hud?                          |
| vfx.drawSongTitle         | true    | Should song title be displayed in expanded hud?                        |
| vfx.drawUI                | true    | Should UI be displayed? (has priority over draw vars)                  |
| vfx.ignoreNoiseCorrection | false   | Should the alternate noise calculation methode be used?                |
| exitingLevel              | false   | Should the level end on pause-resume or beat 0 if placed in load beat? |
| vfx.calibration           | false   | Should the level use calibration system?                               |
| paused                    | false   | Should the level be paused?                                            |
| holdEntityDraw            | true    | Should do something with holds?                                        |

#### Editor Only Bools (broken stuff)
| Variable Name             | Default | Description                                                                                                       |
| ------------------------- | ------- | ----------------------------------------------------------------------------------------------------------------- |
| choosingVariant           | true    | Should do something?                                                                                              |
| errorDialogue             | false   | Should the error dialogue exist? (does make *an* error dialogue in standard play, just not the one it's meant to) |
| levelPropertiesDialogue   | false   | Should the level properties dialogue exist?                                                                       |
| allowDevOnly              | false   | Should dev only stuff be allowed?                                                                                 |
| overlappingEventsDialogue | false   | Should the overlapping events dialogue be shown?                                                                  |
| resetwindows              | false   | Should the windows be reset?                                                                                      |
| multieditdeltamode        | false   | Should delta mode be enabled in multiselect?                                                                      |
| altSliderHovered          | false   | Should the alt slider be hovered over?                                                                            |
| altSliderHeld             | false   | Should the alt slider be held?                                                                                    |
| startClickFromSlider      | false   | Should do something?                                                                                              |
| And more variables        | yes     | Should there be more vars?                                                                                        |

THE INCONSISTENCIES ARE **NOT MY FAULT, blame the devs.** (jk they are amazing people, please don't yell at them)

### Eases

| Variable Name           | Default | Description                                                    |
| ----------------------- | ------- | -------------------------------------------------------------- |
| vfx.tapWidthPulse       | 3       | Line thickness for taps on pulses.                             |
| vfx.angleTwist.offset   | 0       | How much angles should be offset by at the specified distance. |
| vfx.angleTwist.distance | 8       | How far away angles should be offset from.                     |
| vfx.hglitch.strength    | 0       | How many pixels in either direction hglitch can shift.         |
| vfx.hglitch.resolution  | 3       | How tall in pixels hglitch "chunks" should be.                 |
| vfx.hwaves.strength     | 0       | Controls the amplitude of the screen waves.                    |
| vfx.hwaves.offset       | 0       | How offset the waves should be.                                |
| vfx.hwaves.offsetDelta  | 0       | How much the offset should be changed ever frame.              |
|                         |         |                                                                |
<sub/> There are text eases, more info **will** be in wiki

## Deco

### Color Channels (and another bypass mod)
| ColorChannel | DecoColor |
| ------------ | --------- |
|              |           |
### Deco Properties

### Still Decos

### Animated Decos

## Rhythms 101

### Basic Rhythms

### Weird/advanced rhythms
