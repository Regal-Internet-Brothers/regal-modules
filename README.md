regal-modules
=======

This repository contains the *stable* public modules written by The Regal Internet Brothers in [Monkey](https://github.com/blitz-research/monkey). Any of our public modules that are not found in this repository are considered experimental or otherwise separate. That being said, they belong in the same parent directory when used.

All functionality is *'as-is'*, some things may not work as expected. That being said, I personally use many of these modules, so if a module makes it here, I've deemed it suitable for real-world use.

## Installation
On git versions 1.6.5 and newer, you may do the following from a command-line:
> git clone --recursive https://github.com/Regal-Internet-Brothers/regal-modules.git

**The exact *URI* depends on your protocol preference, view the download-area above for details.** **(***HTTPS / SSH***)**

Once you've downloaded this repository properly, there's a few ways to handle module placement. Either create a sub-folder in one of your global "modules" folders, or create a sub-folder for your project. **As of 10/27/2015, this sub-folder must be named "regal".** These modules now assume the parent-directory "**regal**". For legacy support, you can add the "regal" folder, then add that as a global module directory as well.

To modify your module-path formally, edit your platform's configuration file in your [Monkey installation's "bin" folder](https://github.com/blitz-research/monkey/tree/develop/bin). You'll want to edit your 'MODPATH' variable, adding a **;** (Semi-colon), then the (*Parent*) directory housing these modules. For legacy support, you may also add the main "regal" directory, but for future support, please use the proper module prefix.

### Notes

These modules support varying minimum versions of Monkey, and do not explicitly state support. Generally, if your version is an experimental version that's been out for around a week, and/or is the latest major version, it's supported. If your version is older than about a month old, then it's not supported directly, but will likely still work.

The current work-flow for the release of these modules is to create an experimental/trial repository, then eventually get the module stable enough to be adopted into this repository.

I originally wrote a number of these modules for private/internal use. Some of my modules have not been released. These modules will NOT be required to use the modules in this repository. However, they may be optionally available as extensions to my public modules. When using them, place them in the same master directory ("regal").

## Source Control Disclaimer

A bit of clarification on my intents by releasing my source code:

I'm an advocate of open software, but some things aren't in good enough condition to release. But, what I do release is provided as-is, and may be redistributed or modified with no implied warranty, or commitment. Credit would be appreciated, but is not required. Licenses are supplied on a per-module basis, however the standard license used is the [MIT license](https://en.wikipedia.org/wiki/MIT_License).

### Design Practices

The modules available here were written with a specific design and work-flow. I will not accept pull requests that do not attempt to follow my design practices. I will, however, take pull requests at face value, modifying submissions as needed. That being said, these are not *community-driven modules*, they're **open source modules**. Pull requests are welcome, but are not always accepted without further modification.

### Other

**If you see one of my modules using types you may not think existed in Monkey, [you might want to read this](https://github.com/Regal-Internet-Brothers/typetool/blob/master/README.md).**
**Some of my older modules aren't hosted on GitHub, those modules could be in several places, but they're most likely on [BitBucket](https://bitbucket.org/ImmutableOctet).**
**This repository was released on May 17th, 2014, and was released [alongside this forum post](http://www.monkey-x.com/Community/posts.php?topic=8506&post=93769).**
