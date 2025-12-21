# OCA-Plus for Krita

Export animation keyframes from Krita to OCA, an open standard designed for interchange between animation and compositing tools.
This branch (Plus) focuses on adding clonelayer recognition and support for more non-destructive .OCA based workflows. 

## Overview

OCA, the Open Cel Animation format, is an open format intended to ease traditional, frame-by-frame, and cel animation data interchange.

This exporter allows Krita documents to be exported to OCA while preserving animation structure and timing. The resulting OCA files can be imported into other applications such as Blender or Adobe After Effects using available importers, or parsed directly thanks to the openness of the format.

This repository contains the official OCA exporter for Krita.

## Features

The OCA Krita exporter supports the most common features expected from drawing and animation software:

- Export of individual layers or a flattened image
- Layer groups, including pass-through mode where applicable
- Layer labels
- Layer visibility
- Clones still Inherit Alpha state via object based material slots
- Keyframes and their duration (exposure)
- Opacity keyframes
- Blending modes
- Layer sizes and coordinates
- Document color depth

## Known Issues:

- Some advanced Krita features such as transform masks are not yet supported and may cause export failures.

## Platform Support

- Application: Krita
- Operating Systems: Windows, macOS, Linux

## License

GNU GPL v3

## Author

Originally created by Duduf  
Maintained as part of the RxLaboratorio ecosystem
This branch maintained by Simon Heggie.

## Current Version

1.5.0

## Support and Community

Documentation and learning resources are available through RxLaboratorio:

- User guides
- Video tutorials
- Books and written documentation
- Community chat and support

Stay connected through the official RxLaboratorio channels for updates, discussions, and announcements.

