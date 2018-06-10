# RetDec Support

Support packages for the [RetDec](https://github.com/avast-tl/retdec) decompiler.

The packages contain the following data:
* A mapping of ordinal numbers to names for functions from selected Windows DLLs.
* A database of data types for functions from selected standard header files.
* YARA rules for statically linked code detection for functions from selected standard libraries.
* YARA rules for standard cryptographic constants.

The packages are created as follows:
```
XZ_DEFAULTS="-T 8" XZ_OPT=-9 tar cvJf retdec-support_2018-02-08.tar.xz *
```

## Use

A suitable package from this repository is automatically downloaded during the installation step of RetDec.

## License

Copyright (c) 2017 Avast Software, licensed under the MIT license. See the [`LICENSE`](https://github.com/avast-tl/retdec-support/blob/master/LICENSE) file for more details.
