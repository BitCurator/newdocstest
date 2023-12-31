**Create MD5 Sums (Nautilus)**
==============================

**Overview**
~~~~~~~~~~~~

A checksum (of which MD5 sums are one type) is a string of characters
produced by an algorithm acting on a file.

The checksum is used to validate data integrity, as the algorithm will
produce a different checksum if any changes occur to the file in
question, making it easy to detect errors that may have been introduced
during the file's transmission or storage (e.g. due to physical damage,
bit rot, malicious intent, or accidental non-write-protected usage). The
sum thus acts as an identifier for the file in its exact current state.
You can calculate the sum at a point when you know your file (e.g. a
disk image) isn't corrupted or altered from how you think it should be,
and calculate the sum again at later points in time, comparing the newly
calculated sum to the original sum to check that the disk has not been
corrupted or altered. See this
`page <https://en.wikipedia.org/wiki/Checksum>`__ for more on how
checksums work.

**Step-by-Step Guide**
~~~~~~~~~~~~~~~~~~~~~~

1. Open Nautilus and navigate to the file or files for which you would
   like to calculate MD5 sums.

2. Select the desired file or files.

3. | Right click on any of the file icons and select Scripts > File
     Analysis > Calculate MD5 (see Figure 1).
   | |image1|

..

   **Figure 1**: Select "Calculate MD5" from the Nautilus script menu.

4. Select whether you would like the MD5 sum to be displayed or saved
   (if you have selected multiple files, the output will be saved by
   default) (see Figure 3).

..

   |image2|

**Figure 2**: Choose to either save or display the MD5 sum output.

5. If you chose to save the MD5 sum(s), a file listing each of the MD5's
   will be generated in your present directory. Otherwise the MD5 sum
   will be displayed in a window.

**If you would like to provide feedback for this page, please follow
this** `link to the BitCurator Wiki Google
Form <https://docs.google.com/forms/d/e/1FAIpQLSelmRx1VmgDEg3dU5_8cXZy9MZ5v8_sAl-Ur2nPFLAi6Lvu2w/viewform?usp=sf_link>`__
**for the BitCurator All Step-by-Step Guides section.**

.. |image1| image:: ./media/image2.png
   :width: 6.5in
   :height: 4.20833in
.. |image2| image:: ./media/image1.png
   :width: 6.5in
   :height: 4.72222in
