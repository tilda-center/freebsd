# $FreeBSD$

.include <src.opts.mk>

PACKAGE=dnctl
PROG=	dnctl
SRCS=	ipfw2.c dummynet.c main.c
WARNS?=	2

LIBADD=	jail util
MAN=	dnctl.8

.include <bsd.prog.mk>
