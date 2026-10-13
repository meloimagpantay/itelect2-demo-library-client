# itelect2-demo-library-client

The **Library client** -- the React page for the Library API, built in
ITELECT2 Session 13 with Vite and plain JavaScript.

Session 13 holds the books in the page itself (`useState` in
`src/App.jsx`) and calls no API. Session 14 replaces that array with
`GET /api/books` on the live Render address.

| File | What it does |
| ---- | ------------ |
| `src/main.jsx` | puts `<App />` into `<div id="root">` in `index.html` |
| `src/App.jsx` | holds the list of books in state, and `addBook` |
| `src/components/BookList.jsx` | one `<li>` per book |
| `src/components/BookForm.jsx` | a controlled input; calls `onAdd` with the title |

## Run it

```
npm install
npm run dev
```

Then open http://localhost:5173.
