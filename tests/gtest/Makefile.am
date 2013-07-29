# We define the global AM_CPPFLAGS as everything we compile includes from these
# directories.
AM_CPPFLAGS = -I$(srcdir) -I$(srcdir)/include
AM_CXXFLAGS = $(GTEST_CXXFLAGS)
AM_LDFLAGS = $(GTEST_LDFLAGS)
LDADD = $(GTEST_LIBS)

# Build rules for libraries.
noinst_LTLIBRARIES = lib/libgtest.la lib/libgtest_main.la

lib_libgtest_la_SOURCES = src/gtest-all.cc

lib_libgtest_main_la_SOURCES = src/gtest_main.cc
lib_libgtest_main_la_LIBADD = lib/libgtest.la

EXTRA_DIST = src/gtest.cc \
	     src/gtest-death-test.cc \
	     src/gtest-filepath.cc \
	     src/gtest-internal-inl.h \
	     src/gtest-port.cc \
	     src/gtest-printers.cc \
	     src/gtest-test-part.cc \
	     src/gtest-typed-test.cc
