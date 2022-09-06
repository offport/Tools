
Compress file named dir1

`7zr a -t7z -m0=lzma -mx=9 -mfb=64 -md=32m -ms=on archive.7z dir1`

Uncompress file `archive.7` to directory `myfiles`. Yes. No space after -o.

`7zr.exe e archive.7z -omyfiles`
