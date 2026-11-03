# Zhicheng Li · Kevin Lee

Personal homepage of Zhicheng Li (李智成), also known as Kevin Lee.

- Academic email: 23373285 AT buaa DOT edu DOT cn
- Personal email: lizhicheng2005 AT icloud DOT com
- Homepage: `index.html`
- Photo: `images/KevinLee.jpeg`

This is a static website with no build step or external dependencies.
Email addresses use AT and DOT in place of the usual symbols to discourage
simple email scrapers; there are no `mailto:` links or full addresses in metadata.

## Editing the profile

All homepage content and styles live in `index.html`. Replace the placeholder
paragraph inside `id="personal-introduction"` to add your introduction below the
portrait. Additional paragraphs can be added inside that same div; its height
grows with the text. Research and hobbies are in the labelled sections below it.
The layout adapts to narrow screens, system text size, and light/dark appearance.

## GitHub Pages

Push the changes to GitHub. In the repository, open **Settings → Pages**,
choose **Deploy from a branch**, then select **master** and **/ (root)**.
Use the public URL shown by GitHub Pages after deployment.
Once configured, pushing commits to `master` triggers deployment automatically;
a local commit alone does not update the public website.
If **Custom domain** still contains `jonbarron.info`, clear it in Pages settings.

The current repository is `KevinLeeeee323/kevinlee.github.io`, so its default
project URL is https://KevinLeeeee323.github.io/kevinlee.github.io/ .
For a root-level personal homepage, rename the repository to
`KevinLeeeee323.github.io`; its URL will then be https://KevinLeeeee323.github.io/ .

Original template assets are retained for later cleanup and are not linked from
the personal homepage.
