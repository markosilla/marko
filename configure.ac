#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.68])
AC_INIT([MARKO], v0.1, [no-reply@ericsson.com])
AM_INIT_AUTOMAKE(marko, 0.1)
AC_CONFIG_SRCDIR([examples/cpp/helloworld/greeter_async_client.cc])
AC_CONFIG_HEADERS([config.h])
LT_INIT

# Checks for programs.
AC_CONFIG_MACRO_DIR([m4])
AC_PROG_CXX
AC_PROG_AWK
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET
AC_PROG_OBJC
AC_PROG_RANLIB


# Checks for libraries.
# FIXME: Replace `main' with a function in `-lFuzzer':
AC_CHECK_LIB([Fuzzer], [main])
# FIXME: Replace `main' with a function in `-lcares':
AC_CHECK_LIB([cares], [main])
# FIXME: Replace `main' with a function in `-ldl':
AC_CHECK_LIB([dl], [main])
# FIXME: Replace `main' with a function in `-lgflags':
AC_CHECK_LIB([gflags], [main])
# FIXME: Replace `main' with a function in `-lgpr':
AC_CHECK_LIB([gpr], [main])
# FIXME: Replace `main' with a function in `-lgrpc':
AC_CHECK_LIB([grpc], [main])
# FIXME: Replace `main' with a function in `-lgrpc_cronet':
AC_CHECK_LIB([grpc_cronet], [main])
# FIXME: Replace `main' with a function in `-lgrpc_unsecure':
AC_CHECK_LIB([grpc_unsecure], [main])
# FIXME: Replace `main' with a function in `-lprofiler':
AC_CHECK_LIB([profiler], [main])
# FIXME: Replace `main' with a function in `-lprotobuf':
AC_CHECK_LIB([protobuf], [main])
# FIXME: Replace `main' with a function in `-lpython':
AC_CHECK_LIB([python], [main])
# FIXME: Replace `main' with a function in `-lz':
AC_CHECK_LIB([z], [main])

# Checks for header files.
AC_CHECK_HEADERS([arpa/inet.h fcntl.h float.h inttypes.h limits.h mach/mach.h memory.h netdb.h netinet/in.h stddef.h stdint.h stdlib.h string.h strings.h sys/ioctl.h sys/socket.h sys/time.h sys/timeb.h unistd.h wchar.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_INT8_T
AC_TYPE_PID_T
AC_C_RESTRICT
AC_TYPE_SIZE_T
AC_TYPE_SSIZE_T
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT64_T
AC_TYPE_UINT8_T
AC_CHECK_TYPES([ptrdiff_t])

# Checks for library functions.
AC_FUNC_ALLOCA
AC_FUNC_ERROR_AT_LINE
AC_FUNC_FORK
AC_FUNC_MALLOC
AC_FUNC_MKTIME
AC_FUNC_REALLOC
AC_FUNC_STRNLEN
AC_FUNC_STRTOD
AC_CHECK_FUNCS([alarm atexit clock_gettime gethostname gettimeofday localtime_r memchr memmove memset mkdir modf pow putenv regcomp select setenv socket sqrt strcasecmp strchr strdup strerror strncasecmp strrchr strstr strtol strtoul strtoull])

AC_CONFIG_FILES([Makefile
				examples/cpp/helloworld/Makefile])

AC_OUTPUT
