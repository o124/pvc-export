### Implen spectra export(er)

__Intention:__

- extract XY (absorbance spectrum) data from PVC wavescan files created by _"Implen NanoPhotometer Pearl P300"_
- export the data as a "CSV" (TAB-separated) table, original and smoothed
- find most prominent peaks in the spectrum and export them as a separate CSV table
- plot the data and save the image
- support loading of multiple PVC files, plotting them together in one figure and exporting them into a single table
- if a custom configuration file (*.yaml) provided (by the`-c`option), read it,
  merge it with the default configuration and use to style the plot(s)
- if requested (by the`--cc`option), create a custom configuration file template

_The repo has moved to [GitLab][]_

[GitLab]:
https://gitlab.com/_124_/pvc-export
