# Guest guide shell

This static GitHub Pages shell decrypts the guest guide only in a browser from a secret placed in the URL fragment. The fragment is not sent to GitHub Pages. `vault.js` contains ciphertext only.

The public site is intentionally marked `noindex,nofollow,noarchive,nosnippet`; this reduces accidental discovery but does not provide access control. Anyone who receives the complete guest link can open it.
