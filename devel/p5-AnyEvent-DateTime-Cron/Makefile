# Created by: James Luck <jluck@udel.edu>
# $FreeBSD$

PORTNAME=	AnyEvent-DateTime-Cron
PORTVERSION=	0.08
CATEGORIES=	devel perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	jluck@udel.edu
COMMENT=	AnyEvent crontab with DateTime::Event::Cron

RUN_DEPENDS=	\
		p5-AnyEvent>=0:${PORTSDIR}/devel/p5-AnyEvent \
		p5-DateTime>=0:${PORTSDIR}/devel/p5-DateTime \
		p5-DateTime-Event-Cron>=0:${PORTSDIR}/devel/p5-DateTime-Event-Cron \
		p5-DateTime-Event-Cron-Quartz>=0:${PORTSDIR}/devel/p5-DateTime-Event-Cron-Quartz

USES=		perl5
USE_PERL5=	modbuild

.include <bsd.port.mk>
