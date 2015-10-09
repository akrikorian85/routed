sleepyMUSTACHE - Routed Setup
===============================================================================

sleepyMUSTACHE is a modular PHP micro framework designed to provide solutions for everyday PHP challenges. This routed edition is aimed at providing a scaffolding for a project that uses the frameworks router

Getting Started
-------------------------------------------------------------------------------
sleepyMUSTACHE is ready to go out of the box. Configuration is done in the *settings.php* file. There you can define your dev/stage/live environments and debugging preferences.

Whats included?
-------------------------------------------------------------------------------
The routed setup includes the core and a tool for installing [modules](https://github.com/sleepymustache/modules).

It also includes some third party libraries to help get you started including, jQuery, requirejs, normalize, html4shiv, and a small JS toolset (sleepy.js).

### Core functionality

* Debugging
* Hooks
* Routing
* Templating

### Installing Modules

We have included a python script (sleepy.py) to assist in installing modules. It does this by creating git submodules.

You can get a list of available modules:

	sleepy --list

You can install modules:

	sleepy --add Performance

You can search for modules:

	sleepy --search DB

You can get more info about a module:

	sleepyu --help Performance

Learning More
-------------------------------------------------------------------------------
Documentation about the core functionality is available in the [core repo](https://github.com/sleepymustache/core). A list of existing modules can be found in the [modules repo](https://github.com/sleepymustache/modules).