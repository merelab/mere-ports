# $FreeBSD$

PORTNAME=	mere-config-lite
DISTVERSIONPREFIX=v
DISTVERSION=	0.0.1b
CATEGORIES= 	devel	
#MASTER_SITES=	https://ports.merelab.io/downlaods/mere-config-lite-${PORTVERSION}.tar.gz

MAINTAINER=	bhuiyan.mohammad.iklash@gmail.com
COMMENT= 	A lightweight configuration library 	

LICENSE=	BSD2CLAUSE
LICENSE_FILE=	${WRKSRC}/LICENSE

LIB_DEPENDS=    libmere-utils.so:x11/mere-utils

USES=		compiler:c++11-lang qmake qt:5
USE_QT=		core \
		buildtools_build

USE_GITHUB=	yes
GH_ACCOUNT=	merelabs

.include <bsd.port.mk>
