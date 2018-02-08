# RetDec Support

Support packages for the [RetDec](https://github.com/avast-tl/retdec) decompiler.

Packages contain the following information:
* Mapping of ordinal numbers to names for functions from selected Windows DLLs.
* Database of data types for functions from selected standard header files.
* YARA rules for statically linked code detection for functions from selected standard libraries.
* YARA rules for standard cryptographic constants.

Packages get created like this:
```
XZ_DEFAULTS="-T 8" XZ_OPT=-9 tar cvJf retdec-support_2018-02-08.tar.xz *
```

## Use

A suitable package from this repository is automatically downloaded during the RetDec installation step.

## License

Copyright (c) 2017 Avast Software, licensed under the MIT license. See the [`LICENSE`](https://github.com/avast-tl/retdec-support/blob/master/LICENSE) file for more details.
