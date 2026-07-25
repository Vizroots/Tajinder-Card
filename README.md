# Vizroots card — GitHub Pages

## Fast path (5 minutes, all in the browser)

1. github.com -> **New repository**
   - Name: **card**  (short, so your URL stays short)
   - **Public** (required for free Pages)
   - Create repository
2. On the new repo page: **uploading an existing file**
3. Drag in ALL files from this folder: index.html, card-a.html, card.vcf, .nojekyll
4. **Commit changes**
5. **Settings -> Pages** -> Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** -> Save
6. Wait 1-2 minutes, then open:

       https://<your-username>.github.io/card/

## Your URLs

| URL | What |
|---|---|
| https://<username>.github.io/card/ | Card B (QR appears when you tap your photo) |
| https://<username>.github.io/card/card-a.html | Card A (QR always visible) |
| https://<username>.github.io/card/card.vcf | Contact file WITH your photo |

## On your phone

Open the URL in Safari -> **Share -> Add to Home Screen**. It launches
full-screen like an app.

## Later: point the QR at the hosted contact (adds your photo)

Right now the QR carries your details directly, so it works with no signal.
Once Pages is live and you have confirmed the .vcf URL loads, set the card's
**vcardUrl** to:

    <username>.github.io/card/card.vcf

Then the QR becomes a short link, the saved contact includes your photo, and you
can update your details later by replacing card.vcf — every card already shared
keeps working.

## Moving to vizroots.com afterwards

Same three files work on your own domain. Either point a CNAME at Pages, or
upload them to your web host and use vizroots.com/card.
