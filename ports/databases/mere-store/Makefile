# $FreeBSD$

PORTNAME=	mere-store
DISTVERSIONPREFIX=v
DISTVERSION=	0.0.1b
CATEGORIES=	databases
#MASTER_SITES=	https://store.merelab.io/downlaods/mere-store-${PORTVERSION}.tar.gz

MAINTAINER=	bhuiyan.mohammad.iklash@gmail.com
COMMENT=	Object storage system for mere system interface

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYING

LIB_DEPENDS=    libmere-utils.so:x11/mere-utils

RUN_DEPENDS=    leveldb>=0:databases/leveldb

USES=		compiler:c++11-lang qmake qt:5
USE_QT=		core \
		buildtools_build

USE_GITHUB=	yes
GH_ACCOUNT=	merelab

.include <bsd.port.mk>
