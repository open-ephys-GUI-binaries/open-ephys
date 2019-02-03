# NpxExtractor

Extracts NPX files saved by the [Open Ephys GUI](https://github.com/open-ephys/plugin-GUI)

If you've saved Neuropixels data in compressed "NPX" format, this program will convert it to a more useful Binary format (flat binary files of 16-bit integers).

This will work with data saved by the Neuropix-3a or Neuropix-PXI plugins.

## Usage:

Open up a comnmand window (type 'cmd' in the Windows search bar), and cd to the directory containing NpxExtractor.exe

Run:
`> NpxExtractor.exe <input_directory> <output_directory>`

`<input_directory>` = where your .npx files were saved
`<output_directory>` = where you want the data to be extracted to

*WARNING:* This version of NpxExtractor.exe assumes the default gain values of 500x for the AP band and 250x for the LFP band. If you are using a different gain value, you'll need to scale the continuous data outputs accordingly. We are working on a version that will automatically read the gain values from the settings file.