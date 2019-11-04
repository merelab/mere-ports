# $FreeBSD$

PORTNAME=       mere-auth
PORTVERSION=	0.0.1b
PORTREVISION=	1
CATEGORIES=     x11
#MASTER_SITES=	https://ports.merelab.io/downlaods/mere-auth-${PORTVERSION}.tar.gz

MAINTAINER=     bhuiyan.mohammad.iklash@gmail.com
COMMENT= 	Auth library to be used for mere system interface

LICENSE=     	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYING

LIB_DEPENDS=	libmere-utils.so:x11/mere-utils

USES=		compiler:c++11-lang qmake qt:5
USE_QT=		core \
		buildtools_build

USE_GITHUB=	yes
GH_ACCOUNT=	merelab
GH_PROJECT=	mere-auth
GH_TAGNAME=	v0.0.1b

#WRKSRC=         ${WRKDIR}/${PORTNAME}-${PORTVERSION}

.include <bsd.port.mk>
