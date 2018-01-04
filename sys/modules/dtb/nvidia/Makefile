# $FreeBSD$
# All the dts files for Nvidia ARM systems we support.
.if ${MACHINE_ARCH} == "armv7"
DTS=	\
	tegra124-jetson-tk1-fbsd.dts
.elif ${MACHINE_ARCH} == "aarch64"
DTS=	\
	nvidia/tegra210-p2371-2180-fbsd.dts
.endif
.include <bsd.dtb.mk>
