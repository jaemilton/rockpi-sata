<div id="mw-content-text" lang="en" dir="ltr" class="mw-content-ltr"><div class="hf-nsheader"></div><div class="hf-header"></div><div class="col-md-12">
<div class="btn btn-primary pull-right"><i class="fa fa-language"></i> <strong class="selflink">English</strong></div> 
<div class="btn btn-primary pull-right"><i class="fa fa-language"></i> <a href="/mw/index.php?title=Dual_Quad_SATA_HAT/zh_cn&amp;action=edit&amp;redlink=1" class="new" title="Dual Quad SATA HAT/zh cn (page does not exist)">中文（中国大陆）‎</a></div> 
<div class="btn btn-primary pull-right"><i class="fa fa-language"></i> <a href="/mw/index.php?title=Dual_Quad_SATA_HAT/es_es&amp;action=edit&amp;redlink=1" class="new" title="Dual Quad SATA HAT/es es (page does not exist)">español</a></div> 
<div class="btn btn-primary pull-right"><i class="fa fa-language"></i> <a href="/mw/index.php?title=Dual_Quad_SATA_HAT/de_DE&amp;action=edit&amp;redlink=1" class="new" title="Dual Quad SATA HAT/de DE (page does not exist)">Deutsch</a></div> 
<div class="btn btn-primary pull-right"><i class="fa fa-language"></i> <a href="/mw/index.php?title=Dual_Quad_SATA_HAT/pt_BR&amp;action=edit&amp;redlink=1" class="new" title="Dual Quad SATA HAT/pt BR (page does not exist)">português do Brasil</a></div>
<div class="box-Title"></div>
</div>
<pre>   <a href="/Home" title="Home"> Home</a> &gt; <a href="/SATA_HAT" title="SATA HAT"> SATA HAT</a> &gt; <strong class="selflink"> Dual/Quad SATA HAT</strong>
</pre>
<h3><span class="mw-headline" id="Introduction">Introduction</span></h3>
<div id="toc" class="toc"><div id="toctitle"><h2>Contents</h2><span class="toctoggle">&nbsp;[<a href="#" class="internal" id="togglelink">hide</a>]&nbsp;</span></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="#Introduction"><span class="tocnumber">1</span> <span class="toctext">Introduction</span></a></li>
<li class="toclevel-1 tocsection-2"><a href="#Software_support"><span class="tocnumber">2</span> <span class="toctext">Software support</span></a></li>
<li class="toclevel-1 tocsection-3"><a href="#Upgrade_firmware"><span class="tocnumber">3</span> <span class="toctext">Upgrade firmware</span></a></li>
<li class="toclevel-1 tocsection-4"><a href="#NAS_support.28optional.29"><span class="tocnumber">4</span> <span class="toctext">NAS support(optional)</span></a>
<ul>
<li class="toclevel-2 tocsection-5"><a href="#OpenMediaVault"><span class="tocnumber">4.1</span> <span class="toctext">OpenMediaVault</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-6"><a href="#RTC_support.28optional.29"><span class="tocnumber">5</span> <span class="toctext">RTC support(optional)</span></a></li>
<li class="toclevel-1 tocsection-7"><a href="#Supplied_with_this_product"><span class="tocnumber">6</span> <span class="toctext">Supplied with this product</span></a>
<ul>
<li class="toclevel-2 tocsection-8"><a href="#Dual_version"><span class="tocnumber">6.1</span> <span class="toctext">Dual version</span></a></li>
<li class="toclevel-2 tocsection-9"><a href="#Quad_version"><span class="tocnumber">6.2</span> <span class="toctext">Quad version</span></a></li>
<li class="toclevel-2 tocsection-10"><a href="#SATA_HAT_Top_board.28Optional.29"><span class="tocnumber">6.3</span> <span class="toctext">SATA HAT Top board(Optional)</span></a></li>
<li class="toclevel-2 tocsection-11"><a href="#Metal_Case.28Optional.29"><span class="tocnumber">6.4</span> <span class="toctext">Metal Case(Optional)</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-12"><a href="#Other_hardware_needed"><span class="tocnumber">7</span> <span class="toctext">Other hardware needed</span></a></li>
<li class="toclevel-1 tocsection-13"><a href="#Model_Number"><span class="tocnumber">8</span> <span class="toctext">Model Number</span></a></li>
<li class="toclevel-1 tocsection-14"><a href="#PINOUT"><span class="tocnumber">9</span> <span class="toctext">PINOUT</span></a></li>
<li class="toclevel-1 tocsection-15"><a href="#Getting_Started"><span class="tocnumber">10</span> <span class="toctext">Getting Started</span></a>
<ul>
<li class="toclevel-2 tocsection-16"><a href="#Assemble_the_Kits"><span class="tocnumber">10.1</span> <span class="toctext">Assemble the Kits</span></a></li>
<li class="toclevel-2 tocsection-17"><a href="#Full_Setup_Quad_Sata_Hat_for_Raspberry_Pi_4_NAS_Review"><span class="tocnumber">10.2</span> <span class="toctext">Full Setup Quad Sata Hat for Raspberry Pi 4 NAS Review</span></a></li>
<li class="toclevel-2 tocsection-18"><a href="#Detail_of_the_HAT_board"><span class="tocnumber">10.3</span> <span class="toctext">Detail of the HAT board</span></a></li>
<li class="toclevel-2 tocsection-19"><a href="#Power_Options"><span class="tocnumber">10.4</span> <span class="toctext">Power Options</span></a>
<ul>
<li class="toclevel-3 tocsection-20"><a href="#Option_1:_Powering_from_Raspberry_Pi.2FROCK_Pi_40P_GPIO_header"><span class="tocnumber">10.4.1</span> <span class="toctext">Option 1: Powering from Raspberry Pi/ROCK Pi 40P GPIO header</span></a></li>
<li class="toclevel-3 tocsection-21"><a href="#Option_2:_Powering_from_USB_C_or_DC_Jack_on_SATA_HAT"><span class="tocnumber">10.4.2</span> <span class="toctext">Option 2: Powering from USB C or DC Jack on SATA HAT</span></a></li>
<li class="toclevel-3 tocsection-22"><a href="#Option_3:_Powering_from_ATX_PSU"><span class="tocnumber">10.4.3</span> <span class="toctext">Option 3: Powering from ATX PSU</span></a></li>
</ul>
</li>
</ul>
</li>
<li class="toclevel-1 tocsection-23"><a href="#Software_configuration"><span class="tocnumber">11</span> <span class="toctext">Software configuration</span></a></li>
<li class="toclevel-1 tocsection-24"><a href="#SATA_HAT_Firmware_Update"><span class="tocnumber">12</span> <span class="toctext">SATA HAT Firmware Update</span></a></li>
<li class="toclevel-1 tocsection-25"><a href="#Troubleshooting"><span class="tocnumber">13</span> <span class="toctext">Troubleshooting</span></a></li>
<li class="toclevel-1 tocsection-26"><a href="#Dimensions"><span class="tocnumber">14</span> <span class="toctext">Dimensions</span></a></li>
<li class="toclevel-1 tocsection-27"><a href="#Hardware_Revision"><span class="tocnumber">15</span> <span class="toctext">Hardware Revision</span></a></li>
</ul>
</div>

<p>ROCK Pi Dual/Quad SATA HAT is an addon HAT designed for Raspberry Pi 4. It utilizes the high-speed USB3 buses on Raspberry Pi 4 and providing a complete NAS solution based on Raspberry Pi 4. It has the following features:
</p>
<ul>
<li> Up to 4x HDD/SSD, support 2.5inch or 3.5inch SSD
</li>
<li> Utilize two independent USB3 buses on Raspberry Pi 4
</li>
<li> Type C power input with USB PD support for both 2.5inch SSD and Raspberry Pi 4(v1.1 hardware)
</li>
<li> 12V DC power input for 2.5 and 3.5 inch HDD and Raspberry Pi 4(v1.2 hardware)
</li>
<li> External standard ATX power supply support for 3.5inch HDD
</li>
<li> Support HDD suspend mode
</li>
<li> Support software RAID 0/1/5
</li>
<li> Support USB Direct Access Mode from PC
</li>
<li> Optional PWM control fan for HDD heat dispatching
</li>
<li> Optional OLED display for IP/Storage info
</li>
</ul>
<p><a href="/File:Quad_sata_hat_angle.png" class="image"><img alt="Quad sata hat angle.png" src="/mw/images/thumb/b/b0/Quad_sata_hat_angle.png/500px-Quad_sata_hat_angle.png" width="500" height="375" srcset="/mw/images/thumb/b/b0/Quad_sata_hat_angle.png/750px-Quad_sata_hat_angle.png 1.5x, /mw/images/b/b0/Quad_sata_hat_angle.png 2x"></a>
</p>
<h3><span class="mw-headline" id="Software_support">Software support</span></h3>
<p>We provide an install script to help you get the SATA software that works in Raspberry Pi 4B.
</p><p><a href="/File:Get-rockpi-sata.png" class="image"><img alt="Get-rockpi-sata.png" src="/mw/images/a/ae/Get-rockpi-sata.png" width="734" height="611"></a>
</p>
<pre>curl -sL <a rel="nofollow" class="external free" href="https://rock.sh/get-rockpi-sata">https://rock.sh/get-rockpi-sata</a> | sudo -E bash -
</pre>
<p>Just copy the command above and paste it into the terminal and press enter. If you want more settings, check out section  Software Configuration at the bottom of the page.
</p>
<h3><span class="mw-headline" id="Upgrade_firmware">Upgrade firmware</span></h3>
<p>1. <a rel="nofollow" class="external text" href="https://forum.radxa.com/t/how-to-upgrade-f-w-with-jms561-under-raspberry-pi/3560">How to upgrade F/W with jms561 under Raspberry Pi</a>
</p><p>2. <a rel="nofollow" class="external text" href="https://forum.radxa.com/t/how-to-upgrade-f-w-with-jms561-under-windows/4437">How to upgrade F/W with jms561 under Windows</a> (recommend)
</p>
<h3><span class="mw-headline" id="NAS_support.28optional.29">NAS support(optional)</span></h3>
<h5><span class="mw-headline" id="OpenMediaVault">OpenMediaVault</span></h5>
<p>Install: <a rel="nofollow" class="external text" href="https://github.com/OpenMediaVault-Plugin-Developers/docs/blob/master/Adden-B-Installing_OMV5_on_an%20R-PI.pdf">Installing OMV5 on Raspberry PI's</a>
</p><p>Troubleshooting: 
</p><p>1. <a rel="nofollow" class="external text" href="https://forum.radxa.com/t/quad-sata-kit-and-openmediavault-5-raspberry-pi-4/3193">OMV WebUI only shows two HDD's</a>
</p><p>This is likely because JMicron controllers incorrectly report identical serial numbers and other data which confuses various systems.
</p><p>You can “fix” this by adding a rule to /lib/udev/rules.d/60-persistent-storage.rules <b>after</b> the entry for <b>“Fall back usb_id for USB devices”</b>:
</p>
<pre>   # Fix Quad SATA HAT disk serial number
   KERNEL=="sd*", ATTRS{idVendor}=="1058", ATTRS{idProduct}=="0a10", SUBSYSTEMS=="usb", PROGRAM="/root/serial.sh&nbsp;%k", ENV{ID_SERIAL}="USB-%c", ENV{ID_SERIAL_SHORT}="%c"
</pre>
<p>You will also need to create <b>/root/serial.sh</b> containing the following:
</p>
<pre>   #!/bin/bash
   /sbin/hdparm -I /dev/$1 | grep 'Serial Number' | awk '{print $3}'
</pre>
<p><br>
And you need to add execute permission to the file via the following:
</p>
<pre>   chmod +x /root/serial.sh
</pre>
<p><br>
Finally, install the hdparm.
</p>
<pre>   sudo apt-get install hdparm
</pre>
<p>This will ensure that unique paths are created based on the serial number of the actual drives and not the hat.
</p>
<h3><span class="mw-headline" id="RTC_support.28optional.29">RTC support(optional)</span></h3>
<p>In version 1.2, we added RTC functionality. If you want to use the RTC, you will need to install a battery (socket next to the fan). For Raspbian, you can do this to enable RTC:
</p><p>Add <b>dtoverlay=i2c-rtc,pcf8563</b> to the /boot/config.txt and reboot. Execute <b>sudo hwclock -w</b> after reboot.
</p><p><a href="/File:Rtc-battery.jpeg" class="image"><img alt="Rtc-battery.jpeg" src="/mw/images/thumb/3/39/Rtc-battery.jpeg/400px-Rtc-battery.jpeg" width="400" height="200" srcset="/mw/images/thumb/3/39/Rtc-battery.jpeg/600px-Rtc-battery.jpeg 1.5x, /mw/images/thumb/3/39/Rtc-battery.jpeg/800px-Rtc-battery.jpeg 2x"></a>
</p>
<h3><span class="mw-headline" id="Supplied_with_this_product">Supplied with this product</span></h3>
<h4><span class="mw-headline" id="Dual_version">Dual version</span></h4>
<ul>
<li> ROCK Pi Dual SATA HAT
</li>
<li> Mechanical spacers
</li>
<li> 2x USB 3.0 connection adapter *1
</li>
<li> CPU heatsink with fan(DF4 version only)
</li>
</ul>
<h4><span class="mw-headline" id="Quad_version">Quad version</span></h4>
<ul>
<li> ROCK Pi Quad SATA HAT
</li>
<li> Mechanical spacers
</li>
<li> 4x USB 3.0 connection adapter *1
</li>
<li> CPU heatsink with fan(DF4 version only)
</li>
</ul>
<p><br>
</p>
<h4><span class="mw-headline" id="SATA_HAT_Top_board.28Optional.29">SATA HAT Top board(Optional)</span></h4>
<ul>
<li> 0.91inch OLED
</li>
<li> One GPIO button
</li>
<li> PWM controlled 40x40mm FAN
</li>
</ul>
<p><a href="/File:Sata_hat_top_board.png" class="image"><img alt="Sata hat top board.png" src="/mw/images/thumb/7/72/Sata_hat_top_board.png/500px-Sata_hat_top_board.png" width="500" height="341" srcset="/mw/images/thumb/7/72/Sata_hat_top_board.png/750px-Sata_hat_top_board.png 1.5x, /mw/images/7/72/Sata_hat_top_board.png 2x"></a>
</p>
<h4><span class="mw-headline" id="Metal_Case.28Optional.29">Metal Case(Optional)</span></h4>
<ul>
<li> Holds up to four 2.5 inch HDDs/SSDs
</li>
<li> Supports top board
</li>
<li> Top acrylic cover for OLED display
</li>
<li> Support fan for HDD heat dispatching air flow
</li>
<li> One button for powering off and OLED info switch
</li>
</ul>
<p><a href="/File:Quad_sata_case_coke.jpeg" class="image"><img alt="Quad sata case coke.jpeg" src="/mw/images/thumb/9/9e/Quad_sata_case_coke.jpeg/500px-Quad_sata_case_coke.jpeg" width="500" height="710" srcset="/mw/images/thumb/9/9e/Quad_sata_case_coke.jpeg/750px-Quad_sata_case_coke.jpeg 1.5x, /mw/images/9/9e/Quad_sata_case_coke.jpeg 2x"></a>
</p>
<h3><span class="mw-headline" id="Other_hardware_needed">Other hardware needed</span></h3>
<ul>
<li> Proper power adapter(Check power options below for more info)
</li>
<li> 2.5inch or 3.5inch HDD/SSD
</li>
<li> Raspberry Pi 4 or ROCK Pi 4 with OS running
</li>
<li> optional 7+15P SATA cable(For 3.5inch HDD or extending the length)
</li>
</ul>
<h3><span class="mw-headline" id="Model_Number">Model Number</span></h3>
<p>Since the Raspberry Pi 4 changes the form factor(swapping USB and RJ45), we need a different USB connection adapter. The ROCK Pi 4 shares form factor with Raspberry Pi 3/3B+.  Below is the different model number:
</p>
<table class="wikitable" border="1">

<tbody><tr>
<th> Model
</th>
<th> Description
</th></tr>
<tr>
<td> DF4
</td>
<td> Dual version for Raspberry Pi 4
</td></tr>
<tr>
<td> QF3
</td>
<td> Quad version for ROCK Pi 4, Raspberry Pi 3/3B+
</td></tr>
<tr>
<td> QF4
</td>
<td> Quad version for Raspberry Pi 4
</td></tr></tbody></table>
<h3><span class="mw-headline" id="PINOUT">PINOUT</span></h3>
<p>Pinout for 40PIN GPIO header
</p>
<table class="wikitable">
<tbody><tr>
<th style="text-align: center;"> Description
</th>
<th style="text-align: center;"> Function
</th>
<th style="text-align: center;"> Pin#
</th>
<th rowspan="21">
</th>
<th style="text-align: center;"> Pin#
</th>
<th style="text-align: center;"> Function
</th>
<th style="text-align: center;"> Description
</th></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 1
</td>
<td style="text-align: center;"> 2
</td>
<td style="text-align: center;"> VCC5V0_SYS
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;"> OLED I2C
</td>
<td style="text-align: center;"> I2C_SDA
</td>
<td style="text-align: center;"> 3
</td>
<td style="text-align: center;"> 4
</td>
<td style="text-align: center;"> VCC5V0_SYS
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;"> OLED I2C
</td>
<td style="text-align: center;"> I2C_SCL
</td>
<td style="text-align: center;"> 5
</td>
<td style="text-align: center;"> 6
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 7
</td>
<td style="text-align: center;"> 8
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 9
</td>
<td style="text-align: center;"> 10
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;"> top board key
</td>
<td style="text-align: center;"> GPIO4_C2
</td>
<td style="text-align: center;"> 11
</td>
<td style="text-align: center;"> 12
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> GPIO4_C6
</td>
<td style="text-align: center;"> 13
</td>
<td style="text-align: center;"> 14
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 15
</td>
<td style="text-align: center;"> 16
</td>
<td style="text-align: center;"> GPIO4_D2
</td>
<td style="text-align: center;"> reset OLED
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 17
</td>
<td style="text-align: center;"> 18
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 19
</td>
<td style="text-align: center;"> 20
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 21
</td>
<td style="text-align: center;"> 22
</td>
<td style="text-align: center;"> GPIO_RST1
</td>
<td style="text-align: center;"> reset SATA1/2
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 23
</td>
<td style="text-align: center;"> 24
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 25
</td>
<td style="text-align: center;"> 26
</td>
<td style="text-align: center;"> ADC_IN0
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> SDA
</td>
<td style="text-align: center;"> 27
</td>
<td style="text-align: center;"> 28
</td>
<td style="text-align: center;"> SCL
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 29
</td>
<td style="text-align: center;"> 30
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 31
</td>
<td style="text-align: center;"> 32
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;"> control tb-fan speed
</td>
<td style="text-align: center;"> PWM_33
</td>
<td style="text-align: center;"> 33
</td>
<td style="text-align: center;"> 34
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 35
</td>
<td style="text-align: center;"> 36
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;"> reset SATA3/4
</td>
<td style="text-align: center;"> GPIO_RST2
</td>
<td style="text-align: center;"> 37
</td>
<td style="text-align: center;"> 38
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr>
<tr>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;"> 39
</td>
<td style="text-align: center;"> 40
</td>
<td style="text-align: center;">
</td>
<td style="text-align: center;">
</td></tr></tbody></table>
<p>Pinout for 2x5 PHD 2.0mm connector
</p>
<table class="wikitable">
<tbody><tr>
<th style="text-align: center;"> Function
</th>
<th style="text-align: center;"> Pin#
</th>
<th rowspan="6" style="text-align: center;">
</th>
<th style="text-align: center;"> Pin#
</th>
<th style="text-align: center;"> Function
</th></tr>
<tr>
<td style="text-align: center;"> I2C_SDA
</td>
<td style="text-align: center;"> 1
</td>
<td style="text-align: center;"> 2
</td>
<td style="text-align: center;"> VCC3V3_SYS
</td></tr>
<tr>
<td style="text-align: center;"> I2C_SCL
</td>
<td style="text-align: center;"> 3
</td>
<td style="text-align: center;"> 4
</td>
<td style="text-align: center;"> VCC5V0_SYS
</td></tr>
<tr>
<td style="text-align: center;"> GPIO4_D2
</td>
<td style="text-align: center;"> 5
</td>
<td style="text-align: center;"> 6
</td>
<td style="text-align: center;"> GPIO4_C2
</td></tr>
<tr>
<td style="text-align: center;"> GND
</td>
<td style="text-align: center;"> 7
</td>
<td style="text-align: center;"> 8
</td>
<td style="text-align: center;"> PWM_33
</td></tr>
<tr>
<td style="text-align: center;"> GND
</td>
<td style="text-align: center;"> 9
</td>
<td style="text-align: center;"> 10
</td>
<td style="text-align: center;"> NC
</td></tr></tbody></table>
<h3><span class="mw-headline" id="Getting_Started">Getting Started</span></h3>
<h4><span class="mw-headline" id="Assemble_the_Kits">Assemble the Kits</span></h4>
<div class="col-md-6">
           <div class="lazyYT lazyYT-image-loaded" data-youtube-id="xz-AhmjiTu8" data-ratio="16:9" style="cursor: pointer; position: relative; height: 0px; width: 100%; padding-top: 56.25%; background: url(&quot;http://img.youtube.com/vi/xz-AhmjiTu8/hqdefault.jpg&quot;) center center / cover no-repeat;"><p id="lazyYT-title-xz-AhmjiTu8" class="lazyYT-title"></p><div class="lazyYT-button"></div></div> (click image to play or watch on <a rel="nofollow" class="external text" href="https://www.youtube.com/watch?v=xz-AhmjiTu8&amp;feature=youtu.be">Youtube</a>)
</div>
<p><br>
</p>
<div class="clearfix"></div>
<h4><span class="mw-headline" id="Full_Setup_Quad_Sata_Hat_for_Raspberry_Pi_4_NAS_Review">Full Setup Quad Sata Hat for Raspberry Pi 4 NAS Review</span></h4>
<div class="col-md-6">
           <div class="lazyYT lazyYT-image-loaded" data-youtube-id="Eix0PCB0byQ" data-ratio="16:9" style="cursor: pointer; position: relative; height: 0px; width: 100%; padding-top: 56.25%; background: url(&quot;http://img.youtube.com/vi/Eix0PCB0byQ/hqdefault.jpg&quot;) center center / cover no-repeat;"><p id="lazyYT-title-Eix0PCB0byQ" class="lazyYT-title"></p><div class="lazyYT-button"></div></div> (click image to play or watch on <a rel="nofollow" class="external text" href="https://www.youtube.com/watch?v=Eix0PCB0byQ&amp;feature=youtu.be">Youtube</a>)
</div>
<p><br>
</p>
<div class="clearfix"></div>
<h4><span class="mw-headline" id="Detail_of_the_HAT_board">Detail of the HAT board</span></h4>
<p><a href="/File:Quad_sata_hat_ports.jpg" class="image"><img alt="Quad sata hat ports.jpg" src="/mw/images/thumb/6/61/Quad_sata_hat_ports.jpg/600px-Quad_sata_hat_ports.jpg" width="600" height="357" srcset="/mw/images/thumb/6/61/Quad_sata_hat_ports.jpg/900px-Quad_sata_hat_ports.jpg 1.5x, /mw/images/6/61/Quad_sata_hat_ports.jpg 2x"></a>
</p>
<h4><span class="mw-headline" id="Power_Options">Power Options</span></h4>
<p>Power consumptions for typical disks:
</p>
<table class="wikitable">
<tbody><tr>
<th>
</th>
<th> Power Consumption
</th></tr>
<tr>
<td> SSD
</td>
<td> &lt;3W
</td></tr>
<tr>
<td> 2.5 HDD
</td>
<td> 3 ~ 5W
</td></tr>
<tr>
<td> 3.5 HDD
</td>
<td> 5 ~10W
</td></tr></tbody></table>
<p>Note: the table above is for reference, check your disk label for the exact power consumption. 
More info can be found <a rel="nofollow" class="external text" href="https://linustechtips.com/main/topic/1062501-35-vs-25-hdd-power-consumption/">here</a>.
</p>
<h5><span class="mw-headline" id="Option_1:_Powering_from_Raspberry_Pi.2FROCK_Pi_40P_GPIO_header">Option 1: Powering from Raspberry Pi/ROCK Pi 40P GPIO header</span></h5>
<p>The Raspberry Pi GPIO <a rel="nofollow" class="external text" href="https://pinout.xyz/pinout/pin2_5v_power">+5V can provide up to 1.5A power</a>, the typical SSD is <a rel="nofollow" class="external text" href="https://www.anandtech.com/show/8747/samsung-ssd-850-evo-review/10">3W power consumption</a>. So you can drive up to two SSDs directly powering from Raspberry Pi with a good 5V/5A USB C power adapter.
</p><p>The ROCK Pi 4 GPIO +5V can provide up to 4A current. You can drive four SSD/HDD directly if your power adapter can provide &gt; 35W power.
</p>
<h5><span class="mw-headline" id="Option_2:_Powering_from_USB_C_or_DC_Jack_on_SATA_HAT">Option 2: Powering from USB C or DC Jack on SATA HAT</span></h5>
<p><b>V1.1 SATA HAT</b>
</p><p>For V1.1 hardware revision, we use USB C for the power input on SATA HAT with PD/QC support. Same as option 1, you can choose USB PD power adapter &gt; 35W to drive up to four 2.5inch HDDs and Raspberry PI at the same time. 3.5inch HDD powering is not supported by the USB C port.
</p><p><b>V1.2 SATA HAT</b>
</p><p>For V1.2, we changed the power jack on SATA HAT to 12V DC because the 12V power adapter is much cheaper than the USB C PD adapter. Also, users want to power 3.5inch HDD with a power adapter instead of ATX PSU. The 12V DC jack is 5.5x2.1mm diameter. You need at least 12V/3A to power four 2.5inch HDD and 12V/5A to power four 3.5inch HDD.
</p>
<h5><span class="mw-headline" id="Option_3:_Powering_from_ATX_PSU">Option 3: Powering from ATX PSU</span></h5>
<p>If you plan to put the SATA HAT in a PC enclosure, then you can use the ATX PSU. Mostly ATX PSU can meet the power requirement. You need an ATX Floppy cable to power the SATA HAT and Raspberry Pi.
</p>
<h3><span class="mw-headline" id="Software_configuration">Software configuration</span></h3>
<p>Just edit /etc/rockpi-sata.conf, take it effect by below command
</p>
<pre>sudo systemctl restart rockpi-sata.service
</pre>
<p>Below is the default <b>/etc/rockpi-sata.conf</b>, which you can modify according to the comments
</p>
<div dir="ltr" class="mw-geshi mw-code mw-content-ltr"><div class="ini source-ini"><ol><li class="li1"><pre class="de1"><span class="re0"><span class="br0">[</span>fan<span class="br0">]</span></span></pre></li><li class="li1"><pre class="de1"># When the temperature is above lv0 <span class="br0">(</span><span class="nu0">35</span>'C<span class="br0">)</span>, the fan at <span class="nu0">25</span>% power,</pre></li><li class="li1"><pre class="de1"># and lv1 at <span class="nu0">50</span>% power, lv2 at <span class="nu0">75</span>% power, lv3 at <span class="nu0">100</span>% power.</pre></li><li class="li1"><pre class="de1"># When the temperature is below lv0, the fan is turned off.</pre></li><li class="li2"><pre class="de2"># You can change these values if necessary.</pre></li><li class="li1"><pre class="de1"><span class="re1">lv0</span> <span class="sy0">=</span><span class="re2"> 35</span></pre></li><li class="li1"><pre class="de1"><span class="re1">lv1</span> <span class="sy0">=</span><span class="re2"> 40</span></pre></li><li class="li1"><pre class="de1"><span class="re1">lv2</span> <span class="sy0">=</span><span class="re2"> 45</span></pre></li><li class="li1"><pre class="de1"><span class="re1">lv3</span> <span class="sy0">=</span><span class="re2"> 50</span></pre></li><li class="li2"><pre class="de2">&nbsp;</pre></li><li class="li1"><pre class="de1"><span class="re0"><span class="br0">[</span>key<span class="br0">]</span></span></pre></li><li class="li1"><pre class="de1"># You can customize the function of the key, currently available functions are</pre></li><li class="li1"><pre class="de1"># slider: oled display next page</pre></li><li class="li1"><pre class="de1"># switch: fan turn on/off switch</pre></li><li class="li2"><pre class="de2"># reboot, poweroff</pre></li><li class="li1"><pre class="de1"># If you have any good suggestions for key functions, </pre></li><li class="li1"><pre class="de1"># please add an issue on https://rock.sh/rockpi-sata</pre></li><li class="li1"><pre class="de1"><span class="re1">click</span> <span class="sy0">=</span><span class="re2"> slider</span></pre></li><li class="li1"><pre class="de1"><span class="re1">twice</span> <span class="sy0">=</span><span class="re2"> switch</span></pre></li><li class="li2"><pre class="de2"><span class="re1">press</span> <span class="sy0">=</span><span class="re2"> none</span></pre></li><li class="li1"><pre class="de1">&nbsp;</pre></li><li class="li1"><pre class="de1"><span class="re0"><span class="br0">[</span>time<span class="br0">]</span></span></pre></li><li class="li1"><pre class="de1"># twice: maximum time between double clicking <span class="br0">(</span>seconds<span class="br0">)</span></pre></li><li class="li1"><pre class="de1"># press: long press time <span class="br0">(</span>seconds<span class="br0">)</span></pre></li><li class="li2"><pre class="de2"><span class="re1">twice</span> <span class="sy0">=</span><span class="re2"> 0.7</span></pre></li><li class="li1"><pre class="de1"><span class="re1">press</span> <span class="sy0">=</span><span class="re2"> 1.8</span></pre></li><li class="li1"><pre class="de1">&nbsp;</pre></li><li class="li1"><pre class="de1"><span class="re0"><span class="br0">[</span>slider<span class="br0">]</span></span></pre></li><li class="li1"><pre class="de1"># Whether the oled auto display next page and the time interval <span class="br0">(</span>seconds<span class="br0">)</span></pre></li><li class="li2"><pre class="de2"><span class="re1">auto</span> <span class="sy0">=</span><span class="re2"> true</span></pre></li><li class="li1"><pre class="de1"><span class="re1">time</span> <span class="sy0">=</span><span class="re2"> 10</span></pre></li><li class="li1"><pre class="de1">&nbsp;</pre></li><li class="li1"><pre class="de1"><span class="re0"><span class="br0">[</span>oled<span class="br0">]</span></span></pre></li><li class="li1"><pre class="de1"># Whether rotate the text of oled <span class="nu0">180</span> degrees, whether use Fahrenheit</pre></li><li class="li2"><pre class="de2"><span class="re1">rotate</span> <span class="sy0">=</span><span class="re2"> false</span></pre></li><li class="li1"><pre class="de1"><span class="re1">f-temp</span> <span class="sy0">=</span><span class="re2"> false</span></pre></li></ol></div></div>
<h3><span class="mw-headline" id="SATA_HAT_Firmware_Update">SATA HAT Firmware Update</span></h3>
<p>See Forum Discussion -&gt; <a rel="nofollow" class="external text" href="https://forum.radxa.com/t/how-to-upgrade-f-w-with-jms561-under-raspberry-pi/3560">How to upgrade F/W with jms561 under Raspberry Pi</a>
</p>
<h3><span class="mw-headline" id="Troubleshooting">Troubleshooting</span></h3>
<p>1. <a rel="nofollow" class="external text" href="https://forum.radxa.com/t/quad-sata-hat-assembly-and-troubleshooting/3879">Quad SATA HAT Assembly and Troubleshooting</a>
</p>
<h3><span class="mw-headline" id="Dimensions">Dimensions</span></h3>
<h3><span class="mw-headline" id="Hardware_Revision">Hardware Revision</span></h3>

<!-- 
NewPP limit report
CPU time usage: 0.036 seconds
Real time usage: 0.044 seconds
Preprocessor visited node count: 149/1000000
Preprocessor generated node count: 293/1000000
Post‐expand include size: 731/2097152 bytes
Template argument size: 90/2097152 bytes
Highest expansion depth: 2/40
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key radxa_wiki-radxa_wiki:pcache:idhash:700-0!*!0!!en!2!* and timestamp 20201002142254 and revision id 5655
 -->
<div class="hf-footer"></div><div class="hf-nsfooter"></div></div>
