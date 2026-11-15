# FreeCell Solitaire

A standalone, browser-based FreeCell game built with React and Vite. No backend, accounts, or API keys needed.

## Run locally

```bash
npm install
npm run dev
```

## Deploy to Vercel

1. Import this GitHub repository into Vercel.
2. Framework preset: **Vite**; build command: `npm run build`; output directory: `dist`.
3. Add your custom domain in Vercel, e.g. `freecell.seoudi.net`.
4. Add the DNS record Vercel requests at your domain registrar.

## Controls

- Click a card to select it, then click a destination.
- Drag a card or a descending alternating-color sequence to a destination.
- Double-click a card to automatically move it.
- Use Undo, Redo, and Hint in the toolbar.
- Progress is stored locally in your browser.

## Rules

Build foundations from Ace to King by suit. Tableau cards stack in descending order with alternating colors. Each free cell holds one card. The number of cards movable together depends on available free cells and empty tableau columns.