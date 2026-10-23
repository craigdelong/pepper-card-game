# 🌶️ Pepper - Midwestern Bid Euchre Card Game

A complete, self-contained single-page web app for the classic Midwestern card game **Pepper**.

## How to Play Locally
1. Double-click `index.html` to open the game in any modern web browser (Google Chrome, Microsoft Edge, Safari, Firefox).
2. No internet connection, server, or software installation is required!

## How to Host Online for Free

### Option A: Netlify Drop (30 seconds)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop this folder (or the `index.html` file) directly into the upload area on Netlify.
3. You will immediately receive a live, shareable URL (e.g., `https://your-game-name.netlify.app`) that works on phones, tablets, and computers.

### Option B: GitHub Pages (Free permanent hosting)
1. Log in to [GitHub](https://github.com) and click **New Repository**.
2. Name it `pepper-card-game` and check **Public**.
3. Click **Upload an existing file** and upload `index.html`.
4. Go to **Settings → Pages**.
5. Under **Branch**, select `main` and click **Save**.
6. Your game will be live at `https://<your-username>.github.io/pepper-card-game/`.

## Pepper Rules Summary
- **Deck**: 24 cards (9, 10, J, Q, K, A in all 4 suits).
- **Players**: 4 players in two fixed partnerships (North/South vs. East/West).
- **Bowers**:
  - **Right Bower**: Jack of the trump suit (highest card in the game).
  - **Left Bower**: Jack of the same color as trump (second highest card; legally belongs to trump).
- **Auction**: Players bid on how many tricks (1 to 6) their team can win. "Little Pepper" contracts for all 6 tricks (7 pts); "Big Pepper" contracts to win all 6 tricks alone without partner's help (14 pts).
- **Exchange**: When winning a numeric or Little Pepper bid, the bidder can discard 1 unwanted card and take a blind card from their partner, who then sits out.
- **Surrender**: Defending team can surrender to prevent negative penalties if they believe the bid cannot be stopped.
- **Winning**: First team to reach 42 cumulative points wins the match!
