This is the Tcl/Tk binary repository which I dedicate to the Tcl community.
The package sources are updated once a week, and on compile success the binaries uploaded here: https://github.com/teclabat/tcltk-binaries/releases

**Tcl86** contains the following packages:

| Package | Branch | Repository |
|---------|--------|------------|
| bwidget | - | https://core.tcl-lang.org/bwidget |
| critcl | - | https://github.com/andreas-kupries/critcl |
| itcl | itcl-4-0-6-rc | https://core.tcl-lang.org/itcl |
| itk | itk-4-0-2-rc | https://core.tcl-lang.org/itk |
| iwidgets | - | https://core.tcl-lang.org/iwidgets |
| man2html | - | https://github.com/teclabat/man2html |
| md2html | - | https://github.com/teclabat/md2html |
| parseargs | wip | https://github.com/teclabat/fork-parseargs |
| photoresize | - | https://github.com/auriocus/photoresize |
| rljson | wip | https://github.com/teclabat/fork-rljson |
| snmptools | - | https://github.com/teclabat/fork-snmptools |
| tbcload | - | https://github.com/teclabat/fork-tbcload |
| tcl | core-8-6-branch | https://core.tcl-lang.org/tcl |
| tclcompiler | - | https://github.com/teclabat/fork-tclcompiler |
| tclconfig | - | https://core.tcl-lang.org/tclconfig |
| tclcurl | - | https://github.com/teclabat/fork-tclcurl |
| tclfftw | - | https://github.com/teclabat/tclffts |
| tcllib | - | https://core.tcl-lang.org/tcllib |
| tclntcan | - | https://github.com/teclabat/tclntcan |
| tclperformance | - | https://github.com/teclabat/tclperformance |
| tclrsvisa | - | https://github.com/teclabat/tclrsvisa |
| tclruff | - | https://github.com/teclabat/fork-tclruff |
| tcltls | tls-2.0 | https://core.tcl-lang.org/tcltls |
| tcludp | wip | https://github.com/teclabat/fork-tcludp |
| tdbc | - | https://core.tcl-lang.org/tdbc |
| tdbcmysql | - | https://core.tcl-lang.org/tdbcmysql |
| tdbcodbc | - | https://core.tcl-lang.org/tdbcodbc |
| tdbcpostgres | - | https://core.tcl-lang.org/tdbcpostgres |
| tdbcsqlite3 | - | https://core.tcl-lang.org/tdbcsqlite3 |
| tdom | - | https://www.tdom.org/index.html |
| thread | thread-2-8-branch | https://core.tcl-lang.org/thread |
| tk | core-8-6-branch | https://core.tcl-lang.org/tk |
| tkcon | - | https://github.com/teclabat/fork-tkcon |
| tkimg | trunk | https://sourceforge.net/p/tkimg |
| tklib | - | https://core.tcl-lang.org/tklib |
| tkxcursor | - | https://github.com/teclabat/tkxcursor |
| vectcl | - | https://github.com/teclabat/fork-vectcl |

**Tcl90** still in work, but will follow asap ...

Occasionally the package registry might get deleted to save up some storage space. So please don't count on having kept old builds forever.

You can file issues here https://github.com/teclabat/tcltk-binaries/issues but I am not providing general Tcl support, for that I'd recommend https://stackoverflow.com/questions/tagged/tcl

## Liability
All the work presented here was completed during my free time. Please ensure that you comply with all license terms, particularly those specific to each individual package. Any damage resulting from the use of this code and binaries is not my responsibility. I provide no liability nor warranty for this software.

## Windows builds
For Windows builds the `MSYS2` 64bit environment is used (https://www.msys2.org). No installation is necessary, simply extract `.tgz` file and run. For some packages it might be necessary to put `share/lib64` into the executable search path.

## Debian builds
For Debian builds the Ubuntu and Debian distributions are used. A `.deb` file is created and can be installed using `dpkg -i <file>`. The installation goes into `/opt/tcltk<version>`.

## RPM builds
For RPM builds the RedHat distributions are used. A `.rpm` file is created and can be installed using `rpm -i <file>`. The installation goes into `/opt/tcltk<version>`.
