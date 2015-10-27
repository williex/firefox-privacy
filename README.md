# firefox-privacy

#firefox-disable-sponsored-tiles.patch
This patch disables sponsored tiles in the "new tab" page. The new tab page is reverted to the version from Firefox 38. It also hardcodes the ping (tile) URLs to nothing and sets most functions that get data to return nothing instead of connecting to mozilla.

#firefox-disable-pocket-loop.patch
Disable building the pocket plugin and firefox hello. These two programs should not be bundled with the browser, but installed as separate addons.

#firefox-38-mozconfig
Privacy friendly mozconfig settings. Copy to the extracted source dir and name mozconfig

#firefox-38-prefs.patch
Set some sensible defaults, see the patch for details. Most important changes are disabling healthreport services and disable going to an URL when you paste somewhere in a webpage
