This is the Tcl/Tk binary repository, dedicated to the Tcl community.\
- Packages pulled from their main source (e.g. core.tcl-lang.org) are updated once a week.
- The *fork-...* sources must be updated manually since they contain custom enhancements; these will then be included in upcoming builds.

Package origin, branch, and pull date can be traced in the *share/documents/origins* file.\
On successful compilation, binaries are uploaded here: https://github.com/teclabat/tcltk-binaries/releases

**Tcl86 and Tcl9** include the following packages. A dash indicates that the package is not bound to a dedicated branch and is instead pulled from the default branch.

| Package | B8 | B9 | Repository | Description |
|---------|----------------|----------------|------------|-------------|
| bwidget | - | - | https://core.tcl-lang.org/bwidget | High-level Widget Set for Tcl/Tk built using native Tcl/Tk namespaces. |
| critcl | - | - | https://github.com/andreas-kupries/critcl | Build C extension packages for Tcl on the fly from C code embedded in Tcl scripts. |
| curl | - | - | https://github.com/teclabat/fork-tclcurl | Tcl interface to libcurl for URL operations with HTTP, FTP, and more. |
| fftw | - | n/a | https://github.com/teclabat/tclfftw | High-performance interface to FFTW3 library for Fast Fourier Transform operations. |
| itcl | itcl-4-0-6-rc | n/a | https://core.tcl-lang.org/itcl | Object oriented extension for Tcl. |
| itk | itk-4-0-2-rc | n/a | https://core.tcl-lang.org/itk | Framework for building composite mega-widgets using [incr Tcl] classes. |
| iwidgets | - | n/a | https://core.tcl-lang.org/iwidgets | Widget collection for itk4. |
| nats | - | - | https://github.com/teclabat/fork-nats-tcl | Tcl client library for the NATS messaging system. |
| parseargs | - | - | https://github.com/teclabat/fork-parseargs | Argument parsing for Tcl scripts. |
| performance | - | - | https://github.com/teclabat/tclperformance | High-performance XOR operations. |
| photoresize | - | - | https://github.com/teclabat/fork-photoresize | Extension to resize and resample photo images with high-quality antialiasing. |
| rl_json | - | - | https://github.com/teclabat/fork-rljson | JSON parser and generator with native Tcl_Obj type. |
| rsvisa | - | n/a | https://github.com/teclabat/tclrsvisa | Interface to VISA library for test and measurement instrument control. |
| ruff | - | n/a | https://github.com/teclabat/fork-tclruff | Documentation generator for Tcl using runtime introspection. |
| snmptools | - | n/a | https://github.com/teclabat/fork-snmptools | SNMP tools built using the Tcl Extension Architecture. |
| ssh2 | - | - | https://github.com/teclabat/fork-tclssh2 | Provide SSH2 connectivity through libssh2. |
| tbcload | - | - | https://github.com/teclabat/fork-tbcload | Loads Tcl byte code compiled by tclcompiler. |
| tcl | core-8-6-branch | core-9-0-branch | [https://core.tcl-lang.org/tcl](https://core.tcl-lang.org/tcl/timeline?r=core-8-6-branch) | Tool Command Language (Tcl) scripting language. |
| tclcompiler | - | n/a | https://github.com/teclabat/fork-tclcompiler | Compiles Tcl scripts into byte code format. |
| tcllib | - | - | https://core.tcl-lang.org/tcllib | Collection of Tcl packages providing utility functions. |
| tdbc | - | - | https://core.tcl-lang.org/tdbc | Base classes and SQL tokenizer for Tcl Database Connectivity. |
| tdbcmysql | - | - | https://core.tcl-lang.org/tdbcmysql | TDBC driver for MySQL databases. |
| tdbcodbc | 4ced1c9409* | 4ced1c9409* | https://core.tcl-lang.org/tdbcodbc | TDBC driver for ODBC (Open Database Connectivity). |
| tdbcpostgres | 48bec53fd0* | 48bec53fd0* | https://core.tcl-lang.org/tdbcpostgres | TDBC driver for PostgreSQL databases. |
| tdbcsqlite3 | - | - | https://core.tcl-lang.org/tdbcsqlite3 | TDBC driver for SQLite3 databases. |
| tdom | - | - | https://www.tdom.org/index.html | XML/DOM/XPath/XSLT/HTML/JSON implementation for Tcl. |
| thread | thread-2-8-branch | - | [https://core.tcl-lang.org/thread](https://core.tcl-lang.org/thread/timeline?r=thread-2-8-branch) | Script-level access to Tcl threading capabilities. |
| tk | core-8-6-branch | core-9-0-branch | [https://core.tcl-lang.org/tk](https://core.tcl-lang.org/tk/timeline?r=core-8-6-branch) | Graphical user interface toolkit for Tcl. |
| tkcon | - | - | https://github.com/teclabat/fork-tkcon | Enhanced Tk console for all platforms. |
| tkimg | - | - | https://sourceforge.net/p/tkimg | Collection of image format handlers for Tk photo image type. |
| tklib | - | - | https://core.tcl-lang.org/tklib | Collection of Tk packages providing utility functions. |
| tktable | - | - | https://github.com/teclabat/fork-tktable | A table/matrix widget extension to Tcl/Tk. |
| tls | - | - | https://core.tcl-lang.org/tcltls | SSL and TLS encryption over TCP using OpenSSL. |
| tnm | - | - | https://github.com/teclabat/fork-scotty | Scotty Tcl extension for network management. |
| udp | - | n/a | https://github.com/teclabat/fork-tcludp | UDP socket support for Tcl. |
| vectcl | - | n/a | https://github.com/teclabat/fork-vectcl | Numerical array extension with support for vectors, matrices and tensors. |
| xcursor | - | - | https://github.com/teclabat/tkxcursor | Support for X Cursor library cursor files in Tk applications. |

**Tcl90** support is in progress. Packages marked with `n/a` in the Tcl 9 column are not yet migrated (and itcl stuff never will be).\
* Marked items are bound to a commit-id because of an ongoing issue.\
B8, B9 = Branch TCL8/9.\

Old releases may be removed periodically to save storage space.

You can file issues here: https://github.com/teclabat/tcltk-binaries/issues. Note that I do not provide general Tcl support; for that I recommend https://stackoverflow.com/questions/tagged/tcl.

## Liability
All the work presented here was completed during my free time. Please ensure that you comply with all license terms, particularly those specific to each individual package. Any damage resulting from the use of this code and binaries is not my responsibility. I provide no warranty and accept no liability for this software.

## Windows builds
For Windows builds the `MSYS2` 64bit environment is used (https://www.msys2.org). No installation is necessary, simply extract the `.tgz` file and run. For some packages it might be necessary to put `share/lib64` into the executable search path.

## Debian builds
For Debian builds the Ubuntu and Debian distributions are used. A `.deb` file is created and can be installed using `dpkg -i <file>`. The installation goes into `/opt/tcltk<version>`.

## RPM builds
For RPM builds the RedHat distributions are used. A `.rpm` file is created and can be installed using `rpm -i <file>`. The installation goes into `/opt/tcltk<version>`.
