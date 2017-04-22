### ffmpus

This repository contains Windows builds of ffmpeg and opus.

## Usage

In order to use this it is recommended to add this to the path environment variable.

It is also recommended to have git in the path as well beforehand so you can git clone this before adding this to the path.

Before cloning this ensure you clone it in the root of the partition that Windows is installed in.

And then after you are in the root you can do:

```cmd
git clone https://github.com/DecoraterBot-devs/ffmpus.git
```

This is to ensure you are able to update your ffmpeg and opus binaries with the ones in current master on this repo.

## Why add this to path?

Well if you are using python, having opus and ffmpeg in the path ensures not having to have to manually download and install / manage ffmpeg.

It also ensures that opus can be found and up to date.

Note: for using 64 bit opus with 64 bit python you must use ctypes for your code to know about the 64 bit version of python so it loads up opus64.dll instead of opus.dll which would result in a crashed python interpreter.

## Adding to path

TODO: Add steps to add this to path.
