# Yeloo

## Commandant Usages

| Command | Example | Usage | Version |
|--|--|--|--|
| install | To Install Command (packages) or folders with no commands (source) | yeloo install dir | build-0.0.8 |
| uninstall | To uninstall Command (packages) | yeloo uninstall dir | build-0.0.0 |
| help | Get Information About Yeloo Commands Or Overally| yeloo help install | build-0.0.0 |

## Package Structure
```
/ package
   / stream.hpp
   / info.xml
   / source /
```
- stream.hpp: store images, gui application, video, and audio for let yeloo start those thing without scanning there locations or connect to servers. ( offline )
- info.xml: store all the package data, source, name, creator, and version. ( need for the help Command )*
***warring: without without info.xml package will failed***
- source: store all the package files.
