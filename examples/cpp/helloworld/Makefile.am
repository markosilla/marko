#AM_CPPFLAGS  = -I$(top_srcdir)/include
#AM_CPPFLAGS += -I$(top_srcdir)/emtest/include

bin_PROGRAMS = greeter_server

greeter_server_SOURCES = greeter_server.cc

greeter_server_LDFLAGS = -lcares -lgpr -lgrpc -lgrpc_cronet -lgrpc_unsecure -lprofiler -lprotobuf -lz

greeter_server_CFLAGS  = @AM_CFLAGS@
