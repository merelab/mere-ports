# $FreeBSD$

PORTNAME=	mere-auth
PORTVERSION=	0.0.1b
DISTVERSIONPREFIX=v
CATEGORIES=	security
#MASTER_SITES=https://ports.merelab.io/downlaods/mere-auth-${PORTVERSION}.tar.gz

MAINTAINER=	bhuiyan.mohammad.iklash@gmail.com
COMMENT=	Auth library to be used for mere system interface

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYING

LIB_DEPENDS=	libmere-utils.so:x11/mere-utils

USES=		compiler:c++11-lang qmake qt:5
USE_QT=		core \
		buildtools_build

USE_GITHUB=	yes
GH_ACCOUNT=	merelab

.include <bsd.port.mk>
