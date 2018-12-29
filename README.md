# Open Ephys GUI - Neuropixels Version

Compiled binaries for the [Open Ephys GUI](https://github.com/open-ephys/plugin-GUI)

This repository contains a special version of the Open Ephys GUI for use with Neuropixels probes. Because of limitations of the DLLs supplied by IMEC, we can only compile the GUI as a 32-bit Windows application. Otherwise, the host application is up-to-date with the [development](https://github.com/open-ephys/plugin-GUI/tree/development) branch of the standard Open Ephys GUI.


## Compatible hardware:

- Neuropixels "Phase 3a" probes (options 1-4), with Kintex FPGA and IMEC basestation (use `Neuropix-3a` plugin)
- Neuropixels 1.0 probes, with PXI interface (use `Neuropix-PXI` plugin)


## Compatible operating systems:

- Windows 7
- Windows 10


## Documentation

Documentation is hosted on the Open Ephys wiki:
- [Neuropixels Probes](https://open-ephys.atlassian.net/wiki/spaces/OEW/pages/953548803/Neuropixels+Probes)
- [Neuropix-3a](https://open-ephys.atlassian.net/wiki/spaces/OEW/pages/77332482/Neuropix-3a) plugin
- [Neuropix-PXI](https://open-ephys.atlassian.net/wiki/spaces/OEW/pages/963280903/Neuropix-PXI) plugin