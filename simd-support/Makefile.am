AM_CPPFLAGS = -I $(top_srcdir)
noinst_LTLIBRARIES = libsimd_support.la 

libsimd_support_la_SOURCES = taint.c simd-common.h \
x86-cpuid.h amd64-cpuid.h \
simd-sse2.h sse2.c \
avx.c simd-avx.h \
avx-128-fma.c simd-avx-128-fma.h \
avx2.c simd-avx2.h simd-avx2-128.h \
avx512.c simd-avx512.h \
kcvi.c simd-kcvi.h \
altivec.c simd-altivec.h vsx.c simd-vsx.h \
neon.c simd-neon.h \
simd-generic128.h simd-generic256.h \
rvv.c simd-rvv.h simd-rvv128.h simd-rvv256.h simd-rvv512.h simd-rvv1024.h  \
simd-rvv2048.h simd-rvv4096.h simd-rvv8192.h simd-rvv16384.h simd-rvv32768.h simd-rvv65536.h vtw.h
