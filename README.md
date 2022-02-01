# Github PNG Rendering Test

Both of the files are actually png under the hood, wanted to check if github knew how to render .xyz file as png when its is internally a png

```bash
hexdump -C -n 100 addFiles.tldr
00000000  89 50 4e 47 0d 0a 1a 0a  00 00 00 0d 49 48 44 52  |.PNG........IHDR|
00000010  00 00 0f 08 00 00 11 87  08 02 00 00 00 f6 da ec  |................|
00000020  6d 00 00 80 00 49 44 41  54 78 9c ec fd 7b b0 64  |m....IDATx...{.d|
00000030  75 7d ef ff 7f 3e eb d6  d7 dd fb 3a cc 0c c3 88  |u}...>.....:....|
00000040  20 18 f0 a0 1c af e8 d1  28 5a fc c0 d2 e3 b5 50  | .......(Z.....P|
00000050  39 96 26 65 4c 8e 55 31  9a 8b 15 93 60 8c a6 a4  |9.&eL.U1....`...|
00000060  0c 95 c4 93                                       |....|
00000064
```
