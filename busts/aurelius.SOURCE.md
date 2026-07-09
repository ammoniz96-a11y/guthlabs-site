# aurelius.jpg - source and license

Copied 2026-07-09 from figures/room/aurelius-bust.jpg (same asset). Original provenance:

# Asset sources - figure room mock

## aurelius-bust.jpg

- Source file page: https://commons.wikimedia.org/wiki/File:Marcus_Aurelius_Metropolitan_Museum.png
- Original file URL (fetched from): https://upload.wikimedia.org/wikipedia/commons/c/c5/Marcus_Aurelius_Metropolitan_Museum.png
- Depicts: marble portrait bust of Marcus Aurelius, Roman Antonine period (161-180 AD), Metropolitan Museum of Art, New York.
- License: Public domain. Verified directly from the raw Commons page HTML (not just a fetch summary):
  the page carries the `PD-icon.svg` template and the license statement
  "released into the public domain by the copyright holder" (Commons license template class
  `licensetpl`, Wikidata property P275 "copyright status: released into the public domain by the
  copyright holder").
- Uploader / releasing account: User:Steerpike, uploaded 2007-08-02, Wikimedia Commons.
- Fetched: 2026-07-08, via curl direct to upload.wikimedia.org (one-time authorized download per
  Tony's instruction).
- Local processing: downloaded as PNG (561x694, 619,851 bytes), converted to JPEG at max width
  480px (final 480x593, 58,540 bytes, quality 90) using Python Pillow. Original PNG deleted after
  conversion; only the derived JPEG ships in this directory.
- Runtime use: referenced as a local file (`aurelius-bust.jpg`) in mock.html, no external request
  at runtime.

## Verification note

License was cross-checked two ways: (1) a WebFetch summary of the Commons file page reporting
"Public domain... released into the public domain by the copyright holder", and (2) a raw curl of
the same page's HTML confirming the `PD-icon` template markup and the identical P275 statement
independent of any model summarization. Both agree. This is the ONLY bust image evaluated that
carries a genuine self-released public domain claim - two other candidates found in the same
search (British Museum bust by Zubro, and a Historic Museum of Bern photo by Rosemania) are
CC BY-SA 3.0 / CC BY 2.0 respectively (attribution-required, not public domain) and were rejected
for that reason; they are not used anywhere in this build.
