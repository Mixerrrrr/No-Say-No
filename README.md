# Catch the No

A tiny page that asks a question. **Yes** gets bigger every time you try to click **No**, and **No** runs away on little legs.

## How it works

- Type your own question by tapping the text at the top.
- Move or tap near **No** and it runs to a new spot.
- Every escape makes **Yes** bigger, until it covers the whole screen.
- Click **Yes** to get the hearts screen. **Ask again** resets everything.

The question is saved in each visitor's own browser (localStorage). Other people see the default question until they type their own.

## Files

- `index.html`: the whole page (HTML, CSS and JavaScript in one file). Fonts (Itim and Mali) load from Google Fonts.

## Change the default question

Open `index.html` and edit this line near the bottom:

```js
var DEFAULT_Q = "Will you go out with me?";
```

## Run it locally

Open `index.html` in any browser. No build step and no install.

## Deploy with GitHub Pages

1. Push `index.html` and this README to a public repo.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", choose **Deploy from a branch**, then pick `main` and `/ (root)`.
4. Wait a minute or two. The site will be at `https://YOUR-USERNAME.github.io/REPO-NAME/`.
