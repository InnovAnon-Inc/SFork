# Install the pkg-config file.
pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = src/libsfork.pc

DISTCLEANFILES = $(pkgconfig_DATA)
EXTRA_DIST = src/libsfork.pc.in

SUBDIRS = src
dist_doc_DATA = README.md
ACLOCAL_AMFLAGS = -I m4

