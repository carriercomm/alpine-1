## Process this file with automake to produce Makefile.in
## Use aclocal -I m4; automake

# ========================================================================
# Copyright 2006 University of Washington
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# ========================================================================

noinst_LIBRARIES = libpineosd.a

libpineosd_a_SOURCES = chnge_pw.c debuging.c diskquot.non.c execview.c fltrname.c \
	jobcntrl.c print.c termin.gen.c termin.unx.c termout.gen.c termout.unx.c \
	debuging.h execview.h fltrname.h jobcntrl.h print.h resource.h termin.gen.h \
	termin.unx.h termout.gen.h termout.unx.h windlg.h

AM_CPPFLAGS = -I$(top_builddir)/include -I$(top_srcdir)/include
