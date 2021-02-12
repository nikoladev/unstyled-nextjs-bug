Clone the repo and run `npm install`

## Reproducing the bug

1. Run `npm run dev`
2. Go to http://localhost:3000
    - This is how it's supposed to look
3. Stop the `dev` process
4. Run `npm run build-and-serve`
5. Go to http://localhost:3000
    - The first frame shows the icon filling the entire screen before shrinking to its correct size

- Tested on macOS.
    - On Firefox I get this on every reload.
    - On Safari I get this on every reload.
    - On Chrome I only get it on the first load. If I try to reload it doesn't happen anymore.
        - I have to open up a new tab for it to occur again.
- Tested on iOS
    - On Safari on mobile it's just like Chrome on macOS: It only happens on the first load.
        - I have to open up a new tab for it to occur again.
- Tested on Android
    - On Chrome on mobile it's just like Chrome on macOS: It only happens on the first load.
        - I have to open up a new tab for it to occur again.
    - On Firefox on mobile I get this on every reload.

