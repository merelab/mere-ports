# $FreeBSD$

PORTNAME=       mere-utils
PORTVERSION=	0.0.1b
PORTREVISION=	1
CATEGORIES=     x11
#MASTER_SITES=	https://ports.merelab.io/downlaods/mere-utils-${PORTVERSION}.tar.gz

MAINTAINER=     bhuiyan.mohammad.iklash@gmail.com
COMMENT=	Utility bundle for mere system interface

LICENSE=     	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYING

USES=		compiler:c++11-lang qmake qt:5
USE_QT=		core \
		buildtools_build

USE_XORG=	x11

USE_GITHUB=	yes
GH_ACCOUNT=	merelab
GH_PROJECT=	mere-utils
GH_TAGNAME=	v0.0.1b

#WRKSRC=         ${WRKDIR}/${PORTNAME}-${PORTVERSION}

.include <bsd.port.mk>
