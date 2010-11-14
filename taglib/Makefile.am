SUBDIRS = toolkit mpeg ogg flac ape mpc

INCLUDES = \
	-I$(top_srcdir)/taglib \
	-I$(top_srcdir)/taglib/toolkit \
	-I$(top_srcdir)/taglib/mpeg \
	-I$(top_srcdir)/taglib/ogg \
	-I$(top_srcdir)/taglib/ogg/flac \
	-I$(top_srcdir)/taglib/flac \
	-I$(top_srcdir)/taglib/mpc \
	-I$(top_srcdir)/taglib/ogg/vorbis \
	$(all_includes)

lib_LTLIBRARIES = libtag-gio.la

libtag_gio_la_SOURCES = tag.cpp fileref.cpp audioproperties.cpp
taglib_include_HEADERS = tag.h taglib_export.h fileref.h audioproperties.h
taglib_includedir = $(includedir)/taglib-gio

libtag_gio_la_LDFLAGS = $(all_libraries) -no-undefined -version-info 5:0:4
libtag_gio_la_LIBADD = ./mpeg/libmpeg.la ./ogg/libogg.la ./flac/libflac.la ./mpc/libmpc.la ./ape/libape.la ./toolkit/libtoolkit.la
