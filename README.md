# CBT922
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 922 is from Bill Smith and contains a version of the      *   FILE 922
//*           DSPACE TSO command, which is tailored to work for     *   FILE 922
//*           Extended Access Volumes (EAV's) that have areas       *   FILE 922
//*           with Cylinder-managed space.  The reason why I have   *   FILE 922
//*           kept this file separate from CBT File 633 is because  *   FILE 922
//*           of inconsistencies in formatting the output lines,    *   FILE 922
//*           and also because of the fact that EAV's are not       *   FILE 922
//*           defined for system levels of z/OS 1.9 and lower.      *   FILE 922
//*           The macros needed to assemble this version, started   *   FILE 922
//*           being distributed with z/OS 1.10 and higher.          *   FILE 922
//*                                                                 *   FILE 922
//*           In addition to that, I had modified DSPACE in         *   FILE 922
//*           File 633 (a non-EAV version), to include the          *   FILE 922
//*           number of cylinders in the entire volume.  That       *   FILE 922
//*           information is extremely useful when you are          *   FILE 922
//*           dealing with minidisks, and you want to know how      *   FILE 922
//*           big each disk volume is, in total cylinders.          *   FILE 922
//*           (This note is by Sam Golob - 10/24/2014.)             *   FILE 922
//*                                                                 *   FILE 922
//*           Also, the FDSPACE ISPF dialog depends on the output   *   FILE 922
//*           format of the DSPACE command, and it must be changed  *   FILE 922
//*           to fit.  This has now been done, and all the FDSPACE  *   FILE 922
//*           related members have now been included.               *   FILE 922
//*                                                                 *   FILE 922
//*           email:  sfowjs@sbcglobal.net                          *   FILE 922
//*                                                                 *   FILE 922
```
