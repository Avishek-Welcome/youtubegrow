# youtubegrow

A simple share hub that helps real people find, watch, share and subscribe to your YouTube channel.

## What it does
- Big **Subscribe** button (opens YouTube with the subscribe prompt)
- Every video shown as a card with thumbnail, **Watch**, **WhatsApp**, **Telegram** and **Share/Copy** buttons
- Bengali labels, works well on phones
- No server, no login — just two files

## Add your videos
Edit `config.js`:

```js
window.VIDEOS = [
  { url: "https://youtu.be/VIDEO_ID", title: "Video title", note: "One-line description" },
];
```

Or open the page with `?admin` at the end of the address (e.g. `index.html?admin`), fill in the form,
then copy the generated list into `config.js`.

## Put it online (free, GitHub Pages)
1. On GitHub open **Settings → Pages**.
2. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
3. After a minute your page is live at `https://avishek-welcome.github.io/youtubegrow/`.

Share that link in your WhatsApp and Telegram groups.
