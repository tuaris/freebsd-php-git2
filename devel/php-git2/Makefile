# $FreeBSD$

PORTNAME=	php-git2
PORTVERSION=	0.1.1.20190924
PKGNAMEPREFIX=	${PHP_PKGNAMEPREFIX}
CATEGORIES=	devel

MAINTAINER=	daniel@morante.net
COMMENT=	libgit2 bindings for PHP

LICENSE=	PHP301

LIB_DEPENDS=	libgit2.so:devel/libgit2

USES=		php:ext localbase:ldflags
PHP_MODNAME=	git2

USE_GITHUB=	yes
GH_ACCOUNT=	MagicalTux
GH_PROJECT=	${PORTNAME}
GH_COMMIT=	e083449
GH_TAGNAME=	${GH_COMMIT}

CFLAGS+=        -I${TCL_INCLUDEDIR}
CONFIGURE_ARGS=	--with-system-libgit2

.include <bsd.port.mk>
