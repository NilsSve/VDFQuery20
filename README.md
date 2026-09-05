# VDFQuery20

VDFQuery library for DataFlex 20.0 and later.

... is the old VDFQuery library ported to DF20. Only to help migrate legacy applications to DF20.

This library has been migrated to DF 20 in order to assist in migrating legacy
applications that uses (older versions of) VDFQuery.

The library contains a lot of outdated code that does not at all reflect how
the dataflex language is used in 2021.

If you are new to VDFQuery you should keep it so. Look for more modern libraries

Sture Andersen
April, 2021

**This has been forked to NilsSve to be used with DataFlex 26 and later.**
The original ships its own, old copy of Wil van Antwerpen's vWin32fh files. This fork removes those files from AppSrc and declares the
dependency in its workspace file instead, so adding this package brings in
https://github.com/NilsSve/Library-vwin32fh (StudioLibrary/vWin32fh-Library-DF26.0.sws) automatically, that compiles with DF 26 and up.
The workspace file is DataFlex 26 JSON. For DataFlex 20 to 25 use the original repository.
