# List of Firefox Security & Privacy Addons

This is a curated list of Firefox security/privacy addons & tweaks.

## Adblockers

While many other addons listed here may have the consequence of blocking ads, these addon's primary purpose is to defeat online advertising.

* [Ublock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) - Efficient adblocker thats easy on memory
* [AdNauseam](https://addons.mozilla.org/en-US/firefox/addon/adnauseam/) - Based on UBlock Origin, with the bonus of automatically 'clicking' ads it encounters in the background, obscuring your clickstream.

## Tracking Protection

* [Privacy Badger](https://addons.mozilla.org/en-us/firefox/addon/privacy-badger-firefox/) - As you browse, Privacy Badger identifies 3rd party domains that show up around the web, and tries to intelligently disable cookies or entirely block the request. You can also use its simple interface to block domains yourself, although it works pretty well 'out of the box'.
* [Ghostery](https://addons.mozilla.org/en-us/firefox/addon/ghostery/) - Another tracker blocker, allows you to block trackers by cateogory.
* [Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/) - Replaces many [CDN](https://en.wikipedia.org/wiki/Content_delivery_network) requests with locally loaded content, which speeds up your browsing and prevents some CDN tracking. Decentraleyes is missing many CDNs, however.

## HTTPS Improvements

* [HTTPS Everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/) - The name is kind of misleading, it doesn't actually make 'https' happen automatically *everywhere*, but it does force more common sites that offer HTTPS to use it.
* [Certificate Patrol](https://addons.mozilla.org/en-US/firefox/addon/certificate-patrol/) - Records website https [certificate authorities](https://en.wikipedia.org/wiki/Certificate_authority) and certificate hashes, notifying you about suspicious changes.
* [Smart HTTPS](https://addons.mozilla.org/en-US/firefox/addon/smart-https/) - Similar to HTTPS Everywhere, but works with any website that has *properly implemented* HTTPS.
* [Perspectives](https://addons.mozilla.org/en-US/firefox/addon/perspectives/) - On load of a HTTPS page, perspectives contacts your specified 'notary' servers and asks for its history of recorded certificate hashes. If you currently have a different hash than your notaries are showing, you may be experiencing a man-in-the-middle attack. Perspectives tries to be an alternative to the certificate authority system.

## Controlling Page Content & External Requests

* [NoScript](https://addons.mozilla.org/en-US/firefox/addon/noscript/) - Disables JavaScript & Flash globally, but allows you to whitelist websites/domains either permanently or temporarily.
* [uMatrix](https://addons.mozilla.org/en-US/firefox/addon/umatrix/) - Controls what types of content a website can display or request, and from what sources.
* [CookieController](https://addons.mozilla.org/en-US/firefox/addon/cookie-controller/) - Adds buttons for viewing and removing cookies for specific websites.


![This project is licensed under a Creative-Commons-Attribution-4.0 International License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)
