# Makefile.in generated by automake 1.15 from Makefile.am.
# po/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2014 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



#########################################
##### Defaults & Paths #####


am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/pd
pkgincludedir = $(includedir)/pd
pkglibdir = $(libdir)/pd
pkglibexecdir = $(libexecdir)/pd
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-pc-linux-gnu
host_triplet = x86_64-pc-linux-gnu
subdir = po
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/android.m4 \
	$(top_srcdir)/m4/iphone.m4 $(top_srcdir)/m4/universal.m4 \
	$(top_srcdir)/m4/generated/libtool.m4 \
	$(top_srcdir)/m4/generated/ltoptions.m4 \
	$(top_srcdir)/m4/generated/ltsugar.m4 \
	$(top_srcdir)/m4/generated/ltversion.m4 \
	$(top_srcdir)/m4/generated/lt~obsolete.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(dist_libpdpo_DATA) \
	$(am__DIST_COMMON)
mkinstalldirs = $(install_sh) -d
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(libpdpodir)" "$(DESTDIR)$(libpdpodir)"
DATA = $(dist_libpdpo_DATA) $(libpdpo_DATA)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__DIST_COMMON = $(srcdir)/Makefile.in
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/msp/bis/work/pd-versions/pd-autotools-build/m4/config/missing aclocal-1.15
ALLOCA = 
ALSA_LIBS = -lasound
AMTAR = $${TAR-tar}
AM_CPPFLAGS = 
AM_DEFAULT_VERBOSITY = 1
AR = ar
ARCH_CFLAGS = 
ARCH_LDFLAGS = 
AS = as
AUTOCONF = ${SHELL} /home/msp/bis/work/pd-versions/pd-autotools-build/m4/config/missing autoconf
AUTOHEADER = ${SHELL} /home/msp/bis/work/pd-versions/pd-autotools-build/m4/config/missing autoheader
AUTOMAKE = ${SHELL} /home/msp/bis/work/pd-versions/pd-autotools-build/m4/config/missing automake-1.15
AWK = gawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2 -ffast-math -funroll-loops -fomit-frame-pointer -O3
CPP = gcc -E
CPPFLAGS = 
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -O2
CYGPATH_W = echo
DEFS = -DPACKAGE_NAME=\"pd\" -DPACKAGE_TARNAME=\"pd\" -DPACKAGE_VERSION=\"0.48.1\" -DPACKAGE_STRING=\"pd\ 0.48.1\" -DPACKAGE_BUGREPORT=\"\" -DPACKAGE_URL=\"\" -DPACKAGE=\"pd\" -DVERSION=\"0.48.1\" -DSTDC_HEADERS=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_STAT_H=1 -DHAVE_STDLIB_H=1 -DHAVE_STRING_H=1 -DHAVE_MEMORY_H=1 -DHAVE_STRINGS_H=1 -DHAVE_INTTYPES_H=1 -DHAVE_STDINT_H=1 -DHAVE_UNISTD_H=1 -DHAVE_DLFCN_H=1 -DLT_OBJDIR=\".libs/\" -DSTDC_HEADERS=1 -DHAVE_FCNTL_H=1 -DHAVE_LIMITS_H=1 -DHAVE_MALLOC_H=1 -DHAVE_NETDB_H=1 -DHAVE_NETINET_IN_H=1 -DHAVE_STDDEF_H=1 -DHAVE_STDLIB_H=1 -DHAVE_STRING_H=1 -DHAVE_SYS_IOCTL_H=1 -DHAVE_SYS_PARAM_H=1 -DHAVE_SYS_SOCKET_H=1 -DHAVE_SYS_SOUNDCARD_H=1 -DHAVE_SYS_TIME_H=1 -DHAVE_SYS_TIMEB_H=1 -DHAVE_UNISTD_H=1 -DHAVE_ALLOCA_H=1 -DHAVE_ALLOCA=1 -DHAVE_FORK=1 -DHAVE_VFORK=1 -DHAVE_WORKING_VFORK=1 -DHAVE_WORKING_FORK=1 -DHAVE_STDLIB_H=1 -DHAVE_MALLOC=1 -DHAVE_STDLIB_H=1 -DHAVE_REALLOC=1 -DRETSIGTYPE=void -DHAVE_DUP2=1 -DHAVE_GETCWD=1 -DHAVE_GETHOSTBYNAME=1 -DHAVE_GETTIMEOFDAY=1 -DHAVE_MEMMOVE=1 -DHAVE_MEMSET=1 -DHAVE_REGCOMP=1 -DHAVE_SELECT=1 -DHAVE_SOCKET=1 -DHAVE_STRCHR=1 -DHAVE_STRERROR=1 -DHAVE_STRRCHR=1 -DHAVE_STRSTR=1 -DHAVE_STRTOL=1 -DHAVE_LIBDL=1
DEPDIR = .deps
DLLTOOL = dlltool
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
EXTERNAL_CFLAGS = -fPIC
EXTERNAL_EXTENSION = pd_linux
EXTERNAL_LDFLAGS = -Wl,--export-dynamic -fPIC
EXTERNTARGET = 
FGREP = /bin/grep -F
GREP = /bin/grep
HAVE_MSGFMT = yes
INSTALL = /bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
JACK_LIBS = -ljack
LD = /bin/ld -m elf_x86_64
LDFLAGS = 
LIBM = -lm
LIBOBJS = 
LIBS = -lpthread -ldl  -lrt
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
LT_SYS_LIBRARY_PATH = 
MAKEINFO = ${SHELL} /home/msp/bis/work/pd-versions/pd-autotools-build/m4/config/missing makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
NM = /bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = pd
PACKAGE_BUGREPORT = 
PACKAGE_NAME = pd
PACKAGE_STRING = pd 0.48.1
PACKAGE_TARNAME = pd
PACKAGE_URL = 
PACKAGE_VERSION = 0.48.1
PATH_SEPARATOR = :
RANLIB = ranlib
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/sh
STRIP = strip
VERSION = 0.48.1
WISH = 
abs_builddir = /home/msp/bis/work/pd-versions/pd-autotools-build/po
abs_srcdir = /home/msp/bis/work/pd-versions/pd-autotools-build/po
abs_top_builddir = /home/msp/bis/work/pd-versions/pd-autotools-build
abs_top_srcdir = /home/msp/bis/work/pd-versions/pd-autotools-build
ac_ct_AR = ar
ac_ct_CC = gcc
ac_ct_CXX = g++
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-pc-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-pc-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/msp/bis/work/pd-versions/pd-autotools-build/m4/config/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
AUTOMAKE_OPTIONS = foreign
SUFFIXES = .po .pot .msg
#XGETTEXT = echo fake:xgettext
XGETTEXT = xgettext
#MSGMERGE = echo fake:msgmerge
MSGMERGE = msgmerge
#MSGFMT = echo fake:msgfmt
MSGFMT = msgfmt

#########################################
##### Files, Binaries, & Libs #####
TCLFILES = \
    apple_events.tcl \
    dialog_canvas.tcl \
    dialog_gatom.tcl \
    dialog_path.tcl \
    pd_bindings.tcl \
    pd_menus.tcl \
    pdwindow.tcl \
    scrollboxwindow.tcl \
    AppMain.tcl \
    dialog_data.tcl \
    dialog_iemgui.tcl \
    dialog_startup.tcl \
    pd_connect.tcl \
    pkgIndex.tcl \
    wheredoesthisgo.tcl \
    dialog_array.tcl \
    dialog_find.tcl \
    dialog_message.tcl \
    helpbrowser.tcl \
    pdtk_canvas.tcl \
    pkg_mkIndex.tcl \
    dialog_audio.tcl \
    dialog_font.tcl \
    dialog_midi.tcl \
    opt_parser.tcl \
    pd_menucommands.tcl \
    pdtk_text.tcl \
    scrollbox.tcl \
    pd_guiprefs.tcl \
    pd_deken.tcl \
    pd_docsdir.tcl

LOCAL_TCLFILES = \
    iemgui_dynamic_strings.tcl \
    pd_dynamic_strings.tcl


# note: adding $(top_srcdir) prefix for out of tree builds
# where $(top_srcdir) and $(top_builddir) are not the same
#
# updating template.pot & the .po files are not considered per-build artifacts
# but part of the source, the per build files are the generated .msg files
FILES = $(addprefix $(top_srcdir)/tcl/, $(TCLFILES)) \
        $(addprefix $(top_srcdir)/po/, $(LOCAL_TCLFILES))


# these are the supported languages
ALL_LINGUAS = af az be bg de el en_ca eu es fr gu he hi hu it pa pt_br pt_pt sq sv vi
POFILES = $(addprefix $(top_srcdir)/po/, $(ALL_LINGUAS:=.po))
MSGFILES = $(ALL_LINGUAS:=.msg)
TEMPLATE = $(top_srcdir)/po/template.pot
libpdpodir = $(pkglibdir)/po
libpdpo_DATA = $(MSGFILES)
dist_libpdpo_DATA = 

# files that are included but not built
EXTRA_DIST = $(POFILES) $(TEMPLATE) README.txt \
             $(addprefix $(top_srcdir)/po/, $(LOCAL_TCLFILES))

all: all-am

.SUFFIXES:
.SUFFIXES: .po .pot .msg
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign po/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign po/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs
install-dist_libpdpoDATA: $(dist_libpdpo_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_libpdpo_DATA)'; test -n "$(libpdpodir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(libpdpodir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(libpdpodir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(libpdpodir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(libpdpodir)" || exit $$?; \
	done

uninstall-dist_libpdpoDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_libpdpo_DATA)'; test -n "$(libpdpodir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(libpdpodir)'; $(am__uninstall_files_from_dir)
install-libpdpoDATA: $(libpdpo_DATA)
	@$(NORMAL_INSTALL)
	@list='$(libpdpo_DATA)'; test -n "$(libpdpodir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(libpdpodir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(libpdpodir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(libpdpodir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(libpdpodir)" || exit $$?; \
	done

uninstall-libpdpoDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(libpdpo_DATA)'; test -n "$(libpdpodir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(libpdpodir)'; $(am__uninstall_files_from_dir)
tags TAGS:

ctags CTAGS:

cscope cscopelist:


distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(DATA) all-local
installdirs:
	for dir in "$(DESTDIR)$(libpdpodir)" "$(DESTDIR)$(libpdpodir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool clean-local mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-dist_libpdpoDATA install-libpdpoDATA

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-dist_libpdpoDATA uninstall-libpdpoDATA

.MAKE: install-am install-strip

.PHONY: all all-am all-local check check-am clean clean-generic \
	clean-libtool clean-local cscopelist-am ctags-am distclean \
	distclean-generic distclean-libtool distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-dist_libpdpoDATA install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-info install-info-am \
	install-libpdpoDATA install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-generic \
	mostlyclean-libtool pdf pdf-am ps ps-am tags-am uninstall \
	uninstall-am uninstall-dist_libpdpoDATA uninstall-libpdpoDATA

.PRECIOUS: Makefile


#########################################
##### Targets #####

.PHONY: locations

all-local: template po msg

clean-local:
	rm -f $(MSGFILES)

# refresh template.pot from the source code
template: $(TEMPLATE)

# remove string file locations and header "POT-Creation-Date" to suppress
# unnecessary changes, we really only want to update the .po files when a
# translation string changes in a tcl file
$(TEMPLATE): $(FILES)
	touch $(TEMPLATE)
	$(XGETTEXT) \
		--from-code=UTF-8 --language=Tcl --keyword=_ \
		--sort-by-file --output=$(TEMPLATE) \
		--package-name="Pure Data" --package-version=$(VERSION) \
		--copyright-holder='This file is put in the public domain' \
		--foreign-user \
		--msgid-bugs-address=pd-dev@iem.at \
		$(FILES)
	sed -i.bak -E '/^#:/d' $(TEMPLATE)
	sed -i.bak -E '/^"POT-Creation-Date/d' $(TEMPLATE)
	rm -f $(TEMPLATE).bak

# print the locations for translation strings in the .tcl source files
locations:
	$(XGETTEXT) \
		--from-code=UTF-8 --language=Tcl --keyword=_ \
		--sort-by-file --foreign-user --omit-header --output=- \
		$(FILES)

# refresh .po files from the template
po: $(POFILES)

# the .po files depend on template.pot, suppress line location changes to
# avoid unnecessary updates
$(POFILES): %.po: $(TEMPLATE)
	$(MSGMERGE) --no-location --quiet --update $@ $(TEMPLATE)
	touch $@
	rm -f $@~

# generate .msg files from the .po files,
# these are installed and loaded by the GUI at runtime
msg: $(MSGFILES)

# each .msg file depends on updates to the corresponding .po file
$(MSGFILES): %.msg: %.po
	$(MSGFMT) --check --tcl --locale=$* -d . $<

etags: TAGS
	etags --append --language=none --regex="/proc[ \t]+\([^ \t]+\)/\1/" *.tcl

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
