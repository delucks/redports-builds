# Created by: James Luck <jluck@udel.edu>
# $FreeBSD$

PORTNAME=	SOAP-XML-Client
PORTVERSION=	2.7
CATEGORIES=	devel perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	jluck@udel.edu
COMMENT=	Simple Perl framework for talking with SOAP web services

BUILD_DEPENDS=	p5-ExtUtils-MakeMaker>=0:${PORTSDIR}/devel/p5-ExtUtils-MakeMaker

RUN_DEPENDS:=	${BUILD_DEPENDS} \
		p5-Carp>=0:${PORTSDIR}/devel/p5-Carp \
		p5-Class-Accessor-Fast-XS>=0:${PORTSDIR}/devel/p5-Class-Accessor-Fast-XS \
		p5-Encode>=0:${PORTSDIR}/converters/p5-Encode \
		p5-File-Slurp>=0:${PORTSDIR}/devel/p5-File-Slurp \
		p5-SOAP-Data-Builder>=0.8:${PORTSDIR}/net/p5-SOAP-Data-Builder \
		p5-SOAP-Lite>=0.67:${PORTSDIR}/net/p5-SOAP-Lite \
		p5-Scalar-List-Utils>=0:${PORTSDIR}/lang/p5-Scalar-List-Utils \
		p5-XML-LibXML>=0:${PORTSDIR}/textproc/p5-XML-LibXML

USES=		perl5
USE_PERL5=	configure

.include <bsd.port.mk>
