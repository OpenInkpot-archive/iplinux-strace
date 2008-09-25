#
# $Id: Makefile,v 1.6 2007/11/13 08:12:12 roland Exp $
#

all: vfork fork sig skodic clone leaderkill childthread

leaderkill: LDFLAGS += -pthread

childthread: LDFLAGS += -pthread

clean distclean:
	rm -f clone vfork fork sig leaderkill *.o core

