Znuny4OTRS - EnableFAQRichText
==============================
This package enables richtext for FAQ even if richtext is disabled in OTRS.


**Installation**

Download the package and install it via admin interface -> package manager.

**Compilation**

You can compile the OPM file using a clean OTRS installation:

* Download the latest release of OTRS or clone the Github repository
* Rename `Kernel/Config.pm.dist` to `Kernel/Config.pm` and edit `$Self->{Home}`
* Copy the `Kernel` folder from this plugin
* Execute `bin/otrs.Console.pl Dev::Package::Build {path/to/file.sopm} {folder/for/file.opm}`

The resulting OPM file, stored in `{folder/for}` can be installed via admin interface on your live installation.

**Prerequisites**

- OTRS 5.0

**Configuration**

Not needed.
