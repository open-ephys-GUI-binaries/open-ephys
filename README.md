# Open Ephys GUI - Neuropixels Version

Compiled binaries for the [Open Ephys GUI](https://github.com/open-ephys/plugin-GUI)

This repository contains a special version of the Open Ephys GUI for use with Neuropixels probes. The host application is up-to-date with the [neuropixels](https://github.com/open-ephys/plugin-GUI/tree/neuropixels) branch of the Open Ephys GUI. Eventually, the Neuropixels plugins will become part of the main Open Ephys distribution.


## Installation

Copy the "open-ephys" directory anywhere on your machine and double-click "open-ephys.exe"

If the software can't open because of missing DLLs, you'll need to install the [Visual C++ Redistributable Package for Visual Studio 2013](https://www.microsoft.com/en-us/download/details.aspx?id=40784).

The application will open a console by default, which will allow you to see the status of various under-the-hood operations. We are planning to gradually fold some of this information into progress bar windows, so it's more obvious what is happening when.


## Compatible hardware:

- Neuropixels 1.0 probes, with PXI interface (use `Neuropix-PXI` plugin)
- Neuropixels 3a probes, with Ethernet interface (use `Neuropix-3a` plugin)

## Compatible operating systems:

- Windows 7
- Windows 10

## Documentation

Documentation is hosted on the Open Ephys wiki:
- [Neuropixels Probes](https://open-ephys.atlassian.net/wiki/spaces/OEW/pages/77332482/Neuropixels+Probes)
- [Neuropix-PXI](https://open-ephys.atlassian.net/wiki/spaces/OEW/pages/963280903/Neuropix-PXI) plugin
- [Neuropix-3a](https://open-ephys.atlassian.net/wiki/spaces/OEW/pages/953548803/Neuropix-3a) plugin

## Reporting bugs & submitting feature requests

Please log any issues related to Neuropixels probes in the [Neuropixels-PXI](https://github.com/open-ephys/neuropixels-pxi/issues) or [Neuropixels-3a](https://github.com/open-ephys/neuropixels-3a/issues) repositories on GitHub.