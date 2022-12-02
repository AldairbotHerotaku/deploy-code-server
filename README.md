

export CFLAGS="-march=ivybridge -mtune=native -maes -mavx -mcx16 -mf16c -mfsgsbase -mfxsr -mmmx -mpclmul -mpopcnt -mrdrnd -msahf -msse -msse2 -msse3 -msse4.1 -msse4.2 -mssse3 -mxsave -mxsaveopt --param=l1-cache-line-size=64 --param=l1-cache-size=32 --param=l2-cache-size=6144 -O3 -pipe"
export CXXFLAGS="${CFLAGS}"
export MAKEFLAGS="-j$(nproc)"
