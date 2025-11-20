This is the Tcl/Tk binary repository which I dedicate to the Tcl community.
The package sources are updated once a week, and on compile success the binaries uploaded here https://gitlab.com/teclabat/tcltk/-/packages.

**Tcl86** contains the following packages: tcl tk tcllib tklib thread tcltls tkimg tbcload tkcon gse bwidget tdbc tdbcodbc tdbcpostgres tdbcmysql tdbcsqlite3 tcludp vectcl photoresize fftw sqlite3 rl_json snmptools;

**Tcl86 Now with new modified `rl_json` package:** https://gitlab.com/teclabat/rl_json

**Tcl86 now comes with `snmptools` package compiled with libraries from `net-snmp`.**

**Tcl90** has a reduced package set since not all libraries are compile clean for the new API: tcl tk tcllib tklib thread tkimg tkcon gse bwidget tdbc tdbcodbc tdbcpostgres tdbcmysql tdbcsqlite3; If a package fails to compile, I might remove it temporarily ... you might observe fluctuation.
Also the new configure script requires `autoconf` 2.72 (latest greatest) which break compilation on older platforms. Anyhow I managed to compile on Debian 12 and Windows, but Ubuntu 20/22/RHEL9 I am going to abandon.

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
