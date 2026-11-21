# Tania-Birthday
# A Night to Sparkle ✨

A bilingual mini site for Tânia Costa’s 45th birthday. Guests can scan the event QR code to upload their photos and view the shared album.

## Features

- **Upload photos / Enviar fotos** — opens a Dropbox file request so guests can submit photos without a Dropbox account.
- **View album / Ver álbum** — opens the shared Dropbox folder with the party photos.
- **PT / EN** — switches between Portuguese and English and remembers the guest’s language preference in their browser.

## Run locally

Open `index.html` in your browser. The HTML, CSS, JavaScript and images are all included in this single file.

## Publish with GitHub Pages

1. Upload `index.html` to the root of the repository.
2. Go to **Settings → Pages**.
3. Select **Deploy from a branch**, choose `main` and `/ (root)`, then click **Save**.
4. Use the published site URL to generate the QR code for the event card.

## Update the Dropbox links

In `index.html`, find `const links`. Update `envio` with the Dropbox file request URL and `album` with the shared folder URL. Both language versions use the same links.

Made with love for Tânia. 💋
