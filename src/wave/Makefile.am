noinst_LIBRARIES =  libwave.a 

if WITH_LIBDDD_PATH
LIBDDD_CPP=-I$(LIBDDD_ROOT)
LIBDDD_PATH=$(LIBDDD_ROOT)/libDDD.a
else
LIBDDD_LINK=-lddd
endif


if WITH_LIBITS_PATH
LIBITS_CPP=-I$(LIBITS_ROOT) 
LIBITS_PATH=$(LIBITS_ROOT)/../lib/libITS.a 
else
LIBITS_LINK=-lITS
endif


AM_CPPFLAGS =  -Wall -g -O2 -I $(top_srcdir)/src $(HAVE_BOOST_FLAG) $(LIBITS_CPP) $(LIBDDD_CPP) 

libwave_a_SOURCES = wave.cpp wave.hh



