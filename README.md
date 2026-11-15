# one-eyed starfish · working document

Website: https://mileuu.github.io/one-eyed-starfish/

- One shared text document. Press **edit**, type your passkey, write, save.
- Every paragraph you add or change gets the date and your colour (Red = Bárbara, Purple = Mileu, Green = Jonathan).
- The page is `index.html` on `main`. The text lives in `doc.json` on the `data` branch; every save is a commit, so old versions can always be restored.
- `keys.json` (on `data`) holds the GitHub key, encrypted once per passkey. The passkeys themselves aren't stored anywhere.
- `?local` in the URL turns on a test mode that only saves in your browser.
