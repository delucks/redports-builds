# Created by: James Luck <jamie.delucks@gmail.com>
# $FreeBSD$

PORTNAME=	DateTime-Event-Cron-Quartz
PORTVERSION=	0.05
CATEGORIES=	devel perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	jamie.delucks@gmail.com
COMMENT=	OpenSymphony Quartz cron expression processor

BUILD_DEPENDS=	\
		p5-ExtUtils-MakeMaker>=0:${PORTSDIR}/devel/p5-ExtUtils-MakeMaker \
		p5-Class-Accessor>=0.33:${PORTSDIR}/devel/p5-Class-Accessor \
		p5-DateTime>=0.5:${PORTSDIR}/devel/p5-DateTime \
		p5-Exception-Class>=1.29:${PORTSDIR}/devel/p5-Exception-Class \
		p5-Readonly>=1.03:${PORTSDIR}/devel/p5-Readonly

RUN_DEPENDS:=	${BUILD_DEPENDS}

USES=		perl5
USE_PERL5=	configure

.include <bsd.port.mk>
