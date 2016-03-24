regal-modules
=======

This repository contains the *stable* public modules developed by [![](https://avatars2.githubusercontent.com/u/3187882?v=3&u=e8f3dc9f996b93a97617fe59eeea93fbb05bc01c&s=16) ImmutableOctet](https://github.com/ImmutableOctet) of  [![](https://avatars2.githubusercontent.com/u/7613882?v=3&s=16) The Regal Internet Brothers](https://github.com/Regal-Internet-Brothers) using the [Monkey programming language](https://github.com/blitz-research/monkey).

Any of our public modules that are not found in this repository are considered experimental or otherwise separate. With that in mind, however, all of our modules belong under the same namespace. (***regal***)

All functionality is *'as-is'*, some things may not work as expected. That being said, I personally use many of these modules, so if a module makes it here, we've deemed it suitable for real-world use. Bug reports should be made in the associated modules' repositories, unless otherwise related to this distribution.

## Installation
This repository uses 'git submodules' for source distribution. Therefore, this repository should be cloned recursively, not directly downloaded.

On git versions 1.6.5 and newer, you may do the following from your preferred shell:
> git clone --recursive https://github.com/Regal-Internet-Brothers/regal-modules.git regal

**The exact *URI* depends on your protocol preference, view the download-area above for details.** **(***HTTPS / SSH***)**

Once you've downloaded this repository properly, place the newly created "regal" folder in your preferred Monkey "modules" folder.

To modify your module-path formally, edit your platform's configuration file in your [Monkey installation's "bin" folder](https://github.com/blitz-research/monkey/tree/develop/bin). You'll want to edit your 'MODPATH' variable, adding a **;** (Semi-colon), then the (*Parent*) directory housing these modules.

**As of 10/27/2015, this folder must be named "regal".** For legacy support, you can install the modules regularly, then add the "regal" folder as a "global modules-directory". Normal users should avoid doing this if possible. For future support, please use the proper module namespace.

When installation is finished, please follow the update instructions below:

## Module Updates
Once you've finished the initial installation process, you will probably need to update your local module versions. Modules are added as they're considered "stable", with the distribution changing occasionally. This means the module versions you have downloaded may or may not work together properly. To solve this issue, it's usually in your best interest to update.

**To update your distribution and any newly added modules, run the "Update.bat" script.**

Alternatively, you may update your existing module collection by running the "Update_Submodules_Pull.bat" script. Please note that this script does not guarantee proper stability and interoperability between existing modules. It's best to run the "Update" instead, although, this may be slower.

Some modules have separate branches, which can be pulled at your discretion. These separate branches/versions are not for regular use, and only exist for experimental development, legacy support, or other similar snapshots. It's best to stick to the main-line versions instead of relying on unfinished behavior or legacy support APIs.

### Notes

These modules support varying minimum versions of Monkey, and do not explicitly state support. Generally, if your version is an experimental version that's been out for around a week, and/or is the latest major version, it's supported. If your version is older than about a month old, then it's not supported directly, but will likely still work.

The current work-flow for the release of these modules is to create an experimental repository, then test and use the module under isolated cases until it is considered stable enough to be adopted formally.

Many of these modules were originally developed for private/internal use. Some modules still remain unreleased. These private modules will never be required to use the modules in this repository. However, they may be optionally available as extensions to my public modules. With that in mind, though, those private modules may never be imported unless explicitly requested.

## Source Control Disclaimer

A bit of clarification on my intents by releasing my source code:

I'm an advocate of open software, but some things aren't in good enough condition to release. But, what I do release is provided as-is, and may be redistributed or modified with no implied warranty, or commitment. Credit would be appreciated, but is not required. Licenses are supplied on a per-module basis, however the standard license used is the [MIT license](https://en.wikipedia.org/wiki/MIT_License).

### Design Practices

The modules available here were written with a specific design and work-flow. I will not accept pull requests that do not attempt to follow my design practices. I will, however, take pull requests at face value, modifying submissions as needed. That being said, these are not *community-driven modules*, they're **open source modules**. Pull requests are welcome, but are not always accepted without further modification.

### Other

**If you see one of my modules using types you may not think existed in Monkey, [you might want to read this](https://github.com/Regal-Internet-Brothers/typetool/blob/master/README.md).**

Some of my older modules aren't hosted on GitHub, those modules could be hosted on several platforms, including BitBucket and Git Lab. These repositories act as backups and legacy code storage, and are therefore unrelated to these repositories.

**This repository was first released on May 17th, 2014, [alongside this forum thread](http://www.monkey-x.com/Community/posts.php?topic=8506&post=93769).** Issues may be made in that thread, or on GitHub.
