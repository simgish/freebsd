##
## $P4: //depot/projects/trustedbsd/openbsm/Makefile.am#5 $
##

SUBDIRS =		\
	bsm

if HAVE_AUDIT_SYSCALLS
SUBDIRS +=              \
       	libauditd
endif

SUBDIRS +=              \
	libbsm		\
	bin		\
	man		\
	modules		\
	sys

ACLOCAL_AMFLAGS = -I m4

EXTRA_DIST =		\
	CHANGELOG	\
	LICENSE		\
	README		\
	TODO		\
	VERSION
