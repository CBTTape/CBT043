# CBT043
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 043 is from Lionel Dyck and contains an exec called       *   FILE 043
//*           CBT, which provides easy access to all CBT Tape       *   FILE 043
//*           files, provided they are cataloged on your system     *   FILE 043
//*           and on disk, and their dataset names have a           *   FILE 043
//*           consistent format.  If a CBT Tape file is not on      *   FILE 043
//*           your local DASD, the dialog provides an option        *   FILE 043
//*           to download the file from the CBTtape.org site to     *   FILE 043
//*           your local DASD.                                      *   FILE 043
//*                                                                 *   FILE 043
//*           Execute $INSTALL to install into a new dataset,       *   FILE 043
//*           replace an existing dataset, or *update* an existing  *   FILE 043
//*           dataset.                                              *   FILE 043
//*                                                                 *   FILE 043
//*           email:  lbdyck@gmail.com                              *   FILE 043
//*                                                                 *   FILE 043
//*       Included with this package is an exec called CBTSRCH      *   FILE 043
//*       provided by Willy Jensen. It may be called by itself,     *   FILE 043
//*       or invoked as the Enhanced Search (ES) within the CBT     *   FILE 043
//*       dialog.                                                   *   FILE 043
//*                                                                 *   FILE 043
//*           email:        willy.h.jensen@outlook.com              *   FILE 043
//*           website:      http://harders-jensen.com/wjtech        *   FILE 043
//*                                                                 *   FILE 043
//*       This package also utilizes Dave Alcock's XMITINFO         *   FILE 043
//*       exec (File 311). It is used to determine the DCB of       *   FILE 043
//*       the XMIT file so that the CBT exec can set an optimal     *   FILE 043
//*       BLKSIZE during the RECEIVE process.                       *   FILE 043
//*                                                                 *   FILE 043
//*       CBT Tape FILE001 is required for this application to      *   FILE 043
//*       run, but if it isn't available, the application will      *   FILE 043
//*       attempt to FTP the file to your local DASD for use.       *   FILE 043
//*       This is then used to build an index of all files          *   FILE 043
//*       for quick access, allowing the user to determine if       *   FILE 043
//*       they want to download the specific file.                  *   FILE 043
//*                                                                 *   FILE 043
//*       An option is also provided to check for file updates      *   FILE 043
//*       and then to download the updated files.                   *   FILE 043
//*                                                                 *   FILE 043
//*       Note: This is another option:                             *   FILE 043
//*       By downloading the tersed backup files of the disk        *   FILE 043
//*       CBTA01 from the CBT website www.cbttape.org               *   FILE 043
//*                                                                 *   FILE 043
//* =============================================================== *   FILE 043
//*  ONLINE Forum                                                   *   FILE 043
//* =============================================================== *   FILE 043
//*                                                                 *   FILE 043
//*       If you'd like to join an online forum to discuss all      *   FILE 043
//*       things CBT use this link to join the System Z Enthusiasts *   FILE 043
//*       Discord server and find the 'cbttape' channel.            *   FILE 043
//*                                                                 *   FILE 043
//*       https://discord.gg/sze                                    *   FILE 043
//*                                                                 *   FILE 043
//* =============================================================== *   FILE 043
//*                                                                 *   FILE 043
//*       NAME       VER.MOD   LAST MODIFIED     SIZE   ID          *   FILE 043
//*       $$README    01.67   2025/02/15 11:21    339 CBT           *   FILE 043
//*       $INSTALL    01.38   2024/01/02 20:12    135 CBT           *   FILE 043
//*       $INSTALP    01.06   2024/01/02 20:16     48 CBT           *   FILE 043
//*       CBT         01.99   2025/03/25 17:12   4330 CBT           *   FILE 043
//*       CBTCONFG    01.23   2025/02/22 11:07     61 CBT           *   FILE 043
//*       CBTDOWN     01.15   2024/02/07 17:35    288 CBT           *   FILE 043
//*       CBTDOWNJ    01.00   2021/04/10 10:58     12 CBT           *   FILE 043
//*       CBTSRCH     01.18   2021/08/12 06:07   1116 CBT           *   FILE 043
//*       CBTSRCH$    01.02   2021/05/01 05:26     63 CBT           *   FILE 043
//*       CBTVIEW     01.01   2021/11/29 11:25     25 CBT           *   FILE 043
//*       UNZIPL      01.00   2021/04/07 03:33    761 CBT           *   FILE 043
//*       UNZIPXMI    01.01   2021/05/10 20:05   3272 CBT           *   FILE 043
//*       XMITINFO    01.01   2022/04/20 09:20    959 CBT           *   FILE 043
//*                                                                 *   FILE 043
```
