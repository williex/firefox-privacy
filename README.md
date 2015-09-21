# firefox-privacy

firefox-disable-sponsored-tiles.patch
This patch disables sponsored tiles in the "new tab" page. The new tab page is reverted to the version from Firefox 38. It also hardcodes the ping (tile) URLs to nothing and sets most functions that get data to return nothing instead of connecting to mozilla.

firefox-disable-pocket-loop.patch
Disable building the pocket plugin and firefox hello. These two programs should not be bundled with the browser, but installed as separate addons.
