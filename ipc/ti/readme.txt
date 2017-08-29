
http://processors.wiki.ti.com/index.php/IPC_Users_Guide
http://blog.csdn.net/mantis_1984/article/details/20846781



kernel boot-up parameter
=========================================


kernel
=========================================
#
# Remoteproc drivers
#
CONFIG_REMOTEPROC=y
CONFIG_OMAP_REMOTEPROC=y
CONFIG_OMAP_REMOTEPROC_WATCHDOG=y
# CONFIG_STE_MODEM_RPROC is not set
CONFIG_WKUP_M3_RPROC=y
# CONFIG_PRUSS_REMOTEPROC is not set

#
# Rpmsg drivers
#
CONFIG_RPMSG=y
CONFIG_RPMSG_RPC=y
CONFIG_PM_DEVFREQ=y

Installing Tests
=====================================================
http://processors.wiki.ti.com/index.php/IPC_Install_Guide_Linux

ipc-dir$ make install prefix=<target filesystem>/usr
target# /usr/bin/lad_<device> lad.txt





Slave Binaries
=====================================================
cp IPC_INSTALL_DIR/packages/ti/ipc/tests/bin/ti_platforms_evmOMAPL138_DSP/ <target filesystem>/lib/firmware/


