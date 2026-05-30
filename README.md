# filterlist

Website filterlist that you can use with [BlockAds](https://f-droid.org/en/packages/app.pwhs.blockads), [Little Snitch](https://obdev.at/products/littlesnitch/index.html), [Little Snitch for Linux](https://obdev.at/products/littlesnitch-linux/index.html), [personalDNSfilter](https://www.zenz-solutions.de/personaldnsfilter-wp/) and [Portmaster](https://safing.io/) and any other apps or programs that accept the same format.

# Installation
## BlockAds
0. Click on the hosts-portmaster file, then click on the Raw button to open the complete file, or get the link from here: https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster
1. Open BlockAds
2. Tap on the 'Filter' tab
3. Scroll to the bottom of the page and tap on the '+ Add Custom Filter List' button
4. In 'Name' add whatever you like. Personally I use 'AlexTECPlayz'.
5. In 'URL (hosts format)' put the 'https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster' link.
6. Tap on the 'Add' button. Once the popup is closed, make sure the toggle for the filterlist is enabled.
7. In the top-right corner of the screen, tap 'Update all filters'. Enjoy!

## Little Snitch, Little Snitch Mini
0. Click on the hosts-portmaster file, then click on the Raw button to open the complete file, or get the link from here: https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster
1. Follow the instructions at [Little Snitch Mini - Main Window - Blocklists](https://help.obdev.at/littlesnitchmini/main-blocklists) or [Little Snitch 6 - Configuration - Manage blocklists](https://help.obdev.at/littlesnitch6/lsc-blocklists?highlight=blocklist) but use the URL you copied instead of the presets.

## Little Snitch for Linux
0. Click on the hosts-portmaster file, then click on the Raw button to open the complete file, or get the link from here: https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster
1. Navigate to the [localhost LittleSnitch for Linux page, and log in](http://localhost:3031/index.html) once LittleSnitch is up and running.
2. In the top-right corner of the page, click on the 'Blocklists' button.
3. On this new page, in the top-right corner of the 'BLOCKLISTS' pane, click on the '+' button.
4. Leave preset as 'No preset, enter your own'.
5. In 'Name' and 'Description' add whatever you like. Personally I use 'AlexTECPlayz' and 'ATP's list of stuff to block or allowlist'.
6. In 'URL' put the 'https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster' link.
7. Leave unchecked the option 'Treat as list of hostnames'
8. Leave update period to 'Every day'
9. Click on 'Save', and make sure that the checkbox next to the filterlist in the 'BLOCKLISTS' pane is checked. Enjoy!

## personalDNSfilter
0. Click on the hosts-portmaster file, then click on the Raw button to open the complete file, or get the link from here: https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster
1. Open personalDNSfilter
2. Tap on 'Advanced settings'
3. Tap on 'Configure filter update'
4. At the bottom of the list, where it says \<new> (Name column), \<new> (URL column) and a crayon button, click on the blue crayon button to edit the entry
5. In 'Category' and 'Name' add whatever you like. Personally I use 'AlexTECPlayz' and 'AlexTEC`s custom filterlist'
6. In 'URL' put the 'https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster' link.
7. Tap on the 'Active' checkbox then on the Tick button
8. Exit the 'Advanced settings' part of the app
9. Tap on 'Reload filter' or 'Restart'. This will prompt personalDNSfilter to manually re-download the filter lists and build the index with all the new entries.
10. It should say 'Building index with (x) entries completed!' after it finished. Enjoy!
  
## Portmaster
0. Three ways of getting the portmaster-hosts file: Download the repository, the hosts-portmaster raw file OR open the https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster link, right-click and choose Save As, and save it as a .txt file somewhere on your computer that Portmaster can reach.
1. Open Portmaster
2. Click on Settings
3. Click on 'Privacy Filter' in the sidebar, then on 'Filter Lists' or just scroll to it
4. At the 'Custom Filter List' option, you'll need to enter the file location to the file. For example, /home/(user)/filterlists/portmaster-hosts.txt (or any other file name the filterlist has)
5. Portmaster should automatically scan and add the file to memory shortly. If that doesn't work for some reason, restart Portmaster and it should work.
