# $FreeBSD$

# WIP Package, remove / replace all wip instances before submission

PORTNAME=	libgoldilocks
DISTVERSION=	g20200316
CATEGORIES=	wip security
MASTER_SITES=	https://github.com/otrv4/libgoldilocks/

MAINTAINER=	fox@FreeBSD.org
COMMENT=	Library providing the ed448 elliptic curve

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE.txt

USES=		autoreconf gmake libtool pkgconfig
USE_LDCONFIG=	yes

GNU_CONFIGURE=	yes

USE_GITHUB=	yes
GH_ACCOUNT=	otrv4
GH_PROJECT=	libgoldilocks
GH_TAGNAME=	d07cb5b

INSTALL_TARGET?=	install-strip

.include <bsd.port.pre.mk>

# Fixes build failures for FreeBSD 13.0-CURRENT (i386)
# Without this it fails with "error: loop not unrolled" optimization
# attempt by the compiler.
# XXX: Is this an important optimization? Ask the upstream
.if ${OPSYS} == FreeBSD && ${ARCH} == i386 && ${OSVERSION} >= 1300022
CFLAGS+=	-Wno-error=pass-failed
.endif

.include <bsd.port.post.mk>
