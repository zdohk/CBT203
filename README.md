~~~~~~~~~~~~~~~~

//***FILE 203 IS FROM JIM MARSHALL.  THIS FILE CONTAINS HIS         *   FILE 203
//*           SOFTWARE TO TAKE A TMSGRW REPORT (CA-1 TAPE LIST)     *   FILE 203
//*           AND GENERATE STK SILO CARDS TO EJECT 21 OF THE        *   FILE 203
//*           TAPES AT A TIME.                                      *   FILE 203
//*                                                                 *   FILE 203
//*                  STK CARTRIDGE EJECT PACKAGE                    *   FILE 203
//*                                                                 *   FILE 203
//*           THE PURPOSE OF THIS PACKAGE IS TO START WITH A        *   FILE 203
//*      TMSGRW REPORT (A LIST OF TAPES) FROM THE CA-1 TAPE         *   FILE 203
//*      MANAGEMENT SYSTEM, AND PRODUCE A BUNCH OF STK CONTROL      *   FILE 203
//*      CARDS TO EJECT THESE TAPES FROM THE STK SILO, 21 TAPES     *   FILE 203
//*      AT A TIME.                                                 *   FILE 203
//*                                                                 *   FILE 203
//*           THAT'S ALL, FOLKS.                                    *   FILE 203
//*                                                                 *   FILE 203
//*           THIS SYSTEM CAN BE REWRITTEN FOR THE EQUIVALENT       *   FILE 203
//*      TLMS REPORT TO TMSGRW.                                     *   FILE 203
//*                                                                 *   FILE 203
//*           SEE THE JCL STREAM CALLED TMSEJECT IN THIS FILE,      *   FILE 203
//*      TO SEE HOW THIS STUFF IS STRUNG TOGETHER.  THERE ARE       *   FILE 203
//*      4 ASSEMBLER PROGRAMS.  THIS CODE HAS BEEN                  *   FILE 203
//*      'MODULARIZED' TO MAKE ITS MAINTENANCE SIMPLER.             *   FILE 203
//*                                                                 *   FILE 203
//*           IF YOU HAVE MORE THAN 5 SILOS, YOU HAVE TO            *   FILE 203
//*      ACCORDINGLY MODIFY PROGRAM STKESTK.                        *   FILE 203
//*                                                                 *   FILE 203
//*           GOOD LUCK !  IF YOU NEED HELP, CALL                   *   FILE 203
//*                                                                 *   FILE 203
//*                Jim Marshall                                     *   FILE 203
//*                Office of Personnel Management                   *   FILE 203
//*                CIO/WTC - Room BH04                              *   FILE 203
//*                1900 E Street NW                                 *   FILE 203
//*                Washington DC   20415-0001                       *   FILE 203
//*                w - 202-606-1261                                 *   FILE 203
//*                f - 202-606-2092                                 *   FILE 203
//*                jdmarsha@opm.gov                                 *   FILE 203
//*                                                                 *   FILE 203
~~~~~~~~~~~~~~~~

