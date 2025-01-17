# pluma-plugins

![pluma-icon](pluma.ico)
![pluma-plugin-icon](pluma-plugin.png)

## General Information

A set set of plugins for Pluma, the MATE text editor. The package *pluma-plugins* started as a fork of *gedit-plugins*.

Currently available plugins:

- **bookmarks** - *Easy document navigation with bookmarks.*
- **bracketcompletion** - *Automatically adds closing brackets.*
- **codecomment** - *Comment and uncomment blocks of code.*
- **quickhighlight** - *Highlights every occurrences of selected text*
- **smartspaces** - *Forget you’re not using tabulations.*
- **sourcecodebrowser** - *View and navigate functions, variables and namespaces*
- **synctex** - *SyncTeX synchronization of TeX files and PDF output.*
- **terminal** - *Embed a terminal in the bottom pane.*
- **wordcompletion** - *Word completion using the completion framework.*

Note:

- The *synctex* plugin requires `dbus-python` (>= 0.82).
- The *terminal* plugin requires the `VTE` (>= 2.91) library.
- The *sourcecodebrowser* plugin requires `ctags` at runtime.

See the Pluma [README](https://github.com/Libre-MATE/pluma/blob/master/README.md) file for more information.

## Installation

Simple install procedure:

```
$ ./autogen.sh                              # Build configuration
$ make                                      # Build
[ Become root if necessary ]
$ make install                              # Installation
```
