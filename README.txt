YARDMAID APP - HOME SCREEN PACKAGE

What is in this folder
  index.html            The YardMaid app (guest, provider, property manager and new-provider flows)
  manifest.webmanifest  Tells the phone the app name, colors and icons
  sw.js                 Lets the app open from the home screen with a weak connection
  icons/                Home screen icons (iOS, Android, browser tab)
  store/                1024px icon for the App Store and Android adaptive icon layer, for the later native build
  source/               Editable SVG versions of the icon

To put it on a phone
  1. Upload this whole folder to any web host that serves over https
     (Netlify, Cloudflare Pages, Vercel or GitHub Pages all work and have free plans).
  2. Open the web address on the phone.
  3. iPhone (Safari): tap Share, then Add to Home Screen, then Add.
     Android (Chrome): tap the menu, then Install app (or Add to Home screen).
  4. Tap the YardMaid icon on the home screen. The app opens full screen with no browser bar.

It must be served over https. Opening index.html straight from the phone's files will not install.

This is the clickable prototype with sample data. Nothing is booked or charged, and data resets when the app is closed.
The icons in store/ are ready to use when YardMaid is rebuilt as a native app in React Native.
