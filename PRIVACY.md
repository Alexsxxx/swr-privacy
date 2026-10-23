# Privacy Policy — SwR (Shortwave Radio)

_Last updated: 24 October 2026_

SwR ("the app") is an unofficial client for public software-defined radio
receivers (KiwiSDR, Web-888, OpenWebRX, FM-DX Webserver, UberSDR and
SpyServer), published by **Kruen s.r.o.** This policy explains what
data the app does and does not handle.

The publisher, and the data controller for the purposes of the GDPR, is:

> **Kruen s.r.o.**
> K Hajku 1714, 509 01 Nova Paka, Czech Republic
> Company ID (IČO): 09670157
> info@kruen.cz

## We do not collect personal data

The app has **no accounts, no analytics, no advertising, and no tracking**. The
developer does not collect, store, or share any personal information about you.
The app stores no personal data on your device beyond your in-app settings.

## Network connections you initiate

To do its job, the app connects to third-party services **that you choose**:

- **Public receivers** — when you connect to a receiver (KiwiSDR, Web-888,
  OpenWebRX, FM-DX Webserver, UberSDR or SpyServer), your device communicates
  directly with that volunteer-operated server. As with any internet
  connection, the server can see your IP address. The name or callsign you
  enter in the app is sent to the receivers you connect to, which commonly show
  it to the receiver's operator and other listeners - this is how these public
  receivers work. These receivers are operated by third parties and are not
  controlled by the developer.
- **Receiver lists, satellite data and broadcast schedules** — downloaded from
  the developer's own static site on GitHub Pages
  (`alexsxxx.github.io`), the same files for every user. If that site cannot
  be reached, the app asks the public registries directly instead:
  `rx.linkfanel.net`, `www.rx-888.com`, `www.receiverbook.de`,
  `servers.fmdx.org`, `instances.ubersdr.org`, `airspy.com`, and for
  satellite orbits `db.satnogs.org` and `celestrak.org`. Like any web request,
  these include your IP address.
- **Station logos** — for FM stations the app may look up a logo the
  broadcaster publishes through RadioDNS. The lookup goes through the public
  DNS-over-HTTPS services of Google (`dns.google`) and Cloudflare
  (`cloudflare-dns.com`) and then to the broadcaster's own server, so these
  can see which station's logo was asked for.
- **Map layers (Pro)** — switching on the satellite ground downloads
  imagery tiles from NASA GIBS (`gibs.earthdata.nasa.gov`) for the part of
  the world on screen, switching on the cloud layer downloads whole-planet
  cloud pictures from EUMETSAT (`view.eumetsat.int`), and switching on the
  aurora layer downloads NOAA's aurora forecast (`services.swpc.noaa.gov`) -
  both the same files for every user. The city lights layer, which is on
  unless you switch it off, also downloads sharper tiles from NASA GIBS for
  the part of the world on screen, but only when you zoom in on an area where
  it is night. Like any web request, these include your IP address.
- **Street map (Pro)** — zooming the world map in close switches to a street
  map whose tiles come from OpenFreeMap (`tiles.openfreemap.org`) for the
  part of the world on screen.
- **Aircraft (Pro)** — the Planes view asks adsb.lol (`api.adsb.lol`) for the
  aircraft around the part of the map on screen.
- **Purchases** — buying or restoring Pro is handled by Google Play or the App
  Store under their own privacy policies. The developer receives no payment
  details.

With the map layers, the street map and Planes not in use, the receiver map is
drawn offline from data bundled with the app.

The developer does not receive or log any of this traffic.

## Permissions

- **Internet** — required to stream audio and download the receiver lists.
- **Approximate location** — asked for only if you tap "use my location" while
  adding your own receiver, and used only to fill in that receiver's
  coordinates so it gets a place on the map and a country flag. The app asks
  the system for approximate location only; it is never requested at startup,
  while listening, or in the background. The coordinates go into a field you
  can edit or clear, they are stored only as part of the receiver you choose to
  save, on your device, and they are not sent anywhere. You can decline and type
  the coordinates in yourself, or leave them empty.
- **Notifications, background audio, display over other apps** — used by the
  Pro features that keep playback running when the app is not in front and that
  float the dial strip over your home screen.
- **USB** — access to a receiver dongle you physically plug in is granted by the
  system, per device, when you plug it in.

## Children

The app is a general-audience utility and is not directed at children.

## Changes

If this policy changes, the updated version will be posted at this URL with a
new "last updated" date.

## Contact

Questions about this policy: **info@kruen.cz**, or by post to Kruen s.r.o.,
K Hajku 1714, 509 01 Nova Paka, Czech Republic.
