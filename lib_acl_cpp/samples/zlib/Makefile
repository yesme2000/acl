include ../Makefile.in
PROG = zlib
#EXTLIBS += -lz -liconv
#Path for SunOS
ifeq ($(findstring SunOS, $(UNIXNAME)), SunOS)
	EXTLIBS = -lz -liconv
endif
ifeq ($(findstring FreeBSD, $(UNIXNAME)), FreeBSD)
	EXTLIBS = -L/usr/local/lib -liconv
endif
EXTLIBS += -lz
