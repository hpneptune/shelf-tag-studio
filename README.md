# Shelf Tag Studio updates

Version 2026.11.08i. The Shelf Tag Studio app downloads its updates from this repository
(built-in update address: github.com/hpneptune/shelf-tag-studio).

## Publishing an update
1. Open the new-release link for the version, which fills in the tag, title and notes.
2. Attach `shelftag-github.zip` and click **Publish release**.
3. The **Publish update** action (`.github/workflows/publish.yml`) unpacks the zip into this repository.
   Phones and PCs install it the next time the app opens.

`version.json` lists every app file with its size and checksum; the app checks each download against it.
The built-in data (pricebook, UPC database, barcode links) is left out on purpose because this
repository is public. The app keeps the copies it already has.
