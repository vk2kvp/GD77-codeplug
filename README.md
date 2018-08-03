# GD77-codeplug

<b>GD77_All_AU_DMR+analog</b> - Comprehensive Australian codeplugs for Radioditty GD-77 </br>
This codeplug is based on that originally developed for TYT MD380 by Matt VK2MRC and Det VK2KVP of the Goulburn and Southern Highlands Amateur Radio Club. Graham, VK2AWS entered the analogue repeater channels. Anyone building on this Codeplug or forking, please acknowledge Matt VK2MRC, Graham VK2AWS and Det VK2KVP

<b>Hotspot/Dongle Frequencies:</b> Australian band plan assigns the following 70cm frequencies for Internet gateways:
- 439.125 (used for the DV4 channels to suit DV4mini)
- 439.150 (used for the DVm channels to suit DVmega and other MMDVM hotspots.)
- 439.175 (not allocated, but used in Z bm channels for my MMDVM Pi-Hat)

439.200 is assigned for digital simplex operation.

<b>Channel Naming Convention</b> 
- DMR-MARC and DMR+ channels are preceeded with a numeral. The numbering is random, however, all channels corresponding to a particular repeater have the same prefix numeral for ease of aggregating into zones and scan lists. 
- Brandmeister channel names are preceeded with the repeater's callsign (without the VK).
- Analogue repeaters have only one channel each and so their channel name is simply the repeater's callsign.

<b>Testing</b> These codeplugs are provided "as is" without support. Use them at your own risk. Testing has been limited to a GD-77 with Firmware v3.0.6 All editing of the codeplug has been done using using Radioddity GD-77 CPS v2.0.5

<b>Importing & Exporting from CSV files</b>. G4ELM has produced a magnificent tool to export and import all the codeplug tables. With a version of the tool for each of firmware releases 2-6-6, 2-6-8 and 3-0-6 the CSV files generated have a consistent field structure so you can easily move the complete codeplug data between CPS versions. I have used this tool to export my GD-77 All AU codeplug for FW 3-0-6, strip it down to 64 Channels and 4 Zones and successfully import the result into a codeplug for the GD-77S with FW 2-6-8. G4ELM's CSV tool is available from http://www.gb3gf.co.uk/downloads.html

<b>Re-engineered Radioddity GD-77 CPS</b>. Numerious issues exist with the CPS supplied by the manufacturer. Roger Clark has decompiled the CPS for firmware v3.0.6 and re-engineered it to overcome many of these. Details of his work and links to his CPS can be found at: http://www.rogerclark.net/re-engineered-radioddity-gd-77-cps/

<b>To use these Codeplugs:</b> Before you write these codeplugs to your radio, replace the callsign and DMR ID with your own in General settings.

<b>Release Notes - GD77_All_AU_DMR+analog_v0.6</b>
- Completed scan lists for all DMR-MARC and DMR+ repeaters (using GB3GF's CSV tool to export and import). <b>NOTE:</b> DO NOT open the Scan Lists in CSP v2.0.5 for my codeplugs from v0.6 onwards. This will destroy most of the scan lists. To edit the scan lists. Use GB3GF's CSV tool to export and import. Roger Clark's re-engineered CPS works fine and does not break the codeplug, so so you can use it to edit all the tables. 

<b>Release Notes - GD77_All_AU_DMR+analog_v0.5</b>
- Created scan lists for ACT and NSW DMR-MARC and DMR+ repeaters and set the corresponding "Scan" channel to auto scan. Added the appropriate scan list to all channels with 2x as prefix in channel name.
- Identified an issue with the 15th scan list where it would not hold the channels added. Instead the channels would revert to ones earlier in the channel list. No further scan lists added. GB3GF advised of a bug in CPS 2.0.5 limiting scan lists frequencies to 1byte (255 limit). I will make future updates using CSV files and GB3GF's CSV tool available from http://www.gb3gf.co.uk/downloads.html
- Added corresponding CSV files to this repository in GD77-All_AU_Codeplug_v0.5_csv.zip

<b>Release Notes - GD77_All_AU_DMR+analog_v0.4</b>
- Reset the VFO channels turning off Digital parameters to overcome auto transmit bug.
- Created zone for Analogue SA (Adelaide analogue repeaters)
- Created "SA Anlg Scan" channel and scan list Analogue SA for Adelaide & SE SA analogue repeaters.

<b>Release Notes - GD77_All_AU_DMR+analog_v0.3</b> 
- Number Keys assigned to Brandmeister TGs 0->505, 1-7->5051-5057, 9->50599
- Corrections to some channel names and Contact Group values were made in the codeplug using the GD-77 CPS and may not be reflected in the csv files.

<b>Release Notes - GD77_All_AU_DMR+analog_v0.2</b> 
- commenced creation of scan lists to correspond to zones

<b>Release Notes - GD77_All_AU_DMR+analog_v0.1</b> 
- used analogue channels as entered by Graham VK2AWS and sorted into alphabetical order.
- created a comprehensive list of contacts for DMR-MARC, DMR+ and Brandmeister talkgroups as well as reflectors for DMR+
- entered a selection of popular taklgroups for each of the DMR repeaters listed in the WIA Repeaters list of Oct 2017, plus all listed in the "DMR Repeaters" Android app 
- created zones for three Hotspots and each DMR repeater




