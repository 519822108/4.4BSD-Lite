# This file was generated automatically by configure.  Do not edit.
VPATH = .
links = 
host_alias = m68k-hp-bsd
host_cpu = m68k
host_vendor = hp
host_os = bsd
host_canonical = m68k-hp-bsd
target_alias = m68k-hp-bsd
target_cpu = m68k
target_vendor = hp
target_os = bsd
target_canonical = m68k-hp-bsd
host_makefile_frag = ../../m68k-hp-bsd.mh
ALL=all.internal

srcdir = .

prefix = /usr/local

exec_prefix = $(prefix)
bindir = $(exec_prefix)/bin
libdir = $(exec_prefix)/lib

datadir = $(prefix)/lib
mandir = $(prefix)/man
man1dir = $(mandir)/man1
man2dir = $(mandir)/man2
man3dir = $(mandir)/man3
man4dir = $(mandir)/man4
man5dir = $(mandir)/man5
man6dir = $(mandir)/man6
man7dir = $(mandir)/man7
man8dir = $(mandir)/man8
man9dir = $(mandir)/man9
infodir = $(prefix)/info
includedir = $(prefix)/include
docdir = $(datadir)/doc

SHELL = /bin/sh

INSTALL = install -c
INSTALL_PROGRAM = $(INSTALL)
INSTALL_DATA = $(INSTALL)

AR = `if [ -f ../../../binutils/ar ] ; \
	then echo ../../../binutils/ar ; \
	else echo ar ; fi`

AR_FLAGS = qc
RANLIB = `if [ -f ../../../binutils/ranlib ] ; \
	then echo ../../../binutils/ranlib ; \
	else echo ranlib ; fi`

MAKEINFO = `if [ -f ../../../texinfo/C/makeinfo ] ; \
	then echo ../../../texinfo/C/makeinfo ; \
	else echo makeinfo ; fi`

STDIO_CFILES = clearerr.C emulate.C fclose.C fdopen.C feof.C \
  ferror.C fflush.C fgetc.C fgetpos.C fgets.C fileno.C fopen.C \
  fprintf.C fputc.C fputs.C fread.C freopen.C fscanf.C fseek.C \
  fsetpos.C ftell.C fwrite.C gets.C perror.C popen.C printf.C puts.C \
  remove.C rename.C rewind.C  scanf.C setbuf.C setbuffer.C \
  setlinebuf.C setvbuf.C sprintf.C sscanf.C stdio.C tmpfile.C \
  tmpnam.C vfprintf.C vfscanf.C vprintf.C vsprintf.C vscanf.C \
  vsscanf.C ungetc.C

STDIO_FILES = $(STDIO_CFILES) stdio.h Makefile

STDIO_OBJECTS = clearerr.o emulate.o fclose.o fdopen.o feof.o \
  ferror.o fflush.o fgetc.o fgetpos.o fgets.o fileno.o fopen.o \
  fprintf.o fputc.o fputs.o fread.o freopen.o fscanf.o fseek.o \
  fsetpos.o ftell.o fwrite.o gets.o perror.o popen.o printf.o puts.o \
  remove.o rename.o rewind.o  scanf.o setbuf.o setbuffer.o \
  setlinebuf.o setvbuf.o sprintf.o sscanf.o stdio.o tmpfile.o \
  tmpnam.o vfprintf.o vfscanf.o vprintf.o vsprintf.o vscanf.o \
  vsscanf.o ungetc.o

DEPEND_SOURCES = $(srcdir)/*.C

TARGETLIB = libstdio++.a

# IO_DIR is used in 'depend' rules generated by ../../utils/gendepend.
IO_DIR = iostream

CC = `if [ -f ../../../gcc/gcc ] ; \
	then echo ../../../gcc/gcc -B../../../gcc/ ; \
	else echo cc ; fi`
CXX = `if [ -f ../../../gcc/gcc ] ; \
	then echo ../../../gcc/gcc -B../../../gcc/ ; \
	else echo gcc ; fi`

CFLAGS = -g
CXXFLAGS = -g -O
XTRAFLAGS = `if [ -f ../../../gcc/gcc ] ; \
	then echo -I../../../gcc/include ; \
	else echo ; fi`

WRAP_C_INCLUDES = -I$(srcdir)/../../g++-include

#### Host and target-dependent makefile fragments come in here.
INSTALL = install -c
INSTALL_DATA = install -c -m 644
# RANLIB = ranlib
# Use -nostdinc++ flag if your version of gcc understands it.
NOSTDINC = # -nostdinc++

# If the C include files are C++-ready (with extern "C"),
# define: HAVE_CPLUS_EXTERN = 1 and: WRAP_C_INCLUDES =
# If not, define HAVE_CPLUS_EXTERN = 0, and do not define WRAP_C_INCLUDES here.
HAVE_CPLUS_EXTERN = 0

# Flags to pass to gen-params when building _G_config.h.
# For example: G_CONFIG_ARGS = size_t="unsigned long"
G_CONFIG_ARGS =
##

.SUFFIXES: .o .C .c .cc

.C.o:
	$(CXX) $(CXXFLAGS) $(NOSTDINC) -I../.. -I$(srcdir) -I$(srcdir)/.. $(WRAP_C_INCLUDES) -c $(XTRAFLAGS) $<
.c.o:
	$(CC) $(CFLAGS) $(NOSTDINC) -I../.. -I$(srcdir) -I$(srcdir)/.. $(WRAP_C_INCLUDES) -c $(XTRAFLAGS) $<

.PHONY: all
all: $(TARGETLIB)
.PHONY: info
info:
.PHONY: clean-info
clean-info:
.PHONY: install-info
install-info:

.PHONY: check
check:

$(TARGETLIB): $(STDIO_OBJECTS)
	-rm -f $(TARGETLIB)
	$(AR) $(AR_FLAGS) $(TARGETLIB) $(STDIO_OBJECTS)
	$(RANLIB) $(TARGETLIB)	

.PHONY: install
install:
	-parent=`echo $(libdir)|sed -e 's@/[^/]*$$@@'`; \
	if [ -d $$parent ] ; then true ; else mkdir $$parent ; fi
	-if [ -d $(libdir) ] ; then true ; else mkdir $(libdir) ; fi
	-rm -f $(libdir)/$(TARGETLIB)
	$(INSTALL_DATA) $(TARGETLIB) $(libdir)/$(TARGETLIB)
	$(RANLIB) $(libdir)/$(TARGETLIB)

.PHONY: mostlyclean clean distclean realclean
mostlyclean:
	rm -f *.o \#* core
clean: mostlyclean
	rm -f *.a
distclean: clean
	rm -f *~ config.status
realclean: distclean
	rm -f depend

force:

# with the gnu make, this is done automatically.

Makefile: $(srcdir)/Makefile.in $(host_makefile_frag) $(target_makefile_frag)
	$(SHELL) ./config.status

.NOEXPORT:


# DO NOT DELETE THIS LINE -- g++dep uses it.
# DO NOT PUT ANYTHING AFTER THIS LINE, IT WILL GO AWAY.

clearerr.o : clearerr.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
emulate.o : emulate.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fclose.o : fclose.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fdopen.o : fdopen.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
feof.o : feof.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
ferror.o : ferror.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fflush.o : fflush.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fgetc.o : fgetc.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fgets.o : fgets.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fileno.o : fileno.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fopen.o : fopen.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fprintf.o : fprintf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h
fputc.o : fputc.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fputs.o : fputs.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fread.o : fread.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
freopen.o : freopen.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fscanf.o : fscanf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fseek.o : fseek.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
ftell.o : ftell.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
fwrite.o : fwrite.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
popen.o : popen.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h \
  $(srcdir)/../../$(IO_DIR)/procbuf.h
printf.o : printf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
rewind.o : rewind.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
scanf.o : scanf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h
setbuf.o : setbuf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
setbuffer.o : setbuffer.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
setlinebuf.o : setlinebuf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
setvbuf.o : setvbuf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
sprintf.o : sprintf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h
sscanf.o : sscanf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h \
  $(srcdir)/../../$(IO_DIR)/strstream.h \
  $(srcdir)/../../$(IO_DIR)/iostream.h
stdio.o : stdio.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
ungetc.o : ungetc.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
vfprintf.o : vfprintf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
vfscanf.o : vfscanf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
vprintf.o : vprintf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h
vscanf.o : vscanf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h 
vsprintf.o : vsprintf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h \
  $(srcdir)/../../$(IO_DIR)/strstream.h \
  $(srcdir)/../../$(IO_DIR)/iostream.h
vsscanf.o : vsscanf.C \
  stdioprivate.h \
  stdio.h \
  $(srcdir)/../../$(IO_DIR)/ioprivate.h \
  $(srcdir)/../../$(IO_DIR)/streambuf.h \
  $(srcdir)/../../$(IO_DIR)/strstream.h \
  $(srcdir)/../../$(IO_DIR)/iostream.h

# IF YOU PUT ANYTHING HERE IT WILL GO AWAY
