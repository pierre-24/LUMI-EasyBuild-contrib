# SZ

  * [SZ web site](https://szcompressor.org)

  * [SZ on Github](https://github.com/szcompressor/SZ)

## EasyBuild

  * No SZ support in the EasyBuilders repository

  * No SZ support in the CSCS repository

  * [SZ support in the JSC repository](https://github.com/easybuilders/JSC/tree/2022/Golden_Repo/s/SZ)

### Version 2.1.12 for CPE 22.08

- Based on the JSC easyconfig
- Unload the cray-libsci module to prevent linking to the threaded version of
  libsci which is not needed. It avoid the double linking problem with 
  application that actually need libsci
