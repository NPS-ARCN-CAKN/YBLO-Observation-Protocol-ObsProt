# ARCN Loons Monitoring Park Observer Protocol (obsprot) Repository.
## National Park Service Arctic Inventory and Monitoring Network
The NPS Yellow-billed loons monitoring program relies on NPS Park Observer software for field data collection. The software uses an observation protocol (.obsprot) file to define what data is collected. This repository contains the most current .obsprot file used for loon surveys. More information on our loon monitoring program is at https://www.nps.gov/im/arcn/ybl.htm.

# How to use this obsprot
Detailed instructions on installing a Park Observer protocol file an at [http://akrgis.nps.gov/Observer/help2/install.html#protocol-install](http://akrgis.nps.gov/Observer/help2/install.html#protocol-install)

Information on .obsprot files and their specifications can be found on the Alaska Regional GIS team web site at [https://inpakrovmgis.nps.doi.net/apps/observer/](https://inpakrovmgis.nps.doi.net/apps/observer/).

# License
U.S. Government Works
Data and content created by government employees within the scope of their employment are not subject to domestic copyright protection under 17 U.S.C. § 105. Government works are by default in the U.S. Public Domain. 

# Recent changes
## Version 5, 2023-05-22 
- Changed Lake to an integer in both the Loons dialog and the HydrologyChange dialog. This change pulls up the number keyboard on the ipad instead of the text keyboard, making things a little more efficient.
- Changed Pond dialog title to HydrologyChange, which was more descriptive. Considered LakeChange which is more descriptive, but this would result in two dialogs appearing on the main screen with the letter L which is confusing. L continues to pull the Loons dialog while H pulls up the HydrologyChange dialog.

## Version 4 2023-05-19 
- Removed Waypoint from the Loons dialog, it's no longer used.
- Added in Incidental boolean checkbox to the Loons dialog to allow user to indicate 'in transit' loon observations as distinct from 'in survey' observations.
- Changed 'Lake is missing' to 'Lake is drained' in the LakeChange dialog.

