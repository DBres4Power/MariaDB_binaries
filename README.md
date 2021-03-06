# MariaDB_binaries
Based on MariaDB Community Source，build and verify  tarball/ RPM binaries for Power (Linux ppc64/ppc64le), release binaries for popular versions.

# 说明
本仓库从社区下载MariaDB主流源码版本，维护MariaDB on Power上经过优化、验证的编译脚本， 并在Releases/Tags中提供编译好的二进制RPM或者TARBALL 软件包.
 
# 示例
* [scripts/src/10.3.27/GET_SOURCE.links.sh](https://github.com/DBres4Power/MariaDB_binaries/blob/main/scripts/src/10.3.27/GET_SOURCE.links.sh) ，内容是下载MariaDB 10.3.27源码的链接
 
* [scripts/build_on_rhel7_by_devtoolset/10.3.27/README.BUILD.RPMS.txt](https://github.com/DBres4Power/MariaDB_binaries/blob/build/scripts/build_on_rhel7_by_devtoolset/10.3.27/README.BUILD.RPMS.txt) 在RedHat/CentOS 7下采用devtoolset gcc编译MariaDB 10.3.27二进制RPM包的过程

* [scripts/build_on_rhel7_by_devtoolset/10.3.27/README.BUILD.TAR.txt](https://github.com/DBres4Power/MariaDB_binaries/blob/build/scripts/build_on_rhel7_by_devtoolset/10.3.27/README.BUILD.TAR.txt) 在RedHat/CentOS 7下采用devtoolset gcc编译MariaDB 10.3.27二进制TAR包的过程

* [Releases/Tags v10.3.27_built_on_rhel7_by_devtoolset](https://github.com/DBres4Power/MariaDB_binaries/releases/tag/v10.3.27_built_on_rhel7_by_devtoolset) 提供在RedHat/CentOS 7下采用devtoolset gcc编译好的MariaDB 10.3.27二进制RPM或者TARBALL 软件包

* 因Linux系统自带gcc版本都比较老，因此采用较新的devtoolset gcc，以便能充分发挥软/硬件新功能和特性；有些还还提供了用Advanced Toolchain编译的脚本和软件包

* 将视需求不断新增其他发行Linux版本下各MariaDB主流版本软件包
