# How to Add Content

## Adding a new blog post

1. Create a new file inside the `_posts/` folder.
2. Name it exactly like this: `YYYY-MM-DD-a-short-title.md` (e.g. `2026-09-02-fake-invoice-scams.md`). The date in the filename controls when it's sorted on the blog — use today's date (or the date you want it to appear as published).
3. At the very top of the file, paste this block and fill it in (the `---` lines are required exactly as shown):

   ```
   ---
   title: "Your Post Title Here"
   excerpt: "One sentence describing the post, shown in previews."
   tags: [social-engineering]
   ---
   ```

4. Write the post below that block using normal Markdown — headings with `##`, bullet points with `-`, bold with `**text**`, links with `[text](https://example.com)`, and images with `![description](/assets/images/your-image.png)`.
5. If you're adding an image, put the image file in `assets/images/` and reference it as shown above.
6. Save, commit, and push (or ask Claude Code to do this for you). The live site updates automatically within a couple of minutes.

## Adding a new educational resource/guide

Same process, but the file goes in `_resources/` instead of `_posts/`, and the filename doesn't need a date — any short, descriptive filename ending in `.md` works (e.g. `spotting-fake-websites.md`). It will automatically show up, alphabetically by title, on the [Educational Materials](https://gonephishing.org/resources/) page — you don't need to edit that page yourself.

## Keeping the changelog up to date

After making a change (new post, resource, fix, or anything else worth noting), add a short bullet to [CHANGELOG.md](CHANGELOG.md) under today's date, in plain language. If you're asking Claude Code to make the change, it should do this for you automatically.

## Things you don't need to worry about

- You never need to "build" or "compile" anything — GitHub does that automatically when you push.
- You don't need to touch `_config.yml`, the theme files, or anything outside `_posts/`, `_resources/`, and `assets/images/` for normal content updates.
