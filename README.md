This is the Tcl/Tk binary repository which I dedicate to the Tcl community.
The package sources are updated once a week, and on compile success the binaries uploaded here: https://github.com/teclabat/tcltk-binaries/releases

**Tcl86** contains the following packages:

| Package | Branch | Repository | Description |
|---------|--------|------------|-------------|
| bwidget | - | https://core.tcl-lang.org/bwidget | High-level Widget Set for Tcl/Tk built using native Tcl/Tk namespaces. |
| critcl | - | https://github.com/andreas-kupries/critcl | Build C extension packages for Tcl on the fly from C code embedded in Tcl scripts. |
| curl | - | https://github.com/teclabat/fork-tclcurl | Tcl interface to libcurl for URL operations with HTTP, FTP, and more. Not included in Ubuntu Focal since it fails to build. |
| fftw | - | https://github.com/teclabat/tclffts | High-performance interface to FFTW3 library for Fast Fourier Transform operations. |
| itcl | itcl-4-0-6-rc | https://core.tcl-lang.org/itcl | Object oriented extension for Tcl. |
| itk | itk-4-0-2-rc | https://core.tcl-lang.org/itk | Framework for building composite mega-widgets using [incr Tcl] classes. |
| iwidgets | - | https://core.tcl-lang.org/iwidgets | Widget collection for itk4. |
| ntcan | - | https://github.com/teclabat/tclntcan | Tcl bindings to ESD NTCAN API for CAN bus communication. |
| parseargs | wip | https://github.com/teclabat/fork-parseargs | Core-style argument parsing for scripts. |
| performance | - | https://github.com/teclabat/tclperformance | High-performance cryptographic operations (XOR cipher). |
| photoresize | - | https://github.com/auriocus/photoresize | Extension to resize and resample photo images with high-quality antialiasing. |
| rljson | wip | https://github.com/teclabat/fork-rljson | JSON parser and generator with native Tcl_Obj type. |
| rsvisa | - | https://github.com/teclabat/tclrsvisa | Interface to VISA library for test and measurement instrument control. |
| ruff | - | https://github.com/teclabat/fork-tclruff | Documentation generator for Tcl using runtime introspection. |
| snmptools | - | https://github.com/teclabat/fork-snmptools | Sample TEA extension demonstrating the Tcl Extension Architecture. |
| ssh2 | - | https://github.com/teclabat/fork-ssh2 | Provide SSH2 connectivity through libssh2.|
| tbcload | - | https://github.com/teclabat/fork-tbcload | Loads Tcl byte code compiled by tclcompiler. |
| tcl | core-8-6-branch | https://core.tcl-lang.org/tcl | Tool Command Language (Tcl) scripting language. |
| tclcompiler | - | https://github.com/teclabat/fork-tclcompiler | Compiles Tcl scripts into byte code format. |
| tclconfig | - | https://core.tcl-lang.org/tclconfig | Building blocks for Tcl Extension Architecture (TEA). |
| tcllib | - | https://core.tcl-lang.org/tcllib | Collection of Tcl packages providing utility functions. |
| tdbc | - | https://core.tcl-lang.org/tdbc | Base classes and SQL tokenizer for Tcl Database Connectivity. |
| tdbcmysql | - | https://core.tcl-lang.org/tdbcmysql | TDBC driver for MySQL databases. |
| tdbcodbc | - | https://core.tcl-lang.org/tdbcodbc | TDBC driver for ODBC (Open Database Connectivity). |
| tdbcpostgres | - | https://core.tcl-lang.org/tdbcpostgres | TDBC driver for PostgreSQL databases. |
| tdbcsqlite3 | - | https://core.tcl-lang.org/tdbcsqlite3 | TDBC driver for SQLite3 databases. |
| tdom | - | https://www.tdom.org/index.html | XML/DOM/XPath/XSLT/HTML/JSON implementation for Tcl. |
| thread | thread-2-8-branch | https://core.tcl-lang.org/thread | Script-level access to Tcl threading capabilities. |
| tk | core-8-6-branch | https://core.tcl-lang.org/tk | Graphical user interface toolkit for Tcl. |
| tkcon | - | https://github.com/teclabat/fork-tkcon | Enhanced Tk console for all platforms. |
| tkimg | trunk | https://sourceforge.net/p/tkimg | Collection of image format handlers for Tk photo image type. |
| tklib | - | https://core.tcl-lang.org/tklib | Collection of Tk packages providing utility functions. |
| tls | tls-2.0 | https://core.tcl-lang.org/tcltls | SSL and TLS encryption over TCP using OpenSSL. |
| udp | wip | https://github.com/teclabat/fork-tcludp | UDP socket support for Tcl. |
| vectcl | - | https://github.com/teclabat/fork-vectcl | Numerical array extension with support for vectors, matrices and tensors. |
| xcursor | - | https://github.com/teclabat/tkxcursor | Support for X Cursor library cursor files in Tk applications. |

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
