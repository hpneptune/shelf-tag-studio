# Shelf Tag Studio updates

Version 2026.11.08h. The Shelf Tag Studio app downloads its updates from this folder.

- Put the update address (Data > App updates > Update address) to this repository's address.
- To publish a new version, upload the new files over these ones. Keep `version.json`: it lists every file
  with its size and checksum, and the app checks each download against it.
- The built-in data (pricebook, UPC database, barcode links) is deliberately left out because this repository
  is public. The app keeps the copies it already has.
