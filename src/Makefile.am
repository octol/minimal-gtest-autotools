#SUBDIRS = gtest
#
#SRC = $(srcdir)/.. 
#AM_CPPFLAGS = -I$(SRC) 

# Modifies compiler and linker flags for pthreads compatibility.
#if HAVE_PTHREADS
#  AM_CXXFLAGS = @PTHREAD_CFLAGS@ -DGTEST_HAS_PTHREAD=1
#  AM_LIBS = @PTHREAD_LIBS@
#else
#  AM_CXXFLAGS = -DGTEST_HAS_PTHREAD=0
#endif

# TESTS -- Programs run automatically by "make check"
# check_PROGRAMS -- Programs built by "make check" but not necessarily run
#TESTS = 
#check_PROGRAMS = 
#
#TESTS += func_gtest
#check_PROGRAMS += Particle_test
#Particle_test_SOURCES = Particle_test.cpp 
#Particle_test_LDADD = gtest/lib/libgtest_main.la \
#		      gtest/lib/libgtest.la \
#		      ../libsdlc-0.1.la

#bin_PROGRAMS = main func_gtest
bin_PROGRAMS = main

main_SOURCES = main.cpp func.cpp
#main_LDADD = gtest/libgtest_main.a

#func_gtest_SOURCES = func.cpp func_gtest.cpp
#func_gtest_LDADD = gtest/libgtest_main.a -lpthread
