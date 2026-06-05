# Destiny Chapel — Digital Visitor Card

## Folder Structure
```
destiny-chapel/
├── index.html          ← The visitor card page
├── video/
│   └── church.mp4      ← DROP YOUR VIDEO FILE HERE (rename it to church.mp4)
└── assets/
    └── logo.png        ← Optional: replace the 🔥 emoji with your real logo
```

## How to deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `destiny-chapel-visitors`)
2. Upload all files keeping the folder structure above
3. Go to **Settings → Pages → Source → main branch → / (root)**
4. Your page will be live at: `https://yourusername.github.io/destiny-chapel-visitors/`
5. Generate a QR code from that URL and print/display it at the church entrance

## Adding your video
- Name your video file exactly: `church.mp4`
- Place it inside the `video/` folder
- The video plays automatically, muted, on loop — your visitors never need to interact with it
- If no video is found, a beautiful animated maroon gradient plays as fallback

## Adding your real logo
- Place your logo image as `assets/logo.png`
- In `index.html`, find the `.logo-box` div and replace the 🔥 emoji with:
  `<img src="assets/logo.png" style="width:38px;height:38px;object-fit:contain;" alt="Destiny Chapel" />`

## WhatsApp Admin Number
- Currently set to: 254716153771
- To change it, search for `254716153771` in index.html and replace with the correct number (country code + number, no + or spaces)

## Google Sheets Integration (next step)
- Ask your developer or Claude to add a Google Apps Script webhook
- Every form submission will auto-log to a spreadsheet
# destiny-chapel
