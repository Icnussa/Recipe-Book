# Recipe Book

<img src="icons/icon-192.png" alt="Recipe Book icon" width="96">

A personal recipe book that runs in your phone's browser and can be added to your home screen like an app.

- **Light and dark mode.** Light is white and red, dark is charcoal and red. Tap the sun/moon button to switch.
- **Bottom tabs.** All, Desserts, Meals and Snacks.
- **Add a recipe** with the red plus button. Pick Meal, Dessert or Snack, and add a cover photo and ingredients if you like. Then write out the steps, or pick a video from your camera roll, or paste a link to a video online.
- **Search** your recipes by name or ingredient.
- **Works offline** after the first visit.

Recipes, photos and videos are saved on the device you add them on, inside the browser (IndexedDB). Nothing is uploaded anywhere.

## Put it online with GitHub Pages

1. On GitHub, open this repository and go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then press **Save**.
3. After a minute or two the address appears at the top of that page, for example `https://icnussa.github.io/Recipe-Book/`.

## Add it to your home screen

- **iPhone (Safari):** open the address, tap the **Share** button, then **Add to Home Screen**.
- **Android (Chrome):** open the address, tap the **⋮** menu, then **Add to Home screen** or **Install app**.

It then opens full screen with the chef hat icon.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app: layout, colours and code |
| `manifest.webmanifest` | App name, colours and icons for the home screen |
| `sw.js` | Lets the app open without internet |
| `icons/` | The chef hat app icon in different sizes |
