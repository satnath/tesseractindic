# Makefile.in generated automatically by automake 1.4-p6 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999, 2001 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.


SHELL = /bin/bash

srcdir = .
top_srcdir = ..

prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include/tesseract
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/
pkglibdir = $(libdir)/
pkgincludedir = $(includedir)/

top_builddir = ..

ACLOCAL = /home/debayan/ocr/trunk/config/missing aclocal-1.4
AUTOCONF = /home/debayan/ocr/trunk/config/missing autoconf
AUTOMAKE = /home/debayan/ocr/trunk/config/missing automake-1.4
AUTOHEADER = /home/debayan/ocr/trunk/config/missing autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
host_alias = 
host_triplet = i686-pc-linux-gnu
CC = gcc
CXX = g++
HAVE_LIB = @HAVE_LIB@
LIB = @LIB@
LTLIB = @LTLIB@
MAINT = #
MAKEINFO = /home/debayan/ocr/trunk/config/missing makeinfo
PACKAGE = 
PACKAGE_DATE = 04/22
PACKAGE_NAME = tesseract
PACKAGE_VERSION = 2.03
PACKAGE_YEAR = 2008
RANLIB = ranlib
VERSION = 

SUBDIRS = 
AM_CPPFLAGS =      -I$(top_srcdir)/ccutil -I$(top_srcdir)/ccstruct     -I$(top_srcdir)/image -I$(top_srcdir)/viewer     -I$(top_srcdir)/ccops -I$(top_srcdir)/dict     -I$(top_srcdir)/classify -I$(top_srcdir)/display     -I$(top_srcdir)/wordrec -I$(top_srcdir)/cutil     -I$(top_srcdir)/textord


EXTRA_DIST = training.cpp unicharset_extractor.dsp wordlist2dawg.dsp     cnTraining.dsp mfTraining.dsp     unicharset_extractor.vcproj wordlist2dawg.vcproj     cnTraining.vcproj mfTraining.vcproj


include_HEADERS =      mergenf.h name2char.h training.h


lib_LIBRARIES = libtesseract_training.a
libtesseract_training_a_SOURCES =      name2char.cpp


bin_PROGRAMS = cntraining mftraining unicharset_extractor wordlist2dawg
cntraining_SOURCES = cnTraining.cpp
cntraining_LDADD =      libtesseract_training.a     ../textord/libtesseract_textord.a     ../classify/libtesseract_classify.a     ../dict/libtesseract_dict.a     ../image/libtesseract_image.a     ../cutil/libtesseract_cutil.a     ../ccstruct/libtesseract_ccstruct.a     ../viewer/libtesseract_viewer.a     ../ccutil/libtesseract_ccutil.a

mftraining_SOURCES = mfTraining.cpp mergenf.cpp
mftraining_LDADD =      libtesseract_training.a     ../textord/libtesseract_textord.a     ../classify/libtesseract_classify.a     ../dict/libtesseract_dict.a     ../image/libtesseract_image.a     ../cutil/libtesseract_cutil.a     ../ccstruct/libtesseract_ccstruct.a     ../viewer/libtesseract_viewer.a     ../ccutil/libtesseract_ccutil.a

unicharset_extractor_SOURCES = unicharset_extractor.cpp
unicharset_extractor_LDADD =      ../ccutil/libtesseract_ccutil.a

wordlist2dawg_SOURCES = wordlist2dawg.cpp
wordlist2dawg_LDADD =      ../dict/libtesseract_dict.a     ../cutil/libtesseract_cutil.a     ../ccstruct/libtesseract_ccstruct.a     ../viewer/libtesseract_viewer.a     ../ccutil/libtesseract_ccutil.a

mkinstalldirs = $(SHELL) $(top_srcdir)/config/mkinstalldirs
CONFIG_HEADER = ../config_auto.h
CONFIG_CLEAN_FILES = 
LIBRARIES =  $(lib_LIBRARIES)


DEFS = -DHAVE_CONFIG_H -I. -I$(srcdir) -I..
CPPFLAGS = 
LDFLAGS = 
LIBS = -ltiff -lpthread -ljpeg -lpng -lz  -lm
libtesseract_training_a_LIBADD = 
libtesseract_training_a_OBJECTS =  name2char.o
AR = ar
PROGRAMS =  $(bin_PROGRAMS)

cntraining_OBJECTS =  cnTraining.o
cntraining_DEPENDENCIES =  libtesseract_training.a \
../textord/libtesseract_textord.a ../classify/libtesseract_classify.a \
../dict/libtesseract_dict.a ../image/libtesseract_image.a \
../cutil/libtesseract_cutil.a ../ccstruct/libtesseract_ccstruct.a \
../viewer/libtesseract_viewer.a ../ccutil/libtesseract_ccutil.a
cntraining_LDFLAGS = 
mftraining_OBJECTS =  mfTraining.o mergenf.o
mftraining_DEPENDENCIES =  libtesseract_training.a \
../textord/libtesseract_textord.a ../classify/libtesseract_classify.a \
../dict/libtesseract_dict.a ../image/libtesseract_image.a \
../cutil/libtesseract_cutil.a ../ccstruct/libtesseract_ccstruct.a \
../viewer/libtesseract_viewer.a ../ccutil/libtesseract_ccutil.a
mftraining_LDFLAGS = 
unicharset_extractor_OBJECTS =  unicharset_extractor.o
unicharset_extractor_DEPENDENCIES =  ../ccutil/libtesseract_ccutil.a
unicharset_extractor_LDFLAGS = 
wordlist2dawg_OBJECTS =  wordlist2dawg.o
wordlist2dawg_DEPENDENCIES =  ../dict/libtesseract_dict.a \
../cutil/libtesseract_cutil.a ../ccstruct/libtesseract_ccstruct.a \
../viewer/libtesseract_viewer.a ../ccutil/libtesseract_ccutil.a
wordlist2dawg_LDFLAGS = 
CXXFLAGS =  -g -O2
CXXCOMPILE = $(CXX) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
CXXLD = $(CXX)
CXXLINK = $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) $(LDFLAGS) -o $@
HEADERS =  $(include_HEADERS)

DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = tar
GZIP_ENV = --best
SOURCES = $(libtesseract_training_a_SOURCES) $(cntraining_SOURCES) $(mftraining_SOURCES) $(unicharset_extractor_SOURCES) $(wordlist2dawg_SOURCES)
OBJECTS = $(libtesseract_training_a_OBJECTS) $(cntraining_OBJECTS) $(mftraining_OBJECTS) $(unicharset_extractor_OBJECTS) $(wordlist2dawg_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .S .c .cpp .o .s
$(srcdir)/Makefile.in: # Makefile.am $(top_srcdir)/configure.ac $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu --include-deps training/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


mostlyclean-libLIBRARIES:

clean-libLIBRARIES:
	-test -z "$(lib_LIBRARIES)" || rm -f $(lib_LIBRARIES)

distclean-libLIBRARIES:

maintainer-clean-libLIBRARIES:

install-libLIBRARIES: $(lib_LIBRARIES)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(libdir)
	@list='$(lib_LIBRARIES)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo " $(INSTALL_DATA) $$p $(DESTDIR)$(libdir)/$$p"; \
	    $(INSTALL_DATA) $$p $(DESTDIR)$(libdir)/$$p; \
	  else :; fi; \
	done
	@$(POST_INSTALL)
	@list='$(lib_LIBRARIES)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo " $(RANLIB) $(DESTDIR)$(libdir)/$$p"; \
	    $(RANLIB) $(DESTDIR)$(libdir)/$$p; \
	  else :; fi; \
	done

uninstall-libLIBRARIES:
	@$(NORMAL_UNINSTALL)
	list='$(lib_LIBRARIES)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(libdir)/$$p; \
	done

.c.o:
	$(COMPILE) -c $<

.s.o:
	$(COMPILE) -c $<

.S.o:
	$(COMPILE) -c $<

mostlyclean-compile:
	-rm -f *.o core *.core

clean-compile:

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

libtesseract_training.a: $(libtesseract_training_a_OBJECTS) $(libtesseract_training_a_DEPENDENCIES)
	-rm -f libtesseract_training.a
	$(AR) cru libtesseract_training.a $(libtesseract_training_a_OBJECTS) $(libtesseract_training_a_LIBADD)
	$(RANLIB) libtesseract_training.a

mostlyclean-binPROGRAMS:

clean-binPROGRAMS:
	-test -z "$(bin_PROGRAMS)" || rm -f $(bin_PROGRAMS)

distclean-binPROGRAMS:

maintainer-clean-binPROGRAMS:

install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(bindir)
	@list='$(bin_PROGRAMS)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo "  $(INSTALL_PROGRAM) $$p $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`"; \
	     $(INSTALL_PROGRAM) $$p $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`; \
	  else :; fi; \
	done

uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	list='$(bin_PROGRAMS)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`; \
	done

cntraining: $(cntraining_OBJECTS) $(cntraining_DEPENDENCIES)
	@rm -f cntraining
	$(CXXLINK) $(cntraining_LDFLAGS) $(cntraining_OBJECTS) $(cntraining_LDADD) $(LIBS)

mftraining: $(mftraining_OBJECTS) $(mftraining_DEPENDENCIES)
	@rm -f mftraining
	$(CXXLINK) $(mftraining_LDFLAGS) $(mftraining_OBJECTS) $(mftraining_LDADD) $(LIBS)

unicharset_extractor: $(unicharset_extractor_OBJECTS) $(unicharset_extractor_DEPENDENCIES)
	@rm -f unicharset_extractor
	$(CXXLINK) $(unicharset_extractor_LDFLAGS) $(unicharset_extractor_OBJECTS) $(unicharset_extractor_LDADD) $(LIBS)

wordlist2dawg: $(wordlist2dawg_OBJECTS) $(wordlist2dawg_DEPENDENCIES)
	@rm -f wordlist2dawg
	$(CXXLINK) $(wordlist2dawg_LDFLAGS) $(wordlist2dawg_OBJECTS) $(wordlist2dawg_LDADD) $(LIBS)
.cpp.o:
	$(CXXCOMPILE) -c $<

install-includeHEADERS: $(include_HEADERS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(includedir)
	@list='$(include_HEADERS)'; for p in $$list; do \
	  if test -f "$$p"; then d= ; else d="$(srcdir)/"; fi; \
	  echo " $(INSTALL_DATA) $$d$$p $(DESTDIR)$(includedir)/$$p"; \
	  $(INSTALL_DATA) $$d$$p $(DESTDIR)$(includedir)/$$p; \
	done

uninstall-includeHEADERS:
	@$(NORMAL_UNINSTALL)
	list='$(include_HEADERS)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(includedir)/$$p; \
	done

# This directory's subdirectories are mostly independent; you can cd
# into them and run `make' without going through this Makefile.
# To change the values of `make' variables: instead of editing Makefiles,
# (1) if the variable is set in `config.status', edit `config.status'
#     (which will cause the Makefiles to be regenerated when you run `make');
# (2) otherwise, pass the desired values on the `make' command line.



all-recursive install-data-recursive install-exec-recursive \
installdirs-recursive install-recursive uninstall-recursive  \
check-recursive installcheck-recursive info-recursive dvi-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	target=`echo $@ | sed s/-recursive//`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    dot_seen=yes; \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

mostlyclean-recursive clean-recursive distclean-recursive \
maintainer-clean-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	rev=''; list='$(SUBDIRS)'; for subdir in $$list; do \
	  rev="$$subdir $$rev"; \
	  test "$$subdir" != "." || dot_seen=yes; \
	done; \
	test "$$dot_seen" = "no" && rev=". $$rev"; \
	target=`echo $@ | sed s/-recursive//`; \
	for subdir in $$rev; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done && test -z "$$fail"
tags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) tags); \
	done

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS: tags-recursive $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
   if test "$$subdir" = .; then :; else \
	    test -f $$subdir/TAGS && tags="$$tags -i $$here/$$subdir/TAGS"; \
   fi; \
	done; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags -o $$here/TAGS $(ETAGS_ARGS) $$tags  $$unique $(LISP))

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(top_builddir)/$(PACKAGE_NAME)-$(PACKAGE_VERSION)/$(subdir)

subdir = training

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
	for subdir in $(SUBDIRS); do \
	  if test "$$subdir" = .; then :; else \
	    test -d $(distdir)/$$subdir \
	    || mkdir $(distdir)/$$subdir \
	    || exit 1; \
	    chmod 777 $(distdir)/$$subdir; \
	    (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir=../$(top_distdir) distdir=../$(distdir)/$$subdir distdir) \
	      || exit 1; \
	  fi; \
	done
cnTraining.o: cnTraining.cpp ../cutil/oldlist.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../cutil/efio.h ../cutil/emalloc.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../classify/featdefs.h \
	../classify/ocrfeatures.h ../cutil/funcdefs.h \
	../ccutil/tessclas.h ../classify/fxdefs.h ../cutil/general.h \
	../ccutil/tessopt.h ../ccutil/notdll.h \
	../classify/ocrfeatures.h ../cutil/general.h \
	../classify/clusttool.h ../ccutil/host.h ../classify/cluster.h \
	../classify/kdtree.h ../cutil/cutil.h ../cutil/oldlist.h \
	../classify/cluster.h name2char.h ../dict/matchdefs.h \
	../cutil/general.h ../ccutil/unichar.h ../ccutil/unichar.h
mergenf.o: mergenf.cpp mergenf.h ../classify/protos.h ../cutil/bitvec.h \
	../cutil/cutil.h ../cutil/general.h ../ccutil/host.h \
	../ccutil/platform.h ../ccutil/unichar.h ../classify/cluster.h \
	../classify/kdtree.h ../cutil/general.h \
	../classify/ocrfeatures.h ../cutil/funcdefs.h \
	../ccutil/tessclas.h ../classify/fxdefs.h ../cutil/oldlist.h \
	../cutil/cutil.h ../classify/ocrfeatures.h training.h \
	../ccutil/host.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../cutil/general.h ../cutil/efio.h ../classify/clusttool.h \
	../ccutil/host.h ../classify/cluster.h ../cutil/oldlist.h \
	../cutil/minmax.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/oldlist.h ../cutil/callcpp.h ../cutil/const.h \
	../classify/featdefs.h ../classify/intproto.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	../classify/protos.h ../cutil/callcpp.h ../ccutil/unicharset.h \
	../ccutil/unichar.h ../ccutil/unicharmap.h
mfTraining.o: mfTraining.cpp ../cutil/oldlist.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../cutil/efio.h ../cutil/emalloc.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../classify/featdefs.h \
	../classify/ocrfeatures.h ../cutil/funcdefs.h \
	../ccutil/tessclas.h ../classify/fxdefs.h ../cutil/general.h \
	../ccutil/tessopt.h ../ccutil/notdll.h \
	../classify/ocrfeatures.h ../classify/mf.h ../cutil/general.h \
	../classify/clusttool.h ../ccutil/host.h ../classify/cluster.h \
	../classify/kdtree.h ../cutil/cutil.h ../cutil/oldlist.h \
	../classify/cluster.h ../classify/protos.h ../cutil/bitvec.h \
	../ccutil/unichar.h ../cutil/minmax.h ../cutil/debug.h \
	../cutil/variables.h ../cutil/oldlist.h ../ccutil/tprintf.h \
	../ccutil/varable.h ../cutil/const.h mergenf.h training.h \
	../ccutil/host.h ../cutil/callcpp.h name2char.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	../classify/intproto.h ../dict/matchdefs.h ../classify/protos.h \
	../cutil/callcpp.h ../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h ../cutil/variables.h ../cutil/freelist.h \
	../cutil/danerror.h ../cutil/globals.h ../ccutil/tessclas.h \
	../cutil/const.h ../ccutil/unicharset.h ../ccutil/strngs.h
name2char.o: name2char.cpp name2char.h ../dict/matchdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/unichar.h ../cutil/danerror.h
training.o: training.cpp training.h ../ccutil/host.h ../config_auto.h \
	../ccutil/platform.h ../cutil/callcpp.h ../ccutil/host.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/cutil.h ../cutil/general.h ../cutil/oldlist.h \
	../cutil/callcpp.h ../ccutil/memry.h ../viewer/grphics.h \
	../viewer/sbgdefs.h ../viewer/sbgconst.h ../ccutil/host.h \
	../viewer/evnts.h ../viewer/grphics.h
unicharset_extractor.o: unicharset_extractor.cpp ../config_auto.h \
	../ccutil/unichar.h ../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h ../ccutil/strngs.h ../ccutil/memry.h \
	../ccutil/host.h ../ccutil/platform.h ../ccutil/serialis.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/boxread.h \
	../ccutil/tessopt.h ../ccutil/notdll.h
wordlist2dawg.o: wordlist2dawg.cpp ../dict/dawg.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h ../dict/makedawg.h \
	../dict/dawg.h ../dict/trie.h ../cutil/cutil.h \
	../cutil/general.h ../dict/reduce.h ../cutil/emalloc.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h

info-am:
info: info-recursive
dvi-am:
dvi: dvi-recursive
check-am: all-am
check: check-recursive
installcheck-am:
installcheck: installcheck-recursive
install-exec-am: install-libLIBRARIES install-binPROGRAMS
install-exec: install-exec-recursive

install-data-am: install-includeHEADERS
install-data: install-data-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-recursive
uninstall-am: uninstall-libLIBRARIES uninstall-binPROGRAMS \
		uninstall-includeHEADERS
uninstall: uninstall-recursive
all-am: Makefile $(LIBRARIES) $(PROGRAMS) $(HEADERS)
all-redirect: all-recursive
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs: installdirs-recursive
installdirs-am:
	$(mkinstalldirs)  $(DESTDIR)$(libdir) $(DESTDIR)$(bindir) \
		$(DESTDIR)$(includedir)


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-libLIBRARIES mostlyclean-compile \
		mostlyclean-binPROGRAMS mostlyclean-tags \
		mostlyclean-generic

mostlyclean: mostlyclean-recursive

clean-am:  clean-libLIBRARIES clean-compile clean-binPROGRAMS clean-tags \
		clean-generic mostlyclean-am

clean: clean-recursive

distclean-am:  distclean-libLIBRARIES distclean-compile \
		distclean-binPROGRAMS distclean-tags distclean-generic \
		clean-am

distclean: distclean-recursive

maintainer-clean-am:  maintainer-clean-libLIBRARIES \
		maintainer-clean-compile maintainer-clean-binPROGRAMS \
		maintainer-clean-tags maintainer-clean-generic \
		distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-recursive

.PHONY: mostlyclean-libLIBRARIES distclean-libLIBRARIES \
clean-libLIBRARIES maintainer-clean-libLIBRARIES uninstall-libLIBRARIES \
install-libLIBRARIES mostlyclean-compile distclean-compile \
clean-compile maintainer-clean-compile mostlyclean-binPROGRAMS \
distclean-binPROGRAMS clean-binPROGRAMS maintainer-clean-binPROGRAMS \
uninstall-binPROGRAMS install-binPROGRAMS uninstall-includeHEADERS \
install-includeHEADERS install-data-recursive uninstall-data-recursive \
install-exec-recursive uninstall-exec-recursive installdirs-recursive \
uninstalldirs-recursive all-recursive check-recursive \
installcheck-recursive info-recursive dvi-recursive \
mostlyclean-recursive distclean-recursive clean-recursive \
maintainer-clean-recursive tags tags-recursive mostlyclean-tags \
distclean-tags clean-tags maintainer-clean-tags distdir info-am info \
dvi-am dvi check check-am installcheck-am installcheck install-exec-am \
install-exec install-data-am install-data install-am install \
uninstall-am uninstall all-redirect all-am all installdirs-am \
installdirs mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
