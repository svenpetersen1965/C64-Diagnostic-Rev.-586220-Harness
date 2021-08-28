# C64-Diagnostic-Rev.-586220-Harness
The Diagnostic Rev. 586220 is a widely accepted test tool for the Commodore C64. It tests the RAM, ROMs and 
the peripheral chips (VIC, SID, CIA). To test all interfaces, a feedback is required. This is provided by this harness.

Find more information about the cable making involved <a href="http://tech.guitarsite.de/cable_making.html">on my website</a>

# Rev. 0
<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_User_Port/Rev.0/pictures/diag586220_harness.jpg" width="300" alt="Diagnostic Harness">
<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_User_Port/Rev.0/pictures/diag586220.jpg" width="300" alt="Diagnostic 586220 running on a C64">

This repository contains all eagle files, gerber files, BOM, descriptions and cable drawings. The main documentation is contained in the User Port section.

Depending on where the parts and pcbs are purchased, the price for the complete harness is less than 20€ (2019).

Now, a 3D printed case for the user port and the cassette donge is designed and the stl files etc. are available here. 

<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Case%20(3D%20print)/Rev.%200/Picture/2649_Harness_with_case.JPG" width="300" alt="Diagnostic Harness with cases">

# Rev. 1
Revision 1 is released now. It fixes the "False OK" of the Control Port test, while the keyboard dongle is inserted. This is a phenomenon, that applies to all sorts of harnesses for Diagnostic Rev. 586220. Please refer to <a src="http://tech.guitarsite.de/c64_diag_harness.html">my website</a>

<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_User_Port/Rev.1/pictures/4035_diagnostic_harness_title.JPG" width="300" alt="Diagnostic Harness Rev. 1">

A fix for existing harnesses is the <b>extended</b> Keyboard Dongle. It can be combined with Rev. 0 of this harness and all other Harnesses. It only requires a connection to the Cassette Port Dongle. It is not required with Rev. 1 of the harness or later. 

<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_Keyboard_ext/Rev.%201/pictures/4034_Ext_KB_Dongle_title.JPG" width="300" alt="Extended keyboard Dongle">

#Keyboard dongle with 90° header
Some people want to test the C64 mainboard while being mounted. The keyboard cable connector is conflicting here. Some leave out the strain relief. This is not a great solution. A 90° boc pin header can be used insted of the vertical one. This swapps the pins, due to a different orientation. Since the symmetrical pinning of the header and the non-directional properties of the analog switches, this does not matter and is working fine. I only build this kind of KB dongle now.

<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_Keyboard/Rev.1/pictures/9053_-_Diag_KB_90deg.JPG" width="300" alt="Keyboard Dongle with 90° pin header">

# The SMD Version
This version has no functional updates compared to Rev. 2 of the UP PCB and Rev. 1 of the Cassette SMD. Some prefer building SMD assemblies (me included). It is now fully tested.

<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_User_Port/SMD_Rev.2/pictures/9049_-_Diag_UP_SMD.JPG" width="300" alt="UP PCB R1v. 2/SMD">   <img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_Cassette_Port/SMD_Rev.1/pictures/9052_-_Diag_Cass_SMD.JPG" width="300" alt="CP PCB Rev. 1/SMD">

<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Diag586220_User_Port/SMD_Rev.2/pictures/Diagnostic_SMD_Test_20210719.jpg" width="300" alt="Diagnostic test">


# Recommended Screws
For the case, I have used 2.9mm x 9.5mm (self taping) screws for sheet metal (C 2,9x9,5H, DIN 7981).  

# C128 diagnostics
They keyboard PCB for the C128 is released now and included in this repository. 

The <b>C128D-CR</b> does not provide +5V at the keyboard D-Sub jack. The keyboard dongle <b>does not work</b> here. A solution needs to be developed.  

I have noticed, that not all female D-Sub connectors provide a proper contact with the pin header on the C128 mainboard. Please keep this in mind. The recommended type is Amphenol DB25S064TLF (Digikey 609-1519-ND). 

You might want to check out the 3D printed dongle case from <a href="https://www.thingiverse.com/thing:4602956">retrorewind.ca</a>.

# Other
you might want to check Jeff Birt's <a href="https://github.com/Jeff-Birt/COREi64_Dual_Diag_Cart_Case/tree/master">case</a> for the harness, too.

Find additional info about the harness on my <a href="http://tech.guitarsite.de/c64_diag_harness.html">website</a>.

Jeff Birt provided the information of the cable lengths for C128 diagnostics. This is part of the documentation now. 

# User Port PCB Rev. 2
The user Port PCB Rev. 2 fits into the User Port Case Rev. 1. It adds an option for the SX-64: Since the SX-64 has no
Cassette Port, the Feedbacks for the CVontrol Port are not switched automatically by the software. Rev. 2 allows to
switch on the feedbacks manually. A User Port Case for thei option has been made. It incorporates a cut out for a slide
switch (standard 19mm hole pitch). This switch can be connected top JP1. For this option the cutpad has to be cut open. 

<img src="https://github.com/svenpetersen1965/C64-Diagnostic-Rev.-586220-Harness/blob/master/Diag586220_Harness/Case%20(3D%20print)/Rev.%201/User%20Port%20SX64/pictures/5460_-_User_Port_Dongle_SX-64.JPG" width="300" alt="User Port Case SX-64 option">

# Prices
The prices are calculated in May 2020. The calculation is based on the item prices from reichelt.de. They might differ from distributor to distributor. The edge connector prices are based on ebay shoppings. The calculated prices do not include any shipping fees. 

* User Port PCB plus cables and IEC dongle: 13.38€
* Cassette Port Dongle: 4.99€
* Keyboard Dongle: 1.85€
* C128 Keyboard Dongle: 3.23€

The 3D printed cases and the labels are not included in the price calculation.
