# Created by: James Luck <jamie.delucks@gmail.com>
# $FreeBSD$

PORTNAME=	AnyEvent-DateTime-Cron
PORTVERSION=	0.08
CATEGORIES=	devel perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	jamie.delucks@gmail.com
COMMENT=	AnyEvent crontab with DateTime::Event::Cron

BUILD_DEPENDS=	\
		p5-Module-Build>=0.3601:${PORTSDIR}/devel/p5-Module-Build \
		p5-AnyEvent>=0:${PORTSDIR}/devel/p5-AnyEvent \
		p5-DateTime>=0:${PORTSDIR}/devel/p5-DateTime \
		p5-DateTime-Event-Cron>=0:${PORTSDIR}/devel/p5-DateTime-Event-Cron \
		p5-DateTime-Event-Cron-Quartz>=0:${PORTSDIR}/devel/p5-DateTime-Event-Cron-Quartz

RUN_DEPENDS:=	${BUILD_DEPENDS}

USES=		perl5
USE_PERL5=	configure

MAN3=		%%PERL5_MAN3%%/AnyEvent::DateTime::Cron

.include <bsd.port.mk>
