# CBT373
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 373 IS FROM GTE LABS IN WALTHAM,  MASS AND CONTAINS TWO   *   FILE 373
//*           OF THEIR TSO COMMAND PROCESSORS.  NEWSPACE AND SAL,   *   FILE 373
//*           THIS FILE IS IN IEBUPDTE SYSIN FORMAT                 *   FILE 373
//*                                                                 *   FILE 373
//*        THE "SAL" PROGRAM IS A FRIENDLIER REPLACEMENT FOR        *   FILE 373
//*        THE TSO "LISTALC" COMMAND.  "SAL" STANDS FOR "SHOW       *   FILE 373
//*        ALLOCATIONS."                                            *   FILE 373
//*                                                                 *   FILE 373
//*        SAL SHOWS DDNAME, DATASET NAME, STATUS, NORMAL           *   FILE 373
//*        DISPOSITION AND DATASET TYPE FOR EACH ALLOCATION.        *   FILE 373
//*        IT WAS DESIGNED TO PRODUCE MORE READABLE OUTPUT THAN     *   FILE 373
//*        "LISTALC."  ITS PRIMARY USE IS IN DEVELOPING CLISTS      *   FILE 373
//*        AND ISPF/PDF DIALOGS.                                    *   FILE 373
//*                                                                 *   FILE 373
//*        SAL USES DYNAMIC ALLOCATION INFORMATION RETRIEVAL TO     *   FILE 373
//*        GET INFORMATION ABOUT ALL CURRENT ALLOCATIONS.  SEE      *   FILE 373
//*        THE MVS JOB MANAGEMENT MANUAL FOR MORE INFO ON THIS      *   FILE 373
//*        USE OF DYNAMIC ALLOCATION.                               *   FILE 373
//*                                                                 *   FILE 373
//*        SAL WRITES TO FILE SYSPRINT, WHICH WOULD NORMALLY BE     *   FILE 373
//*        ALLOCATED TO THE USER'S TSO TERMINAL.  IT WORKS WITH     *   FILE 373
//*        SESSION MANAGER OR WITHOUT IT, AND IS WRITTEN TO BE      *   FILE 373
//*        REENTRANT.                                               *   FILE 373
//*                                                                 *   FILE 373
//*        THIS PACKAGE INCLUDES WELL-COMMENTED ASSEMBLER CODE      *   FILE 373
//*        (MEMBER "SAL"), MACROS ("XSAVE1," "XRETURN,"             *   FILE 373
//*        "REGISTER," "DYNABLD," AND "DYNATXTU"), AND A TSO        *   FILE 373
//*        HELP MEMBER ("SALHELP").                                 *   FILE 373
//*                                                                 *   FILE 373
//*     -------------------------------------------------------     * --FILE 373
//*                                                                 *   FILE 373
//*        NEWSPACE IS A COMMAND FOR EASILY CREATING NEW,           *   FILE 373
//*        MODERATELY SIZED, DATASETS AND LIBRARIES.  IT WAS        *   FILE 373
//*        WRITTEN WITH BEGINNERS IN MIND.  (LARGER OR MORE         *   FILE 373
//*        COMPLEX DATASETS SHOULD BE CREATED WITH THE ALLOCATE     *   FILE 373
//*        AND ATTRIB COMMANDS, OR WITH THE ISPF/PDF DATASET        *   FILE 373
//*        UTILITY (OPTION 3.2))                                    *   FILE 373
//*                                                                 *   FILE 373
//*     )X SYNTAX -                                                 *   FILE 373
//*          NEWSPACE  DATASET-NAME  TYPE  LIBRARY     FIXED        *   FILE 373
//*          NEW                           SEQUENTIAL  VARIABLE     *   FILE 373
//*                                                    UNFORMATTED  *   FILE 373
//*          DEFAULTS:  1.  LIBRARY                                 *   FILE 373
//*                     2.  FIXED, VARIABLE OR UNFORMATTED,         *   FILE 373
//*                         DEPENDING ON TYPE OR DATASET-NAME.      *   FILE 373
//*     )O OPERANDS -                                               *   FILE 373
//*     ))DATASET-NAME -                                            *   FILE 373
//*         THE NAME OF THE DATASET TO BE CREATED.                  *   FILE 373
//*     ))TYPE -                                                    *   FILE 373
//*         THIS DESIGNATES THE INTENDED USE OF THE DATASET.        *   FILE 373
//*     ))SEQUENTIAL -                                              *   FILE 373
//*         THE DATASET WILL BE CONSTRUCTED TO HOLD A SINGLE        *   FILE 373
//*         GROUP OF DATA, SUCH AS ONE FORTRAN PROGRAM, OR ONE      *   FILE 373
//*         MEMO.                                                   *   FILE 373
//*     ))LIBRARY (OR PARTITIONED, OR PDS) -                        *   FILE 373
//*         THE DATASET WILL BE CONSTRUCTED AS A LIBRARY            *   FILE 373
//*         (PARTITIONED DATASET) WHICH CAN HOLD MANY GROUPS OF     *   FILE 373
//*         DATA, SUCH AS MANY FORTRAN PROGRAMS OR MANY MEMOS.      *   FILE 373
//*         LIBRARY IS THE DEFAULT.                                 *   FILE 373
//*     ))FIXED -                                                   *   FILE 373
//*         ALL LINES OF DATA HAVE THE SAME LENGTH.  THIS IS        *   FILE 373
//*         THE DEFAULT IF NO 'TYPE' IS SELECTED AND THE            *   FILE 373
//*         DATASET NAME DOESN'T END WITH A 'TYPE' NAME.            *   FILE 373
//*     ))VARIABLE -                                                *   FILE 373
//*         EACH LINE OF DATA MAY BE A DIFFERENT LENGTH FROM        *   FILE 373
//*         THE REST.  IS THE DEFAULT IF ONE OF THESE TYPES IS      *   FILE 373
//*         SELECTED.                                               *   FILE 373
//*     ))UNFORMATTED -                                             *   FILE 373
//*         THIS IS THE FORMAT FOR LOAD DATASETS.                   *   FILE 373
//*                                                                 *   FILE 373
```
