**Migrating BitCurator VirtualBox VM to Hyper-V**
=================================================

**Overview**
~~~~~~~~~~~~

These instructions were provided by Shelly Black, North Carolina State
University Libraries.

Note that VirtualBox VM is a cross-platform virtualization application
and Hyper-V cannot handle non-Windows operating systems.

**System Requirements for Hyper-V**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The Hyper-V role can be enabled on these versions of Windows 10:

-  Windows 10 Enterprise

-  Windows 10 Pro

-  Windows 10 Education

The Hyper-V role cannot be installed on:

-  Windows 10 Home

-  Windows 10 Mobile

-  Windows 10 Mobile Enterprise

Not a complete list, but the following items are necessary according to
`Hyper-V documentation from
Microsoft <https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/reference/hyper-v-requirements>`__:

-  64-bit Processor with Second Level Address Translation (SLAT).

-  CPU support for VM Monitor Mode Extension (VT-x on Intel CPU's).

-  Minimum of 4 GB memory.

The following items will need to be enabled in the system BIOS:

-  Virtualization Technology - may have a different label depending on
   motherboard manufacturer.

-  Hardware Enforced Data Execution Prevention.

**Migration Instructions**
~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Download BitCurator VM and Oracle Virtualbox, plus VirtualBox
Extension Pack, and ensure BitCurator opens in VirtualBox

See installing BitCurator via virtual machine instructions

2. Export .vbox to .ova using VirtualBox (“Write Manifest file” and
“Include ISO image files” should be checked)

|image1|

*Figure 1*: Within File, navigate to Export Appliance

|image2|

*Figure 2*: Select the BitCurator VM

|image3|

*Figure 3*: "Write Manifest file" and "Include ISO image files" should
be checked

3. Extract .ova in Terminal

tar -xvf BitCurator-2.2.8.ova

4. Convert .vmdk to .vhdx growable image using Starwind V2V Converter

Use `Starwind V2V
Converter <https://www.starwindsoftware.com/converter>`__, a tool for
cloning and transforming VMs from one format to another.

|image4|

*Figure 4*: Select local file as location of image to convert

|image5|

*Figure 5*: Select file name and file info

|image6|

*Figure 6*: Select local file as location of destination image

|image7|

*Figure 7*: Select VHD/VHDX Microsoft Virtual Hard Disk as destination
image format

|image8|

*Figure 8*: Select VHDX growable image as VHD/VHDX image format

5. Use Hyper-V New Virtual Machine Wizard (NOT Quick Create) and
specified Generation

|image9|

*Figure 9*: From the Action menu, navigate to New, and Virtual Machine

|image10|

*Figure 10*: Within Specify Generation menu, choose the generation of
the virtual machine

|image11|

*Figure 11*: Within Connect Virtual Hard Disk menu, select "Use an
existing virtual hard disk"

**Troubleshooting**
~~~~~~~~~~~~~~~~~~~

-  For addressing internet connectivity issues, create a `New Virtual
   Switch <https://docs.microsoft.com/en-us/windows-server/virtualization/hyper-v/get-started/create-a-virtual-switch-for-hyper-v-virtual-machines>`__
   if VM does not connect to the Default Switch used for other VMs.

-  Potential errors when extracting ova file using 7zip

   -  Converted to vhd growable image, but couldn’t open in Hyper-V when
      using Quick Create

   -  Repeated above but extracted ova in Terminal, got similar error in
      Hyper-V, even with secure boot on or off

**If you would like to provide feedback for this page, please follow
this** `link to the BitCurator Wiki Google
Form <https://docs.google.com/forms/d/e/1FAIpQLSeW9_Ri9tzXzisgBzQ26o4Ea4moDYmcKZ_f1qd9s4Ju17Yf_w/viewform?usp=sf_link>`__
**for the Installing BitCurator section.**

.. |image1| image:: ./media/image11.png
   :width: 6.5in
   :height: 3.41667in
.. |image2| image:: ./media/image5.png
   :width: 6.5in
   :height: 4.19444in
.. |image3| image:: ./media/image2.png
   :width: 6.5in
   :height: 5.23611in
.. |image4| image:: ./media/image4.png
   :width: 6.5in
   :height: 6.22222in
.. |image5| image:: ./media/image3.png
   :width: 6.5in
   :height: 5.81944in
.. |image6| image:: ./media/image10.png
   :width: 6.5in
   :height: 6.48611in
.. |image7| image:: ./media/image1.png
   :width: 6.5in
   :height: 6.48611in
.. |image8| image:: ./media/image7.png
   :width: 6.5in
   :height: 6.48611in
.. |image9| image:: ./media/image6.png
   :width: 6.5in
   :height: 4.56944in
.. |image10| image:: ./media/image8.png
   :width: 6.5in
   :height: 4.91667in
.. |image11| image:: ./media/image9.png
   :width: 6.5in
   :height: 4.91667in
