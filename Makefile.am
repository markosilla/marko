AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

SUBDIRS = examples/cpp/helloworld/Makefile
#SUBDIRS += examples/cpp/route_guide/Makefile

doc_DATA = doc/grpc_doc.doc

clean-local:
	rm -rf Doxyfile_ grpc_doc

all: doxygen

doxygen:
	cat $(top_srcdir)/Doxyfile | sed 's:^OUTPUT_DIRECTORY .*:OUTPUT_DIRECTORY = $(PWD)/grpc_doc:g' > Doxyfile_
	cd $(top_srcdir) && doxygen $(PWD)/Doxyfile_ &>/dev/null

install-data-hook:
	cp -ax grpc_doc/html $(DESTDIR)$(docdir)/

uninstall-local:
	rm -rf $(DESTDIR)$(docdir)/html