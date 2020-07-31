This workshop will show you how to create an RPG SDK (a set of procedures to work with a web API) from scratch.

We use these tools:

* https://ileditor.dev/ - My IDE of choice. You can use any you want (RDi, ILEditor, SEU, etc)
* https://github.com/sitemule/noxDB - The JSON parsing library. Service program is also in this repo so you can restore the save file.
  1. Copy `jsonxml.pkg` to IFS
  2. `CPYFRMSTMF FROMSTMF('jsonxml.pkg') TOMBR('/QSYS.LIB/PUNKAPI.LIB/PACKAGE.FILE') MBROPT(*REPLACE) CVTDTA(*NONE)`
  3. `RST DEV('/QSYS.LIB/PUNKAPI.LIB/PACKAGE.FILE') OBJ(('/QSYS.LIB/PUNKAPI.LIB/PUNKAPI.SRVPGM'))`
* https://punkapi.com/documentation/v2 - The API we use in the workshop.

### Videos

1. [Introductions](https://www.youtube.com/watch?v=zTxgby0RxuY&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=2&t=0s)
2. [Setting up the environment](https://www.youtube.com/watch?v=QE_3MdCCNzo&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=3&t=0s)
3. [API Planning](https://www.youtube.com/watch?v=hUulbkmHpIM&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=4&t=0s)
4. [Fetching the data](https://www.youtube.com/watch?v=TWmYr2EI7uA&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=4)
5. [Our first test program](https://www.youtube.com/watch?v=3Op3eQlQoiA&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=5)
6. [Cleanup](https://www.youtube.com/watch?v=giiPqXiJFbI&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=7&t=0s)
7. [Prettier APIs](https://www.youtube.com/watch?v=B8qSJC21RSw&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=8&t=0s)
