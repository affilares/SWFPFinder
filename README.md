### SWFPFinder (beta v.)

SWFPFinder is a simple and open source bash script designed to discovery the potential swf (file) parameters on the webapp analysing the swf file. SWFPFinder use `swfmill` tool, [swfmill](https://github.com/djcsdy/swfmill) is a tool to process Adobe Flash (SWF) files. It can convert SWF from and to an XML dialect called “swfml”, which is closely modeled after the SWF file format.

Install
--

```
$ wget https://raw.githubusercontent.com/m4ll0k/SWFPFinder/master/swfpfinder.sh

or 

$ git clone https://github.com/m4ll0k/SWFPFinder.git swfpfinder
$ cd swfpfinder
```

Support Platforms
--

- MacOSx
- Linux
- Window (Cygwin)

Requirements
--
- [swfmill](https://github.com/djcsdy/swfmill)
   - for linux `apt-get install swfmill`
   - for macosx `brew install swfmill`

Usage
--

```shell
$ bash swfpfinder.sh https://raw.githubusercontent.com/evilcos/xss.swf/master/xss.swf

Event
SecurityErrorEvent
xss_fla
MainTimeline
MovieClip
param
Object
action
String
cmd
attack
get_complete
get_sec_error
frame1
URLLoader
navigateToURL
URLRequest
_self
_blank
COMPLETE
addEventListener
SECURITY_ERROR
ExternalInterface
eval
call
alert
location
open
get
stop
root
loaderInfo
parameters
a
c
addFrameScript
EventDispatcher
DisplayObject
InteractiveObject
DisplayObjectContainer
Sprite
