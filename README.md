# An extended m2html
It has been quite long since the last time m2html was updated by [Guillaume Flandin](https://www.artefact.tk/software/matlab/m2html/), who extended the [MAT2HTML](http://fresh.t-systems-sfr.com/unix/src/www/mat2html) by J.C. Kantor. 

I have no intention to complete all the work in the TODO list, but only improve it to fulfill my needs. Help files are available on the [original m2html website](https://www.artefact.tk/software/matlab/m2html/).

## Changelog
*The changelog and revision tag continues what was left by Guillaume Flandin.*

#### Revision 1.6 (2018/10/21)

New features:
- added basic support for MATLAB class. `classdef` is now highlighted and headers (purpose, synopsis and descriptions) are also filled.
- added an option to turn on/off global `See also` hypertext link.
- added a new template, frameModern (new icons, text style, etc.).
- adds `None.` to `calls` and `is called by` sections if they are empty.
