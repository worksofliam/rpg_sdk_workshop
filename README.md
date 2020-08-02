This workshop will show you how to create an RPG SDK (a set of procedures to work with/consume a web API) from scratch.

We use these tools:

* https://ileditor.dev/ - My IDE of choice. You can use any you want (RDi, ILEditor, SEU, etc)
* https://github.com/sitemule/noxDB - The JSON parsing library. Service program is also in this repo so you can restore the save file.
  1. Copy `jsonxml.pkg` to IFS
  2. `CPYFRMSTMF FROMSTMF('jsonxml.pkg') TOMBR('/QSYS.LIB/PUNKAPI.LIB/PACKAGE.FILE') MBROPT(*REPLACE) CVTDTA(*NONE)`
  3. `RST DEV('/QSYS.LIB/PUNKAPI.LIB/PACKAGE.FILE') OBJ(('/QSYS.LIB/PUNKAPI.LIB/JSONXML.SRVPGM'))`
* https://punkapi.com/documentation/v2 - The API we use in the workshop (parts 1-9).
* https://todo-api-example.herokuapp.com/ - The API we use in the workshop (parts 10-14)
  * The repo for this app is here: https://github.com/worksofliam/todo-api

### Videos

1. [Introductions](https://www.youtube.com/watch?v=zTxgby0RxuY&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=2&t=0s)
2. [Setting up the environment](https://www.youtube.com/watch?v=QE_3MdCCNzo&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=3&t=0s)
3. [API Planning](https://www.youtube.com/watch?v=hUulbkmHpIM&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=4&t=0s)
4. [Fetching the data](https://www.youtube.com/watch?v=TWmYr2EI7uA&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=4)
5. [Our first test program](https://www.youtube.com/watch?v=3Op3eQlQoiA&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=5)
6. [Cleanup](https://www.youtube.com/watch?v=giiPqXiJFbI&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=7&t=0s)
7. [Prettier APIs](https://www.youtube.com/watch?v=B8qSJC21RSw&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=8&t=0s)
8. [Error Handling](https://www.youtube.com/watch?v=9X1Wu7IftrU&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=9&t=0s)
9. [Get by ID](https://www.youtube.com/watch?v=AZU6Pagb_hg&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=10&t=0s)
10. [Intro to next section](https://www.youtube.com/watch?v=WmuyNKsqKLM&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=11&t=0s) where we look at how to authentictate with JWT
11. [Implementing JWT authentication](https://www.youtube.com/watch?v=jdPFRp3pSu8&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=12&t=0s)
12. [Fixes and Test program](https://www.youtube.com/watch?v=kSfafhvBYxk&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=13&t=0s)
13. [Getting a list](https://www.youtube.com/watch?v=RgQT7cFNVaU&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=14&t=0s)
14. [Adding to the list](https://www.youtube.com/watch?v=Jil1gNCtZng&list=PLNl31cqBafComzOAedzgOSNb7dlsDGvv5&index=15&t=0s)
