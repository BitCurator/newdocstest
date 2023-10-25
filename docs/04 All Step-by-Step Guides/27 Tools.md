# **Tools**

### **Overview**

The BitCurator Environment includes many individual tools to perform
specific curation tasks. Listed here are all tools packaged by default
in the environment, organized by the folder found on the BitCurator
desktop. Links will take users to the corresponding external site or
documentation. Where applicable, relevant BitCurator **Step-by-Step
Guides** are listed as well.

Because BitCurator is an Ubuntu environment, users are able to download
and install tools as in any other Ubuntu distribution or Linux OS.

In addition, much functionality is found in the file navigation system,
Nautilus, through contextual menus. Listed are guides for many of these
scripts.

- [<u>Data
  Triage</u>](https://confluence.educopia.org/pages/viewpage.action?pageId=15630990&src=contextnavpagetreemode)

- [<u>Create MD5
  Sums</u>](https://confluence.educopia.org/pages/viewpage.action?pageId=15630994&src=contextnavpagetreemode)

- [<u>Display a file in Hex
  editor</u>](https://confluence.educopia.org/pages/viewpage.action?pageId=15630997&src=contextnavpagetreemode)

- [<u>Disk Image
  Metadata</u>](https://confluence.educopia.org/pages/viewpage.action?pageId=15631001&src=contextnavpagetreemode)

- [<u>Extract Compressed
  Files</u>](https://confluence.educopia.org/pages/viewpage.action?pageId=15631005&src=contextnavpagetreemode)

- [<u>Live Search for
  Files</u>](https://confluence.educopia.org/pages/viewpage.action?pageId=15631010&src=contextnavpagetreemode)

- [<u>Safely Mount
  Device</u>](https://confluence.educopia.org/display/BC/Safely+Mount+Devices)

**Imaging and Recovery**

[**<u>Brasero</u>**](https://wiki.gnome.org/Apps/Brasero): GUI
application to copy data and audio CD and DVDs

[**<u>Guymager</u>**](https://guymager.sourceforge.io/): Open-source
forensic disk imaging tool

- See the [<u>Creating a Disk Image Using
  Guymager</u>](https://confluence.educopia.org/display/BC/Creating+a+Disk+Image+Using+Guymager)
  **Step-by-Step Guide**.

[**cdrdao**](http://cdrdao.sourceforge.net/): CD imaging tool (primarily
for audio CDs)

[**<u>Clonezilla</u>**](https://clonezilla.org/): A imaging and cloning
program for partitions and disks

[**dcfldd**](http://dcfldd.sourceforge.net/): A forensics-focused
rewrite of **dd**

[**dd**](https://www.gnu.org/software/coreutils/manual/html_node/dd-invocation.html):
Create raw disk images and transfer data between devices

[**<u>ddrescue</u>**](https://www.gnu.org/software/ddrescue/): A version
of **dd** with additional options for data recovery

[**<u>dumpfloppy</u>**](https://offog.org/code/dumpfloppy/): Suite of
tools for reading floppy disks in arbitrary formats supported by the PC
floppy controller, and for working with the resulting image files

[**ewfacquire**](https://linux.die.net/man/1/ewfacquire): Acquire Expert
Witness packaged disk images from devices on the command line. Part of
the [<u>libewf</u>](https://github.com/libyal/libewf) library of Expert
Witness tools.

- More documentation at the [<u>Forensics
  wiki</u>](https://forensicswiki.xyz/wiki/index.php?title=Libewf).

**Forensic analysis tools**

**BitCurator Disk Image Access:** A GUI interface to browse raw and
forensically-packaged disk images, export files and deleted items, and
view disk image metadata.

**BitCurator Mounter**: A GUI application to list currently attached
devices along with technical details. Allows users to mount fixed and
removable media according to the current mount policy.

**BitCurator Reporting Tool**: A GUI-driven (and optionally
command-line) tool for running forensics tools in sequence to produce
human- and machine-readable reports in
[<u>DFXML</u>](https://www.github.com/simsong/dfxml).

- Find instructions at the Creating Disk Image Reports using the
  BitCurator Reporting Tool **Step-by-Step Guide**.

- Use of the Reporting Tool is also covered in the [<u>Quickstart
  Guide</u>](https://github.com/BitCurator/bitcurator-distro/wiki/Releases#quickstart-guide).

[**<u>Brunnhilde</u>**](https://github.com/tw4l/brunnhilde): Generates
aggregate reports of files in a directory or disk image based on input
from Richard Lehane's
[<u>Siegfried</u>](http://www.itforarchivists.com/siegfried).

[**bulk_extractor Viewer
(BEViewer)**](https://github.com/simsong/bulk_extractor/wiki/BEViewer):
A GUI front-end for
[<u>bulk_extractor</u>](https://github.com/simsong/bulk_extractor)

- See the [<u>Bulk Extractor
  Viewer</u>](https://confluence.educopia.org/display/~aberish/Bulk+Extractor+Viewer)
  **Step-by-Step Guide**.

- See the [<u>Regular Expressions in Bulk
  Extractor</u>](https://confluence.educopia.org/display/~aberish/Regular+Expressions+in+Bulk+Extractor)
  **Step-by-Step Guide**.

- bulk_extractor is a critical component of the [<u>Annotated Features
  Report</u>](https://confluence.educopia.org/display/~aberish/Annotated+Features+Report)
  **Step-by-Step Guide**.

**[<u>Disktype</u>](http://disktype.sourceforge.net/):** Detects the
content format of a disk or disk image

[**<u>Fiwalk</u>**](https://forensicswiki.xyz/wiki/index.php?title=Fiwalk):
Fiwalk is part of [<u>The Sleuth
Kit's</u>](https://www.sleuthkit.org/sleuthkit/) collection of digital
forensics tools and is used to produce a DFXML (Digital Forensics XML)
report on the contents of a disk image within the **BitCurator Reporting
Tool**.

- See the
  [<u>fiwalk</u>](https://confluence.educopia.org/display/~aberish/Fiwalk)
  **Step-by-Step Guide**.

[**<u>md5deep</u>**](http://md5deep.sourceforge.net/): Set of programs
to compute MD5, SHA-1, SHA-256, Tiger, or Whirlpool message digests on
an arbitrary number of files

[**<u>nsrllookup</u>**](http://rjhansen.github.io/nsrllookup/): Query
tool to check for a matching MD5 hash in the National Software Reference
Library Reference Data Set

[**<u>PhotoRec</u>**](https://www.cgsecurity.org/wiki/PhotoRec): File
data recovery software designed to recover lost files including video,
documents and archives from hard disks, CD-ROMs, and lost pictures from
digital camera memory

[**<u>RegRipper</u>**](https://github.com/keydet89/RegRipper2.8): Tool
for extracting and parsing information (keys, values, data) from the
Windows Registry

[**SDHash**](http://roussev.net/sdhash/sdhash.html): File similarity
tool using similarity digests

[**ssdeep**](https://ssdeep-project.github.io/ssdeep/index.html): Fast
hash generation

[**<u>TestDisk</u>**](https://www.cgsecurity.org/wiki/TestDisk): Data
recovery software with focus on recovering lost partitions, making
non-booting disks bootable again/partition table recovery

**Packaging and Transfer**

[**<u>BagIt Python
Library</u>**](https://github.com/LibraryOfCongress/bagit-python):
Command line implementation of the BagIt specification

[**<u>Grsync</u>**](https://sourceforge.net/projects/grsync/): GUI
fronted for the rysnc command line tool to synchronize or transfer data
between locations

### **Additional tools**

[**<u>Antiword</u>**](http://www.winfield.demon.nl/): Converts the
Microsoft Word 2, 6, 7, 97, 2000, 2002 and 2003 formats to plain text
and PostScript

**BitCurator Reports** (command line): Command line implementation of
the **BitCurator Reporting Tool**, see GUI entry under the *Forensic
analysis tools* section

[**<u>Bless Hex Editor</u>**](https://github.com/bwrsandman/Bless): Hex
editor to edit and view files as a sequence of bytes

[**ClamTK**](https://dave-theunsub.github.io/clamtk/): Virus scanning

[**<u>FIDO Format
Identification</u>**](https://openpreservation.org/technology/products/fido/):
Command line tool to identify the file formats of digital objects,
designed for integration into automated workflows

[**Fiwalk**](https://forensicswiki.xyz/wiki/index.php?title=Fiwalk)
(command line): Fiwalk is part of [<u>The Sleuth
Kit's</u>](https://www.sleuthkit.org/sleuthkit/) collection of digital
forensics tools and is used to produce a DFXML (Digital Forensics XML)
report on the contents of a disk image within the **BitCurator Reporting
Tool**.

- See the
  [<u>fiwalk</u>](https://confluence.educopia.org/display/~aberish/Fiwalk)
  **Step-by-Step Guide**.

[**GHex**](https://developer.gnome.org/ghex/): A hex viewer/editor

[**GtkHash**](http://gtkhash.sourceforge.net/): A cryptographic hashing
tool

[**<u>Hashrat</u>**](https://github.com/ColumPaget/Hashrat): Hashing
tool supporting MD5, SHA1, SAH256, SHA512, Whirlpool, JH and HMAC
versions of these. Includes recursive file hashing and other features.

**<u>[H](https://www.mars.org/home/rob/proj/hfs/)[FS
Explorer](http://www.catacombae.org/hfsexplorer/)</u>**: Provides access
to the legacy HFS file systems

- See the [<u>View and export information from HFS-formatted disk
  images</u>](https://confluence.educopia.org/display/BC/View+and+export+information+from+HFS-formatted+disk+images)
  **Step-by-Step Guide**.

**Match BE Features to File Names**: Command line implementation of the
**BitCurator Reporting Tool** function

[**<u>nwipe</u>**](https://github.com/martijnvanbrummelen/nwipe):
Securely erase disks

[**<u>Read Outlook PST File</u>**](https://www.five-ten-sg.com/libpst/):
A utility for reading and exporting the contents of PST files.

**System Profiler and Benchmark**: Link to the native system information
tool

[**<u>VLC media player</u>**](https://www.videolan.org/vlc/index.html):
Multimedia player and framework that plays most multimedia files as well
as DVDs, audio CDs, VCDs, and various streaming protocols.

**If you would like to provide feedback for this page, please follow
this** **[<u>link to the BitCurator Wiki Google
Form</u>](https://docs.google.com/forms/d/e/1FAIpQLScp7yt_CTLijHqSOzCtOy3gFJs0ZqJHBgBVO6SXadB-vsTA0A/viewform?usp=sf_link)
for the Tools section.**
