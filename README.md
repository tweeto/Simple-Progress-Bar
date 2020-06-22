# Simple Progress Bar

Simple progress bar library for LabVIEW. This library is written in full G code.


## What is it ?

Main features are:
- Asynchronous pre-coded user interface
- Common patterns snippets
- Errors handling
- Abort handling


## Gettings Started

This library has been developed with LabVIEW `2015 SP1` which is the minimum version required to use the library.

### Download

Download VIP files from the [Releases](https://github.com/tweeto/Simple-Progress-Bar/releases) section of this repository.

**Note**: This toolkit is not available through VIPM yet.


### Installation

Open VIP file downloaded in the previous step. VI Package Manager will automatically start and guide you through installation process. The library is installed under `user.lib` LabVIEW directory.


### Examples

Some examples are available and usable out of the box in [Example](https://github.com/tweeto/Simple-Progress-Bar/tree/master/src/Example) folder.

#### Progress Bar Example

This [example](https://github.com/tweeto/Simple-Progress-Bar/blob/master/src/Example/Progress%20Bar%20Example.vi) is the simplest example and illustrates how to use progress bar with a fixed steps count process and an unkown steps count process. 

#### Progress Bar Example Process Error

This [example](https://github.com/tweeto/Simple-Progress-Bar/blob/master/src/Example/Progress%20Bar%20Example%20with%20Process%20Error.vi) illustrates how to send warnings and errors from the process to the progress bar window. Depending on configuration the process can be stopped on errors.

Find more informations on the [Wiki](https://github.com/tweeto/Simple-Progress-Bar/wiki/Error-Handling).

#### Progress Bar Example Process Abort

This [example](https://github.com/tweeto/Simple-Progress-Bar/blob/master/src/Example/Progress%20Bar%20Example%20with%20Process%20Abort.vi) illustrates how to stop progress bar from the process without error.

#### Progress Bar Example User Cancel

This [example](https://github.com/tweeto/Simple-Progress-Bar/blob/master/src/Example/Progress%20Bar%20Example%20with%20User%20Cancel.vi) illustrates how to stop the process when user click on cancel button.

#### Progress Bar Example Multiple Instances

This [example](https://github.com/tweeto/Simple-Progress-Bar/blob/master/src/Example/Progress%20Bar%20Example%20with%20Multiple%20Instances.vi) illustrates how to use multiple instances of progress bar on case of parallel processes.

Find more informations on the [Wiki](https://github.com/tweeto/Simple-Progress-Bar/wiki/Multiple-Instances).


### Development

#### Palette

VIs are not accessible through LabVIEW palette yet.


#### Snippets

Some snippets are available in [Templates](https://github.com/tweeto/Simple-Progress-Bar/tree/master/src/Library/Templates) folder to speed up your developments.


## Documentation

All documentation of this project is available in the [Wiki](https://github.com/tweeto/Simple-Progress-Bar/wiki) of this repository.


## Support

This library is an open source project created for personnal use. This library is not supported. However, do not heasitate to contribute or open tickets if you have any idea or find bugs.
