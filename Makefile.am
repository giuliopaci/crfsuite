# $Id$

SUBDIRS = include lib/cqdb lib/crf frontend swig

docdir = $(prefix)/share/doc/@PACKAGE@
doc_DATA = README INSTALL COPYING AUTHORS ChangeLog

EXTRA_DIST = \
	crfsuite.sln \
	autogen.sh \
	win32/stdint.h \
	win32/inttypes.h \
	example/crfutils.py \
	example/template.py \
	example/pos.py \
	example/ner.py \
	example/chunking.py \
	CMakeLists.txt \
	crfsuiteConfig.cmake.in \
	crfsuiteConfigVersion.cmake.in

AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4
