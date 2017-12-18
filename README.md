# pixi-pause

pixi-pause is a pixi.js plugin which automatically pauses and resumes your `PIXI.Application` when the browser window's visibilty is changed.


## Install

```shell
npm i pixi-pause
```

## Usage

### Basic usage

### Importing

Pixi pause will automatically begin listening to visibilty changes.

#### common.js

```js
require('pixi.js')
require('pixi-pause')
```

#### es6 modules

```js
import pixi from 'pixi.js'
import pixiPause from 'pixi-pause'
```

### Disable

**pixi-pause** will be enabled by default. But occassionaly it is important to disable automatic pausing and resuming.

```js
// disable
PIXI.autoPause = false

// enable
PIXI.autoPause = true
```
