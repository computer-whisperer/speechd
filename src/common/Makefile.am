#
# Copyright (C) 2002 - 2018 Brailcom, o.p.s.
#
# This is free software; you can redistribute it and/or modify it
# under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2, or (at your option)
# any later version.
#
# This software is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this package; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor,
# Boston, MA 02110-1301, USA.
#

## Process this file with automake to produce Makefile.in

noinst_LTLIBRARIES = libcommon.la
libcommon_la_CFLAGS = $(ERROR_CFLAGS) $(GLIB_CFLAGS) \
-DGETTEXT_PACKAGE=\"$(GETTEXT_PACKAGE)\" -DLOCALEDIR=\"$(localedir)\"
libcommon_la_CPPFLAGS = "-I$(top_srcdir)/include/" $(GLIB_CFLAGS)
libcommon_la_LIBADD = $(GLIB_LIBS)
libcommon_la_SOURCES = fdsetconv.c spd_getline.c i18n.c


-include $(top_srcdir)/git.mk
