# qrspike-scanner

This is a throwaway test page for a game-data QR export experiment. It reads a sequence of QR codes from a TV screen with the phone camera, checks and reassembles them, and shows the decoded data.

- Everything runs in the browser. Camera images and decoded data never leave the device.
- It's a static page served over HTTPS by GitHub Pages, because mobile browsers only allow camera access on secure origins.
- `vendor/jsQR.js` is [jsQR](https://github.com/cozmo/jsQR) 1.4.0, under the Apache-2.0 licence (see `vendor/jsQR.LICENSE`).

This is an unofficial fan project, not affiliated with or endorsed by ZeniMax Media or Bethesda.
