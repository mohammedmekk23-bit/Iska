
/* pyconfig.h.in.  Generated from configure.ac by autoheader.  */


#ifndef Py_PYCONFIG_H
#define Py_PYCONFIG_H


/* Define if building universal (internal helper macro) */
#undef AC_APPLE_UNIVERSAL_BUILD

/* BUILD_GNU_TYPE + AIX_BUILDDATE are used to construct the PEP425 tag of the
   build system. */
#undef AIX_BUILDDATE

/* Define for AIX if your compiler is a genuine IBM xlC/xlC_r and you want
   support for AIX C++ shared extension modules. */
#undef AIX_GENUINE_CPLUSPLUS

/* The normal alignment of 'long', in bytes. */
#undef ALIGNOF_LONG

/* The normal alignment of 'max_align_t', in bytes. */
#undef ALIGNOF_MAX_ALIGN_T

/* The normal alignment of 'size_t', in bytes. */
#undef ALIGNOF_SIZE_T

/* Alternative SOABI used in debug build to load C extensions built in release
   mode */
#undef ALT_SOABI

/* The Android API level. */
#undef ANDROID_API_LEVEL

/* Define if C doubles are 64-bit IEEE 754 binary format, stored with the most
   significant byte first */
#undef DOUBLE_IS_BIG_ENDIAN_IEEE754

/* Define if C doubles are 64-bit IEEE 754 binary format, stored with the
   least significant byte first */
#undef DOUBLE_IS_LITTLE_ENDIAN_IEEE754

/* Define if --enable-ipv6 is specified */
#undef ENABLE_IPV6

/* Define if getpgrp() must be called as getpgrp(0). */
#undef GETPGRP_HAVE_ARG

/* Define if you have the 'accept' function. */
#undef HAVE_ACCEPT

/* Define to 1 if you have the 'accept4' function. */
#undef HAVE_ACCEPT4

/* Define to 1 if you have the 'acosh' function. */
#undef HAVE_ACOSH

/* Define to 1 if you have the 'acospi' function. */
#undef HAVE_ACOSPI

/* struct addrinfo (netdb.h) */
#undef HAVE_ADDRINFO

/* Define to 1 if you have the 'alarm' function. */
#undef HAVE_ALARM

/* Define if aligned memory access is required */
#undef HAVE_ALIGNED_REQUIRED

/* Define to 1 if you have the <alloca.h> header file. */
#undef HAVE_ALLOCA_H

/* Define this if your time.h defines altzone. */
#undef HAVE_ALTZONE

/* Define to 1 if you have the 'asinh' function. */
#undef HAVE_ASINH

/* Define to 1 if you have the 'asinpi' function. */
#undef HAVE_ASINPI

/* Define to 1 if you have the <asm/types.h> header file. */
#undef HAVE_ASM_TYPES_H

/* Define to 1 if you have the 'atan2pi' function. */
#undef HAVE_ATAN2PI

/* Define to 1 if you have the 'atanh' function. */
#undef HAVE_ATANH

/* Define to 1 if you have the 'atanpi' function. */
#undef HAVE_ATANPI

/* Define to 1 if you have the 'backtrace' function. */
#undef HAVE_BACKTRACE

/* Define if you have the 'bind' function. */
#undef HAVE_BIND

/* Define to 1 if you have the 'bind_textdomain_codeset' function. */
#undef HAVE_BIND_TEXTDOMAIN_CODESET

/* Define to 1 if you have the <bluetooth/bluetooth.h> header file. */
#undef HAVE_BLUETOOTH_BLUETOOTH_H

/* Define to 1 if you have the <bluetooth.h> header file. */
#undef HAVE_BLUETOOTH_H

/* Define if mbstowcs(NULL, "text", 0) does not return the number of wide
   chars that would be converted. */
#undef HAVE_BROKEN_MBSTOWCS

/* Define if nice() returns success/failure instead of the new priority. */
#undef HAVE_BROKEN_NICE

/* Define if the system reports an invalid PIPE_BUF value. */
#undef HAVE_BROKEN_PIPE_BUF

/* Define if poll() sets errno on invalid file descriptors. */
#undef HAVE_BROKEN_POLL

/* Define if the Posix semaphores do not work on your system */
#undef HAVE_BROKEN_POSIX_SEMAPHORES

/* Define if pthread_sigmask() does not work on your system. */
#undef HAVE_BROKEN_PTHREAD_SIGMASK

/* define to 1 if your sem_getvalue is broken. */
#undef HAVE_BROKEN_SEM_GETVALUE

/* Define if 'unsetenv' does not return an int. */
#undef HAVE_BROKEN_UNSETENV

/* Has builtin __atomic_load_n() and __atomic_store_n() functions */
#undef HAVE_BUILTIN_ATOMIC

/* Define to 1 if you have the <bzlib.h> header file. */
#undef HAVE_BZLIB_H

/* Define to 1 if you have the 'chflags' function. */
#undef HAVE_CHFLAGS

/* Define to 1 if you have the 'chmod' function. */
#undef HAVE_CHMOD

/* Define to 1 if you have the 'chown' function. */
#undef HAVE_CHOWN

/* Define if you have the 'chroot' function. */
#undef HAVE_CHROOT

/* Define to 1 if you have the 'clearenv' function. */
#undef HAVE_CLEARENV

/* Define to 1 if you have the 'clock' function. */
#undef HAVE_CLOCK

/* Define to 1 if you have the 'clock_getres' function. */
#undef HAVE_CLOCK_GETRES

/* Define to 1 if you have the 'clock_gettime' function. */
#undef HAVE_CLOCK_GETTIME

/* Define to 1 if you have the 'clock_nanosleep' function. */
#undef HAVE_CLOCK_NANOSLEEP

/* Define to 1 if you have the 'clock_settime' function. */
#undef HAVE_CLOCK_SETTIME

/* Define to 1 if the system has the type 'clock_t'. */
#undef HAVE_CLOCK_T

/* Define to 1 if you have the 'closefrom' function. */
#undef HAVE_CLOSEFROM

/* Define to 1 if you have the 'close_range' function. */
#undef HAVE_CLOSE_RANGE

/* Define if the C compiler supports computed gotos. */
#undef HAVE_COMPUTED_GOTOS

/* Define to 1 if you have the 'confstr' function. */
#undef HAVE_CONFSTR

/* Define to 1 if you have the <conio.h> header file. */
#undef HAVE_CONIO_H

/* Define if you have the 'connect' function. */
#undef HAVE_CONNECT

/* Define to 1 if you have the 'copy_file_range' function. */
#undef HAVE_COPY_FILE_RANGE

/* Define to 1 if you have the 'cospi' function. */
#undef HAVE_COSPI

/* Define to 1 if you have the 'ctermid' function. */
#undef HAVE_CTERMID

/* Define if you have the 'ctermid_r' function. */
#undef HAVE_CTERMID_R

/* Define if you have the 'define_key' function. */
#undef HAVE_CURSES_DEFINE_KEY

/* Define if you have the 'ESCDELAY' variable. */
#undef HAVE_CURSES_ESCDELAY

/* Define if you have the 'filter' function. */
#undef HAVE_CURSES_FILTER

/* Define if you have the 'getmouse' function with the X/Open signature. */
#undef HAVE_CURSES_GETMOUSE

/* Define to 1 if you have the <curses.h> header file. */
#undef HAVE_CURSES_H

/* Define if you have the 'has_key' function. */
#undef HAVE_CURSES_HAS_KEY

/* Define if you have the 'has_mouse' function. */
#undef HAVE_CURSES_HAS_MOUSE

/* Define if you have the 'immedok' function. */
#undef HAVE_CURSES_IMMEDOK

/* Define if you have the 'is_keypad' function. */
#undef HAVE_CURSES_IS_KEYPAD

/* Define if you have the 'is_leaveok' function. */
#undef HAVE_CURSES_IS_LEAVEOK

/* Define if you have the 'is_pad' function. */
#undef HAVE_CURSES_IS_PAD

/* Define if you have the 'is_term_resized' function. */
#undef HAVE_CURSES_IS_TERM_RESIZED

/* Define if you have the 'keyok' function. */
#undef HAVE_CURSES_KEYOK

/* Define if you have the 'key_defined' function. */
#undef HAVE_CURSES_KEY_DEFINED

/* Define if you have the 'new_prescr' function. */
#undef HAVE_CURSES_NEW_PRESCR

/* Define if you have the 'nofilter' function. */
#undef HAVE_CURSES_NOFILTER

/* Define if you have the 'resizeterm' function. */
#undef HAVE_CURSES_RESIZETERM

/* Define if you have the 'resize_term' function. */
#undef HAVE_CURSES_RESIZE_TERM

/* Define if you have the 'scr_dump' function. */
#undef HAVE_CURSES_SCR_DUMP

/* Define if you have the 'scr_set' function. */
#undef HAVE_CURSES_SCR_SET

/* Define if you have the 'set_escdelay' function. */
#undef HAVE_CURSES_SET_ESCDELAY

/* Define if you have the 'set_tabsize' function. */
#undef HAVE_CURSES_SET_TABSIZE

/* Define if you have the 'slk_attr_off' function. */
#undef HAVE_CURSES_SLK_ATTR_OFF

/* Define if you have the 'slk_attr_on' function. */
#undef HAVE_CURSES_SLK_ATTR_ON

/* Define if you have the 'slk_attr_set' function. */
#undef HAVE_CURSES_SLK_ATTR_SET

/* Define if you have the 'slk_color' function. */
#undef HAVE_CURSES_SLK_COLOR

/* Define if you have the 'syncok' function. */
#undef HAVE_CURSES_SYNCOK

/* Define if you have the 'TABSIZE' variable. */
#undef HAVE_CURSES_TABSIZE

/* Define if you have the 'term_attrs' function. */
#undef HAVE_CURSES_TERM_ATTRS

/* Define if you have the 'typeahead' function. */
#undef HAVE_CURSES_TYPEAHEAD

/* Define if you have the 'use_env' function. */
#undef HAVE_CURSES_USE_ENV

/* Define if you have the 'use_screen' function. */
#undef HAVE_CURSES_USE_SCREEN

/* Define if you have the 'use_window' function. */
#undef HAVE_CURSES_USE_WINDOW

/* Define if you have the 'wattr_get' function. */
#undef HAVE_CURSES_WATTR_GET

/* Define if you have the 'wattr_off' function. */
#undef HAVE_CURSES_WATTR_OFF

/* Define if you have the 'wattr_on' function. */
#undef HAVE_CURSES_WATTR_ON

/* Define if you have the 'wattr_set' function. */
#undef HAVE_CURSES_WATTR_SET

/* Define if you have the 'wchgat' function. */
#undef HAVE_CURSES_WCHGAT

/* Define if you have the 'wcolor_set' function. */
#undef HAVE_CURSES_WCOLOR_SET

/* Define to 1 if you have the <db.h> header file. */
#undef HAVE_DB_H

/* Define to 1 if you have the declaration of 'PR_SET_VMA_ANON_NAME', and to 0
   if you don't. */
#undef HAVE_DECL_PR_SET_VMA_ANON_NAME

/* Define to 1 if you have the declaration of 'RTLD_DEEPBIND', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_DEEPBIND

/* Define to 1 if you have the declaration of 'RTLD_GLOBAL', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_GLOBAL

/* Define to 1 if you have the declaration of 'RTLD_LAZY', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_LAZY

/* Define to 1 if you have the declaration of 'RTLD_LOCAL', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_LOCAL

/* Define to 1 if you have the declaration of 'RTLD_MEMBER', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_MEMBER

/* Define to 1 if you have the declaration of 'RTLD_NODELETE', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_NODELETE

/* Define to 1 if you have the declaration of 'RTLD_NOLOAD', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_NOLOAD

/* Define to 1 if you have the declaration of 'RTLD_NOW', and to 0 if you
   don't. */
#undef HAVE_DECL_RTLD_NOW

/* Define to 1 if you have the declaration of 'tzname', and to 0 if you don't.
   */
#undef HAVE_DECL_TZNAME

/* Define to 1 if you have the declaration of 'UT_NAMESIZE', and to 0 if you
   don't. */
#undef HAVE_DECL_UT_NAMESIZE

/* Define to 1 if you have the device macros. */
#undef HAVE_DEVICE_MACROS

/* Define to 1 if you have the /dev/ptc device file. */
#undef HAVE_DEV_PTC

/* Define to 1 if you have the /dev/ptmx device file. */
#undef HAVE_DEV_PTMX

/* Define to 1 if you have the <direct.h> header file. */
#undef HAVE_DIRECT_H

/* Define to 1 if the dirent structure has a d_type field */
#undef HAVE_DIRENT_D_TYPE

/* Define to 1 if you have the <dirent.h> header file, and it defines 'DIR'.
   */
#undef HAVE_DIRENT_H

/* Define if you have the 'dirfd' function or macro. */
#undef HAVE_DIRFD

/* Define to 1 if you have the 'dladdr' function. */
#undef HAVE_DLADDR

/* Define to 1 if you have the 'dladdr1' function. */
#undef HAVE_DLADDR1

/* Define to 1 if you have the <dlfcn.h> header file. */
#undef HAVE_DLFCN_H

/* Define to 1 if you have the 'dlopen' function. */
#undef HAVE_DLOPEN

/* Define to 1 if you have the 'dl_iterate_phdr' function. */
#undef HAVE_DL_ITERATE_PHDR

/* Define to 1 if you have the 'dup' function. */
#undef HAVE_DUP

/* Define to 1 if you have the 'dup2' function. */
#undef HAVE_DUP2

/* Define to 1 if you have the 'dup3' function. */
#undef HAVE_DUP3

/* Define if you have the '_dyld_shared_cache_contains_path' function. */
#undef HAVE_DYLD_SHARED_CACHE_CONTAINS_PATH

/* Defined when any dynamic module loading is enabled. */
#undef HAVE_DYNAMIC_LOADING

/* Define to 1 if you have the <editline/readline.h> header file. */
#undef HAVE_EDITLINE_READLINE_H

/* Define to 1 if you have the <endian.h> header file. */
#undef HAVE_ENDIAN_H

/* Define if you have the 'epoll_create' function. */
#undef HAVE_EPOLL

/* Define if you have the 'epoll_create1' function. */
#undef HAVE_EPOLL_CREATE1

/* Define to 1 if you have the 'erf' function. */
#undef HAVE_ERF

/* Define to 1 if you have the 'erfc' function. */
#undef HAVE_ERFC

/* Define to 1 if you have the <errno.h> header file. */
#undef HAVE_ERRNO_H

/* Define if you have the 'eventfd' function. */
#undef HAVE_EVENTFD

/* Define to 1 if you have the <execinfo.h> header file. */
#undef HAVE_EXECINFO_H

/* Define to 1 if you have the 'execv' function. */
#undef HAVE_EXECV

/* Define to 1 if you have the 'explicit_bzero' function. */
#undef HAVE_EXPLICIT_BZERO

/* Define to 1 if you have the 'explicit_memset' function. */
#undef HAVE_EXPLICIT_MEMSET

/* Define to 1 if you have the 'expm1' function. */
#undef HAVE_EXPM1

/* Define to 1 if you have the 'faccessat' function. */
#undef HAVE_FACCESSAT

/* Define if you have the 'fchdir' function. */
#undef HAVE_FCHDIR

/* Define to 1 if you have the 'fchmod' function. */
#undef HAVE_FCHMOD

/* Define to 1 if you have the 'fchmodat' function. */
#undef HAVE_FCHMODAT

/* Define to 1 if you have the 'fchown' function. */
#undef HAVE_FCHOWN

/* Define to 1 if you have the 'fchownat' function. */
#undef HAVE_FCHOWNAT

/* Define to 1 if you have the <fcntl.h> header file. */
#undef HAVE_FCNTL_H

/* Define if you have the 'fdatasync' function. */
#undef HAVE_FDATASYNC

/* Define to 1 if you have the 'fdopendir' function. */
#undef HAVE_FDOPENDIR

/* Define to 1 if you have the 'fdwalk' function. */
#undef HAVE_FDWALK

/* Define to 1 if you have the 'fexecve' function. */
#undef HAVE_FEXECVE

/* Define if you have the 'ffi_closure_alloc' function. */
#undef HAVE_FFI_CLOSURE_ALLOC

/* Define if you have the 'ffi_prep_cif_var' function. */
#undef HAVE_FFI_PREP_CIF_VAR

/* Define if you have the 'ffi_prep_closure_loc' function. */
#undef HAVE_FFI_PREP_CLOSURE_LOC

/* Define to 1 if you have the 'flock' function. */
#undef HAVE_FLOCK

/* Define to 1 if you have the 'fork' function. */
#undef HAVE_FORK

/* Define to 1 if you have the 'fork1' function. */
#undef HAVE_FORK1

/* Define to 1 if you have the 'forkpty' function. */
#undef HAVE_FORKPTY

/* Define to 1 if you have the 'fpathconf' function. */
#undef HAVE_FPATHCONF

/* Define to 1 if you have the 'fseek64' function. */
#undef HAVE_FSEEK64

/* Define to 1 if you have the 'fseeko' function. */
#undef HAVE_FSEEKO

/* Define to 1 if you have the 'fstatat' function. */
#undef HAVE_FSTATAT

/* Define to 1 if you have the 'fstatvfs' function. */
#undef HAVE_FSTATVFS

/* Define if you have the 'fsync' function. */
#undef HAVE_FSYNC

/* Define to 1 if you have the 'ftell64' function. */
#undef HAVE_FTELL64

/* Define to 1 if you have the 'ftello' function. */
#undef HAVE_FTELLO

/* Define to 1 if you have the 'ftime' function. */
#undef HAVE_FTIME

/* Define to 1 if you have the 'ftruncate' function. */
#undef HAVE_FTRUNCATE

/* Define to 1 if you have the 'futimens' function. */
#undef HAVE_FUTIMENS

/* Define to 1 if you have the 'futimes' function. */
#undef HAVE_FUTIMES

/* Define to 1 if you have the 'futimesat' function. */
#undef HAVE_FUTIMESAT

/* Define to 1 if you have the 'gai_strerror' function. */
#undef HAVE_GAI_STRERROR

/* Define if we can use gcc inline assembler to get and set mc68881 fpcr */
#undef HAVE_GCC_ASM_FOR_MC68881

/* Define if we can use x64 gcc inline assembler */
#undef HAVE_GCC_ASM_FOR_X64

/* Define if we can use gcc inline assembler to get and set x87 control word
   */
#undef HAVE_GCC_ASM_FOR_X87

/* Define if your compiler provides __uint128_t */
#undef HAVE_GCC_UINT128_T

/* Define to 1 if you have the <gdbm-ndbm.h> header file. */
#undef HAVE_GDBM_DASH_NDBM_H

/* Define to 1 if you have the <gdbm.h> header file. */
#undef HAVE_GDBM_H

/* Define to 1 if you have the <gdbm/ndbm.h> header file. */
#undef HAVE_GDBM_NDBM_H

/* Define if you have the getaddrinfo function. */
#undef HAVE_GETADDRINFO

/* Define this if you have flockfile(), getc_unlocked(), and funlockfile() */
#undef HAVE_GETC_UNLOCKED

/* Define to 1 if you have the 'getdents64' function. */
#undef HAVE_GETDENTS64

/* Define to 1 if you have the 'getegid' function. */
#undef HAVE_GETEGID

/* Define to 1 if you have the 'getentropy' function. */
#undef HAVE_GETENTROPY

/* Define to 1 if you have the 'geteuid' function. */
#undef HAVE_GETEUID

/* Define to 1 if you have the 'getgid' function. */
#undef HAVE_GETGID

/* Define to 1 if you have the 'getgrent' function. */
#undef HAVE_GETGRENT

/* Define to 1 if you have the 'getgrgid' function. */
#undef HAVE_GETGRGID

/* Define to 1 if you have the 'getgrgid_r' function. */
#undef HAVE_GETGRGID_R

/* Define to 1 if you have the 'getgrnam_r' function. */
#undef HAVE_GETGRNAM_R

/* Define to 1 if you have the 'getgrouplist' function. */
#undef HAVE_GETGROUPLIST

/* Define to 1 if you have the 'getgroups' function. */
#undef HAVE_GETGROUPS

/* Define if you have the 'gethostbyaddr' function. */
#undef HAVE_GETHOSTBYADDR

/* Define to 1 if you have the 'gethostbyname' function. */
#undef HAVE_GETHOSTBYNAME

/* Define this if you have some version of gethostbyname_r() */
#undef HAVE_GETHOSTBYNAME_R

/* Define this if you have the 3-arg version of gethostbyname_r(). */
#undef HAVE_GETHOSTBYNAME_R_3_ARG

/* Define this if you have the 5-arg version of gethostbyname_r(). */
#undef HAVE_GETHOSTBYNAME_R_5_ARG

/* Define this if you have the 6-arg version of gethostbyname_r(). */
#undef HAVE_GETHOSTBYNAME_R_6_ARG

/* Define to 1 if you have the 'gethostname' function. */
#undef HAVE_GETHOSTNAME

/* Define to 1 if you have the 'getitimer' function. */
#undef HAVE_GETITIMER

/* Define to 1 if you have the 'getloadavg' function. */
#undef HAVE_GETLOADAVG

/* Define to 1 if you have the 'getlogin' function. */
#undef HAVE_GETLOGIN

/* Define to 1 if you have the 'getlogin_r' function. */
#undef HAVE_GETLOGIN_R

/* Define to 1 if you have the 'getnameinfo' function. */
#undef HAVE_GETNAMEINFO

/* Define if you have the 'getpagesize' function. */
#undef HAVE_GETPAGESIZE

/* Define if you have the 'getpeername' function. */
#undef HAVE_GETPEERNAME

/* Define to 1 if you have the 'getpgid' function. */
#undef HAVE_GETPGID

/* Define to 1 if you have the 'getpgrp' function. */
#undef HAVE_GETPGRP

/* Define to 1 if you have the 'getpid' function. */
#undef HAVE_GETPID

/* Define to 1 if you have the 'getppid' function. */
#undef HAVE_GETPPID

/* Define to 1 if you have the 'getpriority' function. */
#undef HAVE_GETPRIORITY

/* Define if you have the 'getprotobyname' function. */
#undef HAVE_GETPROTOBYNAME

/* Define to 1 if you have the 'getpwent' function. */
#undef HAVE_GETPWENT

/* Define to 1 if you have the 'getpwnam_r' function. */
#undef HAVE_GETPWNAM_R

/* Define to 1 if you have the 'getpwuid' function. */
#undef HAVE_GETPWUID

/* Define to 1 if you have the 'getpwuid_r' function. */
#undef HAVE_GETPWUID_R

/* Define to 1 if the getrandom() function is available */
#undef HAVE_GETRANDOM

/* Define to 1 if the Linux getrandom() syscall is available */
#undef HAVE_GETRANDOM_SYSCALL

/* Define to 1 if you have the 'getresgid' function. */
#undef HAVE_GETRESGID

/* Define to 1 if you have the 'getresuid' function. */
#undef HAVE_GETRESUID

/* Define to 1 if you have the 'getrusage' function. */
#undef HAVE_GETRUSAGE

/* Define if you have the 'getservbyname' function. */
#undef HAVE_GETSERVBYNAME

/* Define if you have the 'getservbyport' function. */
#undef HAVE_GETSERVBYPORT

/* Define to 1 if you have the 'getsid' function. */
#undef HAVE_GETSID

/* Define if you have the 'getsockname' function. */
#undef HAVE_GETSOCKNAME

/* Define to 1 if you have the 'getspent' function. */
#undef HAVE_GETSPENT

/* Define to 1 if you have the 'getspnam' function. */
#undef HAVE_GETSPNAM

/* Define to 1 if you have the 'gettid' function. */
#undef HAVE_GETTID

/* Define to 1 if you have the 'getuid' function. */
#undef HAVE_GETUID

/* Define to 1 if you have the 'getwd' function. */
#undef HAVE_GETWD

/* Define if glibc has incorrect _FORTIFY_SOURCE wrappers for memmove and
   bcopy. */
#undef HAVE_GLIBC_MEMMOVE_BUG

/* Define to 1 if you have the 'grantpt' function. */
#undef HAVE_GRANTPT

/* Define to 1 if you have the <grp.h> header file. */
#undef HAVE_GRP_H

/* Define if you have the 'hstrerror' function. */
#undef HAVE_HSTRERROR

/* Defi # Iska
