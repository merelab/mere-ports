# $FreeBSD$

PORTNAME=       mere-about
PORTVERSION=	0.0.1b
PORTREVISION=	1
CATEGORIES=     x11
#MASTER_SITES=	https://ports.merelab.io/downlaods/mere-about-${PORTVERSION}.tar.gz

MAINTAINER=     bhuiyan.mohammad.iklash@gmail.com
COMMENT= 	About me, mere!

LICENSE=     	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYING

USES=		compiler:c++11-lang qmake qt:5
USE_QT=		core gui widgets \
		buildtools_build linguisttools_build

USE_GL+=	gl

USE_GITHUB=	yes
GH_ACCOUNT=	merelab
GH_PROJECT=	mere-about
GH_TAGNAME=	v0.0.1b

#WRKSRC=         ${WRKDIR}/${PORTNAME}-${PORTVERSION}

OPTIONS_DEFINE=INSTALL_AS_USER

.include <bsd.port.mk>
