# filterlist

Website filterlist that you can use with Portmaster, personalDNSfilter and any other apps or programs that accept the same format.

# Installation
## personalDNSfilter
0. Click on the hosts-portmaster file, then click on the Raw button to open the complete file, or get the link from here: https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster
1. Open personalDNSfilter
2. Tap on 'Advanced settings'
3. Tap on 'Configure filter update'
4. At the bottom of the list, where it says <new> <new> and a crayon button, click on the blue crayon button to edit the entry
5. In 'Category' and 'Name' add whatever you like. Personally I use 'AlexTECPlayz' and 'AlexTEC`s custom filterlist'
6. In 'URL' put the 'https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster' link.
7. Tap on the 'Active' checkbox then on the Tick button
8. Exit the 'Advanced settings' part of the app
9. Tap on 'Reload filter' or 'Restart'. This will prompt personalDNSfilter to manually re-download the filter lists and build the index with all the new entries.
10. It should say 'Building index with (x) entries completed!' after it finished. Enjoy!
  
## Portmaster
0. Three ways of getting the portmaster-hosts file: Download the repository, the hosts-portmaster raw file OR open the https://raw.githubusercontent.com/alextecplayz/filterlist/main/hosts-portmaster link, CTRL+A, CTRL+C, open a text editing program, create a file with whatever naming you want, CTRL+V to paste the contents there. Save the file at your desired location. This is **important**!
1. Open Portmaster
2. Click on Settings
3. Click on 'Privacy Filter' in the sidebar, then on 'Filter Lists' or just scroll to it
4. At the 'Custom Filter List' option, you'll need to enter the file location to the file. For example, /home/(user)/filterlists/portmaster-hosts.txt (or any other file name the filterlist has)
5. Portmaster should automatically scan and add the file to memory shortly. If that doesn't work for some reason, restart Portmaster and it should work.
