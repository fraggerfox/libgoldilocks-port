# $FreeBSD$

PORTNAME=	libgoldilocks
PORTVERSION=	0.0.0
CATEGORIES=	security
MASTER_SITES=	https://github.com/otrv4/libgoldilocks/

MAINTAINER=	santhosh.raju@gmail.com
COMMENT=	Library providing the ed448 elliptic curve

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE.txt

USES=		autoreconf gmake libtool pkgconfig
USE_LDCONFIG=	yes

GNU_CONFIGURE=	yes

USE_GITHUB=	yes
GH_ACCOUNT=	otrv4
GH_PROJECT=	libgoldilocks
GH_TAGNAME=	c8d9940

INSTALL_TARGET?=	install-strip

.include <bsd.port.mk>
