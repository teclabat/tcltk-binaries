This is the Tcl/Tk binary repository which I dedicate to the Tcl community.
The package sources are updated once a week, and on compile success the binaries uploaded here https://gitlab.com/teclabat/tcltk/-/packages.

**Tcl86** contains the following packages:

| Package | Branch | Repository |
|---------|--------|------------|
| bwidget | - | https://core.tcl-lang.org |
| critcl | - | https://github.com/andreas-kupries |
| itcl | itcl-4-0-6-rc | https://core.tcl-lang.org |
| itk | itk-4-0-2-rc | https://core.tcl-lang.org |
| iwidgets | - | https://core.tcl-lang.org |
| man2html | - | https://github.com/teclabat |
| md2html | - | https://github.com/teclabat |
| parseargs | wip | https://github.com/teclabat |
| photoresize | - | https://github.com/auriocus |
| rljson | wip | https://github.com/teclabat |
| sampleextension | - | https://core.tcl-lang.org |
| snmptools | - | https://github.com/teclabat |
| tbcload | - | https://github.com/teclabat |
| tcl | core-8-6-branch | https://core.tcl-lang.org |
| tclcompiler | - | https://github.com/teclabat |
| tclconfig | - | https://core.tcl-lang.org |
| tclcurl | - | https://github.com/teclabat |
| tclfftw | - | https://github.com/teclabat |
| tcllib | - | https://core.tcl-lang.org |
| tclntcan | - | https://github.com/teclabat |
| tclperformance | - | https://github.com/teclabat |
| tclrsvisa | - | https://github.com/teclabat |
| tclruff | - | https://github.com/teclabat |
| tcltls | tls-2.0 | https://core.tcl-lang.org |
| tcludp | wip | https://github.com/teclabat |
| tdbc | - | https://core.tcl-lang.org |
| tdbcmysql | - | https://core.tcl-lang.org |
| tdbcodbc | - | https://core.tcl-lang.org |
| tdbcpostgres | - | https://core.tcl-lang.org |
| tdbcsqlite3 | - | https://core.tcl-lang.org |
| tdom | - | https://www.tdom.org/index.html |
| thread | thread-2-8-branch | https://core.tcl-lang.org |
| tk | core-8-6-branch | https://core.tcl-lang.org |
| tkcon | - | https://github.com/teclabat |
| tkimg | trunk | https://svn.code.sf.net/p |
| tklib | - | https://core.tcl-lang.org |
| tktable | - | https://github.com/teclabat |
| tkxcursor | - | https://github.com/teclabat |
| vectcl | - | https://github.com/teclabat |


**Tcl90** still in work, but will follow asap ...

Occasionally the package registry might get deleted to save up some storage space. So please don't count on having kept old builds forever.

You can file issues here https://gitlab.com/teclabat/tcltk/-/issues but I am not providing general Tcl support, for that I'd recommend https://stackoverflow.com/questions/tagged/tcl

## Liability
All the work presented here was completed during my free time. Please ensure that you comply with all license terms, particularly those specific to each individual package. Any damage resulting from the use of this code and binaries is not my responsibility. I provide no liability nor warranty for this software.

## Windows builds
For Windows builds the `MSYS2` 64bit environment is used (https://www.msys2.org). No installation is necessary, simply extract `.tgz` file and run. For some packages it might be necessary to put `share/lib64` into the executable search path.

## Debian builds
For Debian builds the Ubuntu and Debian distributions are used. A `.deb` file is created and can be installed using `dpkg -i <file>`. The installation goes into `/opt/tcltk<version>`.

## RPM builds
For RPM builds the RedHat distributions are used. A `.rpm` file is created and can be installed using `rpm -i <file>`. The installation goes into `/opt/tcltk<version>`.
