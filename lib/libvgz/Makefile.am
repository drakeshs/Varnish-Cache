#
AM_LDFLAGS  = $(AM_LT_LDFLAGS)

pkglib_LTLIBRARIES = libvgz.la

libvgz_la_LDFLAGS = $(AM_LDFLAGS) -avoid-version
libvgz_la_CFLAGS = -D_LARGEFILE64_SOURCE=1 -DZLIB_CONST $(libvgz_extra_cflags)

libvgz_la_SOURCES = \
	adler32.c \
	compress.c \
	crc32.c \
	crc32.h \
	deflate.c \
	deflate.h \
	gzguts.h \
	infback.c \
	inffast.c \
	inffast.h \
	inffixed.h \
	inflate.c \
	inflate.h \
	inftrees.c \
	inftrees.h \
	trees.c \
	trees.h \
	uncompr.c \
	zconf.h \
	vgz.h \
	zutil.c \
	zutil.h
