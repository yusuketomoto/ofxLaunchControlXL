# ofxLaunchControlXL

use [novation LAUNCH CONTROL XL](http://global.novationmusic.com/launch/launch-control-xl) with openframeworks

## Dependencies

* ofxXmlSettings
* [ofxMidi](https://github.com/danomatika/ofxMidi) by [danomiatka](https://github.com/danomatika/)

## API

* void registerValue(Type &value, ofxLaunchControlXL::Type type)
* void registerValue(Type &value, ofxLaunchControlXL::Type type, int position)

Type is integer type of floating point type.

### if you use Customized Launch Control XL

edit launch_control_xl_settings.xml (default xml is automatically add to bin/data)

## Update history

### 2015/09/26 ver 0.0.1 release

* initial

## License

MIT License.

## Author

* ISHII 2bit [bufferRenaiss co., ltd.]
* ishii[at]buffer-renaiss.com

## At the last

Please create a new issue if there is a problem.
And please throw a pull request if you have a cool idea!!
