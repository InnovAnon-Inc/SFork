AM_CPPFLAGS = -D__STDC_INT64__

#if USE_SUBMODULES
#SUBDIRS = ../glitter
#AM_CPPFLAGS += -I $(top_srcdir)/glitter/src
#endif

#include Makefile-LIBADD.inc
dist_bin_SCRIPTS = libsfork_config

lib_LTLIBRARIES = libsfork.la
include_HEADERS = sfork.h
libsfork_la_LIBADD = @LIBSFORK_LIBADD@
