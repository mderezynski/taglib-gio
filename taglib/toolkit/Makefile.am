INCLUDES = \
	-I$(top_srcdir)/taglib \
	$(GIO_CFLAGS)
	$(all_includes)

noinst_LTLIBRARIES = libtoolkit.la

libtoolkit_la_SOURCES = \
	tstring.cpp tstringlist.cpp tbytevector.cpp \
	tbytevectorlist.cpp tfile.cpp tdebug.cpp unicode.cpp

taglib_include_HEADERS = 	\
		taglib-gio.h		\
		tbytevector.h		\
		tbytevectorlist.h	\
		tdebug.h			\
		tfile.h				\
		tlist.h				\
		tlist.tcc			\
		tmap.h				\
		tmap.tcc			\
		tstring.h			\
		tstringlist.h		\
		unicode.h

taglib_includedir = $(includedir)/taglib-gio
