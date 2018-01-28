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

<b>Importing from csv files</b>. If you are using a CPS version other then v2.0.5 you can download the csv files used to create this codeplug (GD77_All_AU_DMR+analog.csv.zip) and import the Contacts and Channels into the CPS before writing to the GD-77.  NOTE that the Contacts must be imported before the Channels. Edit and merge the Channels files to suit your local requirements, but do not change the Contacts CSV - the channels depend on it.  To change a Contact value on a Channels csv, add one (+1) to the Number field value displayed int the Channels_v0.2.csv 

<b>To use these Codeplugs:</b> Before you write these codeplugs to your radio, replace the callsign and DMR ID with your own in General settings.

<b>Release Notes - GD77_All_AU_DMR+analog_v0.1</b> 
- used analogue channels as entered by Graham VK2AWS and sorted into alphabetical order.
- created a comprehensive list of contacts for DMR-MARC, DMR+ and Brandmeister talkgroups as well as reflectors for DMR+
- entered a selection of popular taklgroups for each of the DMR repeaters listed in the WIA Repeaters list of Oct 2017, plus all listed in the "DMR Repeaters" Android app 
- created zones for three Hotspots and each DMR repeater
- commenced creation of scan lists to correspond to zones
- Number Keys assigned to Brandmeister TGs 0->505, 1-7->5051-5057, 9->50599
- Corrections to some channel names and Contact Group values were made in the codeplug using the GD-77 CPS and may not be reflected in the csv files.

