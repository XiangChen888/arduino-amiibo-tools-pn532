AM_CFLAGS = -I. -I$(top_srcdir)/libfreefare @LIBNFC_CFLAGS@
AM_LDFLAGS = @LIBNFC_LIBS@

bin_PROGRAMS = ntag2

ntag2_SOURCES = ntag2.c
ntag2_LDADD = $(top_builddir)/libfreefare/libfreefare.la

CLEANFILES=	*.gcno