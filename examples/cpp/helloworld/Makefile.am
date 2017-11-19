#AM_CPPFLAGS  = -I$(top_srcdir)/include
#AM_CPPFLAGS += -I$(top_srcdir)/emtest/include

bin_PROGRAMS = greeter_server

helloworld_SOURCES = greeter_server.cc

helloworld_LDFLAGS = -lcares -lgpr -lgrpc -lgrpc_cronet -lgrpc_unsecure -lprofiler -lprotobuf -lz

helloworld_CFLAGS  = @AM_CFLAGS@
