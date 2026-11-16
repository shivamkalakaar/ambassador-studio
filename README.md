# Ambassador Studio demo site

A one-page demo for our STRAMGT308 venture. It shows what we take in from a brand
(the brief), what the studio does, and what comes out (the ads), using Coupa Café as
the demo client. It also shows the human ambassador we tried first.

## Files
- `index.html` is the whole site.
- `videos/` holds the two mascot ads and the two Emily clips.
- `img/` holds the poster frames.

To preview it, double-click `index.html`.

## Publish on GitHub Pages

### Option 1. Let Claude Code do it (about 5 minutes)
Open a terminal in this folder, run `claude`, and paste:

> Publish this folder as a GitHub Pages site. Use the gh CLI, and run `gh auth login`
> first if I'm not logged in. Create a public repo named ambassador-studio, commit
> everything, push to main, turn on GitHub Pages from the main branch root, wait until
> the site is live, and give me the URL.

### Option 2. Do it on the GitHub website
1. Go to github.com/new, name the repo `ambassador-studio`, and make it **public**.
2. Click "uploading an existing file" and drag in everything in this folder,
   including the `videos` and `img` folders.
3. Go to Settings, then Pages. Under "Build and deployment," choose
   "Deploy from a branch," then `main` and `/ (root)`, and save.
4. After a minute or two, the site is live at
   `https://YOUR-USERNAME.github.io/ambassador-studio/`.

Every file is under 9 MB, so the website upload works.
