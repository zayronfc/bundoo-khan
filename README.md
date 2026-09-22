# Al Haaj Bundoo Khan NFC landing page

## The only file you normally edit
Open `links.js`.

Change:

    const MENU_URL = "PASTE-MENU-LINK-HERE";
    const REVIEW_URL = "PASTE-DIRECT-GOOGLE-REVIEW-LINK-HERE";

Commit/save the change. The buttons update, while the NFC card keeps the same landing-page URL.

## Put it on GitHub Pages
1. Create a repository (for example `bundoo-khan-nfc`).
2. Upload all four files from this folder to the repository root.
3. GitHub: Settings → Pages.
4. Under Build and deployment choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then Save.
6. Wait for the Pages URL to appear.
7. Open the URL on your phone and test both buttons.

## Program the NFC card
Write ONLY the GitHub Pages landing-page URL to the NFC tag.
Do not write the menu or review URL directly to the card.

## Important
The supplied review URL is a temporary search fallback. Replace it with the restaurant's direct Google "write a review" URL before giving the card to the restaurant.
