# CBT476
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 476 is an implementation of the LISP Language on MVS,     *   FILE 476
//*           from Steve Bacher of Draper Laboratory in Cambridge,  *   FILE 476
//*           Massachusetts.  This package includes a compiler,     *   FILE 476
//*           an interpreter, and an ISPF interface for the LISP    *   FILE 476
//*           language.  This is "industrial strength" LISP for     *   FILE 476
//*           MVS.                                                  *   FILE 476
//*                                                                 *   FILE 476
//*              Steve Bacher <seb@draper.com>                      *   FILE 476
//*                                                                 *   FILE 476
//*              Charles Stark Draper Laboratory                    *   FILE 476
//*              555 Technology Square                              *   FILE 476
//*              Cambridge, MA 02139                                *   FILE 476
//*              (617) 258-1525                                     *   FILE 476
//*                                                                 *   FILE 476
//*     email:   Kjeld "Sandy" Hvatum                               *   FILE 476
//*              <kh@i1.net> (letter i,number 1)                    *   FILE 476
//*                                                                 *   FILE 476
//*           Most members of this pds are in TSO XMIT format, and  *   FILE 476
//*           a batch job called $RECEIVE has been included here,   *   FILE 476
//*           to quckly create separate pds'es out of them.         *   FILE 476
//*                                                                 *   FILE 476
//*    Second shipment:  CBT Version 430   (rebuild 09/26/00)       *   FILE 476
//*                                                                 *   FILE 476
//*       Full screen ISPF interface to the interpreter has         *   FILE 476
//*       been added, among other changes.                          *   FILE 476
//*                                                                 *   FILE 476
//*                                                  ¦              *   FILE 476
//*  ZZZZZZZZZZZZZZZZZ    IIIII   LLLLL              ¦              *   FILE 476
//*  ZZZZZZZZZZZZZZZZZ     III     LLL               ¦  L  I  S  P  *   FILE 476
//*  Z            ZZZ      III     LLL               ¦              *   FILE 476
//*              ZZZ       III     LLL               ¦              *   FILE 476
//*             ZZZ        III     LLL               ¦      ON      *   FILE 476
//*            ZZZ         III     LLL               ¦              *   FILE 476
//*           ZZZ          III     LLL               ¦              *   FILE 476
//*          ZZZ           III     LLL               ¦   M  V  S    *   FILE 476
//*         ZZZ            III     LLL               ¦              *   FILE 476
//*        ZZZ             III     LLL               ¦    _____     *   FILE 476
//*       ZZZ              III     LLL               ¦   ¦   ¦ \    *   FILE 476
//*      ZZZ               III     LLL               ¦   ¦  ___ \   *   FILE 476
//*     ZZZ                III     LLL               ¦   ¦ /...\ \  *   FILE 476
//*    ZZZ                 III     LLL               ¦   ¦ ¦.o.¦ ¦  *   FILE 476
//*   ZZZ                  III     LLL               ¦   ¦_¦...¦-¦  *   FILE 476
//*  ZZZ            Z      III     LLL            L  ¦   ¦ \___/ /  *   FILE 476
//*  ZZZZZZZZZZZZZZZZ      III     LLLLLLLLLLLLLLLL  ¦   ¦   ¦  /   *   FILE 476
//*  ZZZZZZZZZZZZZZZZ     IIIII   LLLLLLLLLLLLLLLLL  ¦   ¦_____/    *   FILE 476
//*                                                  ¦              *   FILE 476
//*                                                                 *   FILE 476
//*     ZIL - LISP for MVS - Version 1.3                            *   FILE 476
//*     Copyright 1989 The Charles Stark Draper Laboratory Inc.     *   FILE 476
//*     All Rights Reserved                                         *   FILE 476
//*                                                                 *   FILE 476
//*     Permission has been granted to include this package on      *   FILE 476
//*     the CBT MVS Utilities Tape.                                 *   FILE 476
//*                                                                 *   FILE 476
//*     ZIL is the creation of:                                     *   FILE 476
//*                                                                 *   FILE 476
//*     Steve "Batchman" Bacher <seb@draper.com> - the original     *   FILE 476
//*     conception, the compiler, the interpreter, and the bulk     *   FILE 476
//*     of the runtime, including the interfaces to TSO and ISPF    *   FILE 476
//*     and the Flavors object system.                              *   FILE 476
//*                                                                 *   FILE 476
//*     Kjeld "Sandy" Hvatum <kjeld@ultranet.com> - the runtime     *   FILE 476
//*     code that implements "bignum" arithmetic, symbol hashing    *   FILE 476
//*     and interning, the vectorizing garbage collector            *   FILE 476
//*     (available only if you have the 370 Vector Facility),       *   FILE 476
//*     and thorough, exhaustive testing.                           *   FILE 476
//*                                                                 *   FILE 476
//*     ZIL was developed at the Charles Stark Draper               *   FILE 476
//*     Laboratory (formerly the MIT Instrumentation                *   FILE 476
//*     Laboratory) in Cambridge, Massachusetts, starting in        *   FILE 476
//*     1983.  Steve and Sandy have successfully ported a           *   FILE 476
//*     number of AI applications to it, notably OPS5 (an           *   FILE 476
//*     expert system builder) and DOE Macsyma (a symbolic          *   FILE 476
//*     algebra powerhouse).  In addition, some local               *   FILE 476
//*     applications were developed using ZIL, including an         *   FILE 476
//*     expert system (under OPS5) to analyze and unload tapes      *   FILE 476
//*     on the mainframe.                                           *   FILE 476
//*                                                                 *   FILE 476
```
