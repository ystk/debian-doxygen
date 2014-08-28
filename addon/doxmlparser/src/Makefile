#
# This file was generated from Makefile.in on Sun Apr 20 17:17:24 CEST 2014
#

DOXYGEN   = /Users/dimitri/doxygen
TMAKEPATH = /Users/dimitri/doxygen/tmake/lib/macosx-c++
ENV       = env TMAKEPATH="$(TMAKEPATH)"
TMAKE     = /Users/dimitri/doxygen/tmake/bin/tmake
MAKE      = /opt/local/bin/gmake
PYTHON    = /opt/local/bin/python2
LEX       = /usr/bin/flex
RM        = rm -f
CP        = cp
VERSION   = 1.8.6
INSTALL   = /usr/local
INSTTOOL  = /opt/local/bin/ginstall
DOXYDOCS  = ..
DOCDIR    = $(INSTALL)/share/doc/packages/doxygen
QTDIR     = /usr
HAVE_DOT  = /usr/local/bin/dot
MKSPECS   = -spec macx-g++
all clean depend: Makefile.doxmlparser 
	$(MAKE) -f Makefile.doxmlparser $@

distclean: clean
	$(RM) -rf Makefile.doxmlparser doxmlparser.pro Makefile obj

realclean: distclean

tmake:
	$(ENV) $(PERL) $(TMAKE) doxmlparser.pro >Makefile.doxmlparser

Makefile.doxmlparser: doxmlparser.pro
	$(ENV) $(PERL) $(TMAKE) doxmlparser.pro >Makefile.doxmlparser

install:
